# go-byteliteral

Package **byteliteral** provides more literals for Go's `byte` type; including **binary literals**.

**Note that in Go 1.13 binary literals were added to the Go programming language, which made this package obsolete.**

## Documention

Online documentation, which includes examples, can be found at: http://godoc.org/github.com/reiver/go-byteliteral

[![GoDoc](https://godoc.org/github.com/reiver/go-byteliteral?status.svg)](https://godoc.org/github.com/reiver/go-byteliteral)

## Example

Example usage:
```go
var b byte = byteliteral.B10011111
```

(This is a work around for Go not having built-in binary literals.)
