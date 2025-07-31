# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Migrated to `uv` package manager.
- Added a `main` function to each of the scripts in the examples so that they
  can be configured as project scripts using `main` as the entry point.
- Added `rgb-slider` as project script in pyproject.toml to run the rgb example.
- Added `steps-slider` as project script in pyproject.toml to run the steps example.
- Added `spinal-tap-slider` as project script in pyproject.toml to run the spinal tap example.

### Changed

- Changed build-backed from 'setuptools' to 'hatch'
- Moved project configuration and metadata from setup.cfg and setup.py to pyproject.toml

## [0.2.0] - 2025-01-24

### Added

- Enable clicking (mouse down) to quickly move the slider rather than dragging <https://github.com/TomJGooding/textual-slider/pull/46>

### Changed

- BREAKING CHANGE: The `Slider` constructor now requires optional parameters to be specified as keyword-only arguments <https://github.com/TomJGooding/textual-slider/pull/44>
- Bump the minimum Textual version to 1.0.0 <https://github.com/TomJGooding/textual-slider/pull/48>
- Update the default CSS to bring into line with other Textual widgets <https://github.com/TomJGooding/textual-slider/pull/48>

## [0.1.2] - 2023-11-27

### Fixed

- Fix the slider not showing in Textual v0.42.0 due to `min-height` change <https://github.com/TomJGooding/textual-slider/issues/39>

### Changed

- Bump the minimum Textual version to 0.42.0

## [0.1.1] - 2023-07-05

### Fixed

- Include the `py.typed` marker file in the distributed package

## [0.1.0] - 2023-06-29

- Initial release

[unreleased]: https://github.com/TomJGooding/textual-slider/compare/v0.2.0...HEAD
[0.2.0]: https://github.com/TomJGooding/textual-slider/compare/v0.1.2...v0.2.0
[0.1.2]: https://github.com/TomJGooding/textual-slider/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/TomJGooding/textual-slider/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/TomJGooding/textual-slider/commits/v0.1.0
