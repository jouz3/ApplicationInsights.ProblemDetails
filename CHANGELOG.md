# Changelog

All notable changes to this project will be documented in this file.

## [1.1.0] - 2021-06-02

### Added

- `ProblemDetailsTelemetryOptions`: new `IsFailure` option used to determine whether a ProblemDetail should be considered a success/failure
- `ProblemDetailsTelemetryOptions`: new `MergeInto` convenience method

## [1.0.2] - 2021-06-01

### Fixed

- Dimension collection not respecting `ProblemDetailsTelemetryOptions.MapDimensions`

## [1.0.1] - 2021-04-20

### Fixed

- Raw JSON ProblemDetails value not serialized correctly

## [1.0.0] - 2021-03-29

### Added

- Initial release