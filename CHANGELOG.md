<!--
SPDX-FileCopyrightText: 2020 Tuomas Siipola
SPDX-License-Identifier: AGPL-3.0-or-later
-->

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.3.1] - 2020-06-22

### Changed

- By default `--min` and `--max` are now calculated based on the given `--quality`

### Fixed

- Fix version number

## [0.3.0] - 2020-06-13

### Added

- Add `--quality` which defines a JPEG-like quality target
- Provide glibc-based Linux binary which is about 50% faster than the musl version

### Removed

- `--target` is removed, use `--quality` instead

### Fixed

- Make file extension check case-insensitive

## [0.2.1] - 2020-04-08

### Added

- More documentation
- Provide macOS binary

## [0.2.0] - 2020-02-10

### Added

- Support standard input and output

### Changed

- Output file is now specified with `--output` option

## [0.1.4] - 2019-08-25

### Changed

- Fancy output format

### Fixed

- Fix WebP SSIM calculation
- Fix program hang when input and output are same file

## [0.1.3] - 2019-08-25

### Fixed

- Fix JPEG reading

## [0.1.2] - 2019-08-25

### Added

- Add transparency support

## [0.1.1] - 2019-08-25

### Changed

- Increase WebP compression quality

## [0.1.0] - 2019-08-23

### Added

- Initial release

[0.3.1]: https://github.com/siiptuo/pio/compare/0.3.0...0.3.1
[0.3.0]: https://github.com/siiptuo/pio/compare/0.2.1...0.3.0
[0.2.1]: https://github.com/siiptuo/pio/compare/0.2.0...0.2.1
[0.2.0]: https://github.com/siiptuo/pio/compare/0.1.4...0.2.0
[0.1.4]: https://github.com/siiptuo/pio/compare/0.1.3...0.1.4
[0.1.3]: https://github.com/siiptuo/pio/compare/0.1.2...0.1.3
[0.1.2]: https://github.com/siiptuo/pio/compare/0.1.1...0.1.2
[0.1.1]: https://github.com/siiptuo/pio/compare/0.1.0...0.1.1
[0.1.0]: https://github.com/siiptuo/pio/releases/0.1.0
