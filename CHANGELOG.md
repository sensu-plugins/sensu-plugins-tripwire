#Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed at [Keep A Changelog](http://keepachangelog.com/)

## [Unreleased]

## [1.3.1] - 2020-02-21
### Changed
- Patch release to trigger new Bonsai assets

## [1.3.0] - 2020-02-21
### Changed
- Exit OK if there are only minor violations (fixing "Check did not exit!")

## [1.2.0] - 2020-02-21
### Added
- Support for a Tripwire configuration file (e.g. `--config-file tw.cfg`).

## [1.1.2] - 2020-02-18
### Changed
- Using GitHub release draft to cut a release.

## [1.1.1] - 2020-02-18
### Changed
- Added GitHub token to Travis for release artifact uploads.

## [1.1.0] - 2020-02-18
### Added
- Building Sensu Go asset release artifacts for Bonsai.

## [1.0.0] - 2017-07-09
### Added
- Ruby 2.3.0 & 2.4.1 testing (@Evesy)

### Breaking Changes
- Removed Ruby 1.9.3 support (@Evesy)

## [0.0.3] - 2015-07-14
### Changed
- updated sensu-plugin gem to 1.2.0

## [0.0.2] - 2015-06-03
### Fixed
- added binstubs

### Changed
- removed cruft from /lib

## 0.0.1 - 2015-05-20
### Added
- initial release

[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-tripwire/compare/1.0.0...HEAD
[1.0.0]: https://github.com/sensu-plugins/sensu-plugins-tripwire/compare/0.0.3...1.0.0
[0.0.3]: https://github.com/sensu-plugins/sensu-plugins-tripwire/compare/0.0.2...0.0.3
[0.0.2]: https://github.com/sensu-plugins/sensu-plugins-tripwire/compare/0.0.1...0.0.2
