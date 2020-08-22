# ble

[![GoDoc](https://godoc.org/github.com/go-ble/ble?status.svg)](https://godoc.org/github.com/go-ble/ble)
[![Go Report Card](https://goreportcard.com/badge/go-ble/ble)](https://goreportcard.com/report/go-ble/ble)
[![codebeat badge](https://codebeat.co/badges/ba9fae6e-77d2-4173-8587-36ac8756676b)](https://codebeat.co/projects/github-com-go-ble-ble-master)
[![Build Status](https://travis-ci.org/go-ble/ble.svg?branch=master)](https://travis-ci.org/go-ble/ble)

**ble** is a Golang [Bluetooth Low Energy](https://en.wikipedia.org/wiki/Bluetooth_Low_Energy) package for Linux and Mac OS.

**Note:** The Mac OS portion is not being actively maintained.

## OS-Dependant Build: ##

To find this list of possible platforms, run the following:
```
%go tool dist list

GOOS/GOARCH
-----------
aix/ppc64
android/386
android/amd64
android/arm
android/arm64
darwin/386
darwin/amd64
darwin/arm
darwin/arm64
dragonfly/amd64
freebsd/386
freebsd/amd64
freebsd/arm
illumos/amd64
js/wasm
linux/386
linux/amd64
linux/arm
linux/arm64
linux/mips
linux/mips64
linux/mips64le
linux/mipsle
linux/ppc64
linux/ppc64le
linux/s390x
nacl/386
nacl/amd64p32
nacl/arm
netbsd/386
netbsd/amd64
netbsd/arm
netbsd/arm64
openbsd/386
openbsd/amd64
openbsd/arm
openbsd/arm64
plan9/386
plan9/amd64
plan9/arm
solaris/amd64
windows/386
windows/amd64
windows/arm
```

Find current OS and ARCH
```
%go env GOOS GOARCH
darwin
amd64
```

## package dev is OS-Dependant ##  
examples/lib/dev/dev_darwin.go <== **only built in darwin OS**  
examples/lib/dev/dev_linux.go <== **only built in linux OS**  

