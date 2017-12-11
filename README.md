# go-multi-command

An example of multi-command like docker, kubectl, or helm.  It uses [Cobra](https://github.com/spf13/cobra).

## Install

```bash
$ go get github.com/jkamenik/go-multi-command
$ go get
$ go build
```

## Adding a new command

```bash
$ cobra add command
$ vi cmd/command.go
```