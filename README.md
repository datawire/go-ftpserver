# go-ftpserver: An FTP based Fuse implementation written in Go

[![Unit tests](https://github.com/datawire/go-ftpserver/actions/workflows/unit_tests.yaml/badge.svg)](https://github.com/datawire/go-ftpserver/actions/workflows/unit_tests.yaml)
[![Go Reference](https://pkg.go.dev/badge/github.com/datawire/go-ftpserver.svg)](https://pkg.go.dev/github.com/datawire/go-ftpserver)
[![Go version](https://img.shields.io/github/go-mod/go-version/datawire/go-ftpserver)](https://golang.org/doc/devel/release.html)

## Install ##

```
go get -u github.com/datawire/go-ftpserver
```

## Architecture

This is an FTP server build on [github.com/fclairamb/ftpserverlib]https://github.com/fclairamb/ftpserverlib which exposes a file system where
all symlinks have been resolved

