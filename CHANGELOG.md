# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

- `Added` for new features.
- `Changed` for changes in existing functionality.
- `Deprecated` for soon-to-be removed features.
- `Removed` for now removed features.
- `Fixed` for any bug fixes.
- `Security` in case of vulnerabilities

## [1.2.1] - 2021.08.31

### Changed

- Updated vendor libraries.

## [1.2.0] - 2020.09.15

### Added

- Added `hasDisk` method

### Changed

- Changed limitation for one disk to be required to be named `default`.
Now, the default disk is defined in the configuration array.

- All disks in the configuration array will now connect automatically when Filesystem Factory is instantiated.

## [1.1.0] - 2020.09.09

### Added

- `getDisk` method
- `getDefaultDisk` method
- `getCurrentDisk` method
- `getDiskNames` method
- `getDefaultDiskName` method
- `getCurrentDiskName` method

## [1.0.2] - 2020.08.29

### Fixed

- Fixed a bug where some thrown exceptions were not properly chained.

## [1.0.1] - 2020.08.03

### Added

- Added `FilesystemException` class which all other exceptions extend

## [1.0.0] - 2020.07.27

### Added

- Initial release.