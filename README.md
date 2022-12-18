# HIDAPI Bindings for Go

![](.github/images/gopher.png)

[![](https://github.com/sstallion/go-hid/actions/workflows/ci.yml/badge.svg?branch=master)][1]
[![](https://godoc.org/github.com/sstallion/go-hid?status.svg)][2]
[![](https://goreportcard.com/badge/github.com/sstallion/go-hid)][3]
[![](https://img.shields.io/github/v/release/sstallion/go-hid)][4]
[![](https://img.shields.io/github/license/sstallion/go-hid.svg)][5]

Package `hid` provides an idiomatic interface to HIDAPI, a simple library for
communicating with USB and Bluetooth HID devices on FreeBSD, Linux, macOS, and
Windows.

See https://github.com/libusb/hidapi for details.

## Documentation

Up-to-date documentation can be found on [GoDoc][2], or by issuing the `go doc`
command after installing the package:

    $ go doc -all github.com/sstallion/go-hid

## Installation

Package `hid` may be installed via the `go get` command:

    $ go get github.com/sstallion/go-hid@latest

>**Note**: The prerequisites for HIDAPI must be available prior to installation.
> See the HIDAPI [README][6] for details.

### lshid

An example command named `lshid` is provided, which displays information about
HID devices attached to the system. `lshid` may be installed by issuing:

    $ go get github.com/sstallion/go-hid/cmd/lshid@latest

Once installed, issue `lshid -h` to display usage.

## Contributing

Pull requests are welcome! See [CONTRIBUTING.md][7] for more details.

## License

Source code in this repository is licensed under a Simplified BSD License. See
[LICENSE][5] for more details.

[1]: https://github.com/sstallion/go-hid/actions/workflows/ci.yml
[2]: https://godoc.org/github.com/sstallion/go-hid
[3]: https://goreportcard.com/report/github.com/sstallion/go-hid
[4]: https://github.com/sstallion/go-hid/releases/latest
[5]: https://github.com/sstallion/go-hid/blob/master/LICENSE
[6]: https://github.com/libusb/hidapi/blob/master/README.txt
[7]: https://github.com/sstallion/go-hid/blob/master/CONTRIBUTING.md
