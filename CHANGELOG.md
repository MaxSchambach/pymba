# Pymba change log

## [0.3.3] - 2019/03/28
### Added
- Timeout parameter to acquire frame function.
### Changed
- MIT license.
### Fixed
- Bug fix for USB cameras trying to adjust packet size.

## [0.3.2] - 2019/03/09
### Added
- Colour camera example.
- Bug fix when attempting to open a USB camera.

## [0.3.1] - 2019/02/21
### Added
- Auto adjust packet size upon opening camera.
- Command type features can now be called directly as an object attribute.
### Changed
- Increased default frame buffer size from 3 to 10.
- Also looks in working directory for VimbaC.dll to make distribution easier.

## [0.3] - 2019/02/11
### Added
- Convenience functions for arming and acquiring single images and image streams from a camera.

## [0.2] - 2019/01/30
### Changed
- Refactored classes and module structure.
- Python 3 support only.
### Added
- Usage examples.
