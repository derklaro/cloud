# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Fixes
 - Fixes chained optionals not allowing the command to be executed when more than one optional is omitted

### Fixed
 - Fixed quoted parsing in StringArgument
 - Fixed wrong suggestions following invalid literals

## [1.0.1] - 2020-10-14

### Changes
 - Switched from a snapshot to a release version of adventure 4.0.0
 - Added `Identity.nil()` when sending adventure messages