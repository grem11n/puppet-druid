# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added
- Add extensions_dir to be compatible with Imply 1.2.x

### Changed
- Move the changelog to markdown and start using semver
- Change bard to pivot
- Default imply version changed from 1.1.0 to 1.2.1
- Change name of pivot config file from `pivot_config.yaml` to `config.yaml`

### Fixed
- Fix middleManager node
- Fix variable contains an uppercase letter puppet-lint warnings which means
  renaming parameter `druid::pivot::source_list_refresh_onLoad` to
  `druid::pivot::source_list_refresh_onload`

## [1.0.0] - 2016-03-07
### Changed
- Better service notifications
- Default imply version changed from 1.0.0 to 1.1.0

## [0.1.0] - 2016-02-15
### Added
- Initial Github commit