# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

<!---
your comment goes here
and here
## [Unreleased]
### Added

### Changed
-->

## Release 1.1.4    - 2020-07-21

### Added
- docs\examples.md add lot more examples
- engine.start(...,options)
- AppDelegate now has serviceProvider class as a separate object
- 

### Changed
- signature to service calls
  - old format: service(item);
  - new format: return=service(input,executionContext);

### Removed
-   server.cron.checktimers();