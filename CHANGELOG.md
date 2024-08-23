# Changelog

All notable changes to this project should be documented in this file.

<!--
## [Unreleased] - yyyy-month-dd

### Added
- nothing so far

### Removed
- nothing so far

### Fixed
- nothing so far

### Changed
- nothing so far
-->

## [Unreleased 0.832.0] - 2024-Aug-22

### Corresponding pytest
- This initial version of `ok` is branched from pytest 8.3.2
- Thus the "sort of makes sense" version of 0.832.0
- For now, keeping the middle digit of the version corresponding
  to the pytest version seems to make sense

### Added
- nothing so far

### Removed
- removed folders .githbub, doc, bench, extra, changelog, scripts
- removed all top level .rst files
- removed some other stuff. Nothing functional yet.

### Changed
- CHANGELOG, README, CONTRIBUTING - all changed and now .md files
- pyproject.toml - version is static now, and 0.832.0
- test_config.py - needed mods to minversion since our version changed.

### Test status
- tox -e py312 passes on my mac
- no CI set up yet
