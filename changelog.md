# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.0] - 2024-09-20

### Changed

- update to strapi v5 format

## [1.0.0] - 2024-09-13

### Added

- config validation, epoch can't be in the future

### Fixed

- fix incorrect calculation causing negative values

## [0.0.1] - 2024-09-13

### Added

- basic custom snowflake field
- auto register database hooks for snowflake fields
- custom epoch time
- snowflake service for generation and validation
- custom plugin icon
