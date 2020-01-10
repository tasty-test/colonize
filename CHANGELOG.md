# Change Log
All notable changes to the "Colonize" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [2.2.2] - 2017-03-10

### Fixed
- Mistyping in readme. Shamefully, it can't be done without bumping the version number up.

## [2.2.1] - 2017-03-10

### Changed
- Hold position command is fired with ctrl+alt+enter now. Because ctrl+enter is Visual Studio Code shortcut for insert newline below and people may be used to it.

## [2.2.0] - 2017-03-10

### Added
- Hold position command which inserts a semicolon but doesn't move cursor

## [2.1.0] - 2016-01-02

### Added
- First accepts autocomplete suggestion (if one is present) and then does its job
- [Standard](https://github.com/feross/standard) as dev dependency
- [.editorconfig](http://editorconfig.org/)

### Changed
- No matter if line contains semicolon or not cursor will move

## [2.0.0] - 2016-12-13

### Changed
- Switched from ts to js
- Start following [SemVer](http://semver.org) properly.

[Unreleased]: https://github.com/vmsynkov/colonize/compare/2.2.2...HEAD
[2.2.2]: https://github.com/vmsynkov/colonize/compare/2.2.1...2.2.2
[2.2.1]: https://github.com/vmsynkov/colonize/compare/2.2.0...2.2.1
[2.2.0]: https://github.com/vmsynkov/colonize/compare/2.1.0...2.2.0
[2.1.0]: https://github.com/vmsynkov/colonize/compare/2.0.0...2.1.0
[2.0.0]: https://github.com/vmsynkov/colonize/compare/1.0.0...2.0.0
