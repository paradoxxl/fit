# fit

[![license](http://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/paradoxxl/fit/raw/master/LICENSE)
[![GoDoc](https://godoc.org/github.com/paradoxxl/fit?status.svg)](https://godoc.org/github.com/paradoxxl/fit)
[![Travis Build Status](https://travis-ci.org/paradoxxl/fit.svg?branch=master)](https://travis-ci.org/paradoxxl/fit)

<img src="https://raw.githubusercontent.com/hackraft/gophericons/master/png/2.png" width="225" align="right" hspace="25" />

fit is a [Go](http://www.golang.org/) package that implements decoding and
encoding of the [Flexible and Interoperable Data Transfer (FIT)
Protocol](http://www.thisisant.com/resources/fit). Fit is a "compact binary
format designed for storing and sharing data from sport, fitness and health
devices". Fit files are created by newer GPS enabled Garmin sport watches and
cycling computers, such as the Forerunner/Edge/Fenix series.

The two latest versions of Go is supported. The core decoding package has no
external dependencies. The latest release of Go and a few external dependencies
are required for running the full test suite and benchmarks.

### FIT SDK Version Support

**Current supported FIT SDK version:** 20.90

**Warning:** Data Developers Fields are not yet supported (#21).

Older supported profile versions:

* 20.43
* 20.27
* 20.14
* 16.20

Other profile versions may work, but have not been tested.

### Features

* Supports all FIT file types.
* Accessors for scaled fields.
* Accessors for dynamic fields.
* Field components expansion.
* Go code generation for custom FIT product profiles.

### Installation

Using Go modules:

```
$ go get github.com/paradoxxl/fit@v0.4.0
```

Using `$GOPATH`:

```
$ go get github.com/paradoxxl/fit
```

### About fit

- [Example Usage](https://github.com/paradoxxl/fit/wiki/Example-Usage)
- [Data Types](https://github.com/paradoxxl/fit/wiki/Data-Types)
- [Main API Reference](https://github.com/paradoxxl/fit/wiki/Main-Api-Reference)
- [Custom Product Profiles](https://github.com/paradoxxl/fit/wiki/Custom-Product-Profiles)
- [Upcoming Features](https://github.com/paradoxxl/fit/wiki/Upcoming-Features)
- [Contributing](https://github.com/paradoxxl/fit/blob/master/CONTRIBUTING.md)
- [License](https://github.com/paradoxxl/fit/wiki/License)

### Contributors

- [usedbytes](https://github.com/usedbytes)
