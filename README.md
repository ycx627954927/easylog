# Easylog

A simple logger for Go, support output level.

## Installation

`go get -u github.com/winterssy/easylog`

## Quick Start

```go
package main

import "github.com/winterssy/easylog"

func main() {
	easylog.SetLevel(easylog.Ldebug)
	easylog.Debug("hello world")
	easylog.Info("hello world")
	easylog.Warn("hello world")
	easylog.Error("hello world")
}
```

## License
MIT.
