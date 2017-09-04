# Changelog

## [Unreleased]
### Added
- UUID type.
- Query limits settings.
- Code coverage.
- ClickHouse server and driver version upped to 54276.
- Changelog.
- Added column name to `TypeMismatchError`.

## [0.0.5] - 2017-07-16
### Added
- Nullable(T) type.
- Return data from TOTALS and EXTREMES packets.
- Query setting.
- query_id execution option.
- NULL type.
- Raise exception on SELECT queries.

### Changed
- Small columns refactoring.
- `clickhouse-client` in tests moved to docker.

## [0.0.4] - 2017-06-15
### Added
- FixedString(N) type.
- Enum8/16 types.
- Array(T) type.
- External data for query processing
- Raise UnknownTypeError for unsupported columns.

### Changed
- Socket connect timeout fix.

## [0.0.3] - 2017-05-24
### Added
- QuickLZ, LZ4/LZ4HC, ZSTD compressions.
- Support old servers without BlockInfo.
- Travis CI.
- flake8 syntax check.

## 0.0.2 - 2017-05-16
### Added
- [U]Int8/16/32/64 types.
- Date/DateTime types.
- String types.

[Unreleased]: https://github.com/mymarilyn/clickhouse-driver/compare/0.0.5...HEAD
[0.0.5]: https://github.com/mymarilyn/clickhouse-driver/compare/0.0.4...0.0.5
[0.0.4]: https://github.com/mymarilyn/clickhouse-driver/compare/0.0.3...0.0.4
[0.0.3]: https://github.com/mymarilyn/clickhouse-driver/compare/0.0.2...0.0.3