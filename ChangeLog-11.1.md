# Changes in PHPUnit 11.1

All notable changes of the PHPUnit 11.1 release series are documented in this file using the [Keep a CHANGELOG](https://keepachangelog.com/) principles.

## [11.1.0] - 2024-04-05

### Added

* [#5175](https://github.com/sebastianbergmann/phpunit/issues/5175): `#[CoversMethod]` and `#[UsesMethod]` attributes for more fine-grained code coverage targeting
* [#5696](https://github.com/sebastianbergmann/phpunit/pull/5696): `#[DisableReturnValueGenerationForTestDoubles]` attribute for disabling return value generation for test doubles created using `createMock()`, `createMockForIntersectionOfInterfaces()`, `createPartialMock()`, `createStub()`, and `createStubForIntersectionOfInterfaces()`
* [#5720](https://github.com/sebastianbergmann/phpunit/issues/5720): Support filtering using `--filter`, `--exclude-filter`, `--group`, and `--exclude-group` when listing tests using `--list-tests` and `--list-tests-xml` as well as listing groups with `--list-groups`
* `--only-summary-for-coverage-text` CLI option to reduce the code coverage report in text format to a summary
* `--show-uncovered-for-coverage-text` CLI option to expand the code coverage report in text format to include a list of uncovered files

### Changed

* [#5708](https://github.com/sebastianbergmann/phpunit/issues/5708): Allow the `--group`, `--exclude-group`, `--covers`, `--uses`, and `--test-suffix` CLI options to be used multiple times

### Deprecated

* [#5709](https://github.com/sebastianbergmann/phpunit/issues/5709): Deprecate support for using comma-separated values with the `--group`, `--exclude-group`, `--covers`, `--uses`, and `--test-suffix` CLI options

[11.1.0]: https://github.com/sebastianbergmann/phpunit/compare/11.0...main
