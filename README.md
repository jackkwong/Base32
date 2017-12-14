# Base32 for Swift on OS X and iOS
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![CI Status](http://img.shields.io/travis/norio-nomura/Base32.svg?style=flat)](https://travis-ci.org/norio-nomura/Base32)

Base32 is a [Base32](https://tools.ietf.org/html/rfc4648) implementation for Swift.

## Note

*Everthing is identical to the [original project](https://github.com/norio-nomura/Base32), except the slight modification to the bundle identifier, which is done to address the code signing error **App installation failed - This application’s bundle identifier does not match its code signing identifier.** when deploying on iphone (real device)

## Requirements

* iOS 8 or later
* macOS 10.9 or later
* tvOS 9 or later
* watchOS 2 or later

## Installation

### Carthage

Base32 is available through [Carthage](https://github.com/Carthage/Carthage). To install
it, simply add the following line to your Cartfile:

`github "jackkwong/Base32"`

## Author

Norio Nomura

## License

Base32 is available under the MIT license. See the LICENSE file for more info.
