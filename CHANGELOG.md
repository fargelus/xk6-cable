# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog],
and this project adheres to [Semantic Versioning].

## [Unreleased]

## [0.2.0] - 2021-11-29

### Changed
- Update k6 dependency to latest v0.35.0 release. ([@skryukov])

## [0.1.0] - 2021-09-15
### Added
- Protobuf codec support. ([@palkan])

### Fixed
- Fix setting logging level. ([@palkan])

## [0.0.3] - 2021-09-12
### Added
- Ability to change logging level with `logLevel` option. ([@palkan])

## [0.0.2] - 2021-09-10
### Added
- New `channel.ignoreReads()` method, that allows skipping collecting incoming messages. ([@palkan])
- More examples. ([@palkan])

### Changed
- Use buffered channels to receive messages. ([@palkan])


## [0.0.1] - 2021-08-19
### Added
- Initial implementation. ([@skryukov], [@palkan])

[@skryukov]: https://github.com/skryukov
[@palkan]: https://github.com/palkan

[Unreleased]: https://github.com/anycable/xk6-cable/compare/v0.2.0...HEAD
[0.2.0]: https://github.com/anycable/xk6-cable/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/anycable/xk6-cable/compare/v0.0.3...v0.1.0
[0.0.3]: https://github.com/anycable/xk6-cable/compare/v0.0.2...v0.0.3
[0.0.2]: https://github.com/anycable/xk6-cable/compare/v0.0.1...v0.0.2
[0.0.1]: https://github.com/anycable/xk6-cable/releases/tag/v0.0.1

[Keep a Changelog]: https://keepachangelog.com/en/1.0.0/
[Semantic Versioning]: https://semver.org/spec/v2.0.0.html
