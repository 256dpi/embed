# embed

[![Go Report Card](https://goreportcard.com/badge/github.com/256dpi/embed)](https://goreportcard.com/report/github.com/256dpi/embed)

**A small tool for embedding files in a Go source file.**

## Install

```
go get github.com/256dpi/embed
```

## Example

```go
//go:generate go run github.com/embed -pkg frontend -strings ./assets 
```

## Usage

```
Usage of embed:
  -const
        Whether to use constants instead of a map.
  -export
        Whether to export variables.
  -name string
        The map name. (default "files")
  -out string
        The output filename. (default "files.go")
  -pkg string
        The package name. (default "main")
  -strings
        Whether to use strings instead of byte slices.
  -strip
        Whether to strip names of path and extension.
```
