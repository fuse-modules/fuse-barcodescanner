# fuse-barcodescanner

[![NPM package](https://img.shields.io/npm/v/fuse-barcodescanner.svg?style=flat-square)](https://www.npmjs.com/package/fuse-barcodescanner)
[![License: MIT](https://img.shields.io/github/license/fuse-modules/fuse-barcodescanner.svg?style=flat-square)](LICENSE)
![Target platforms](https://img.shields.io/badge/os-Android%20%7C%20iOS-7F5AB6?style=flat-square)

BarcodeScanner package for [Fuse Open].

[Fuse Open]: https://fuseopen.com/

## Install

```shell
npm install fuse-barcodescanner
```

This will install the `BarcodeScanner` library for [Fuse SDK](https://www.npmjs.com/package/fuse-sdk).

## Usage

> To use this library in your project, you must add `"BarcodeScanner"` to `"Packages"` in your `.unoproj` file.

### Example app

> You can play around with the included [example app](https://github.com/fuse-modules/fuse-barcodescanner/tree/master/BarcodeScannerExample).

First, make sure dependencies are installed and our library is built.

```shell
npm install
npm run build
```

Then, issue one of the following commands to run the app on your desired platform.

```shell
npm run android
npm run ios
```

> Android by default uses the `zbar` library. Alternatively build with `-DZXING` to use the `zxing` library

## Contributing

Please [report an issue](https://github.com/fuse-modules/fuse-barcodescanner/issues) if you encounter a problem, or [open a pull request](https://github.com/fuse-modules/fuse-barcodescanner/pulls) if you make a patch.
