# Release Notes

## [Unreleased](https://github.com/laravel/horizon/compare/v2.2.2...master)

### Changed
- Require latest symfony/debug version ([72cc3a7](https://github.com/laravel/horizon/commit/72cc3a7e250f1f03c20b0f8e65989a3b0a7d5148))
- Require symfony/process ([f2a214c](https://github.com/laravel/horizon/commit/f2a214c65cf265a5144fb8e8472d991aa8f4e71a))
- Require ext-json ([5a54d27](https://github.com/laravel/horizon/commit/5a54d2710d4a33eb7399ddd8e31b3cbc4dcb1dc0))

### Fixed
- Fix deprecated process calls ([#515](https://github.com/laravel/horizon/pull/515))
- Add missing createPayloadArray arg ([#516](https://github.com/laravel/horizon/pull/516))

### Removed
- Removed support for Laravel 5.5 & 5.6 ([8a92e09](https://github.com/laravel/horizon/commit/8a92e099ecaad6d0a2823a89f860fd8f8fab51bf))

## [v2.2.2 (2019-02-21)](https://github.com/laravel/horizon/compare/v2.2.1...v2.2.2)

### Fixed
- Fix breaking change with `createPayload` method on `RedisQueue` ([b79bb27](https://github.com/laravel/horizon/commit/b79bb2762ed3f234125892c811d3a73d13bf66cc))

## [v2.2.1 (2019-02-15)](https://github.com/laravel/horizon/compare/v2.2.0...v2.2.1)

### Changed
- Adjust configuration for 5.8 default configuration ([f1f830e](https://github.com/laravel/horizon/commit/f1f830e8de84c2827c9e155a6abd5cc4576b498e))

## [v2.2.0 (2019-02-12)](https://github.com/laravel/horizon/compare/v2.1.0...v2.2.0)

### Added
- Laravel 5.8 support ([292bbc1](https://github.com/laravel/horizon/commit/292bbc15ce814ae24e0b47d749631cf45a827bc1))

### Fixed
- Fix Failed Jobs page showing no results when failed jobs do exist ([#511](https://github.com/laravel/horizon/pull/511))

## [v2.1.0 (2019-02-11)](https://github.com/laravel/horizon/compare/v2.0.3...v2.1.0)

### Added
- Let user choose custom env ([#483](https://github.com/laravel/horizon/pull/483))

### Changed
- Expire monitored jobs ([#484](https://github.com/laravel/horizon/pull/484))
- Updated axios to v0.18 ([#491](https://github.com/laravel/horizon/pull/491))
- Updated laravel-mix to v4.0 ([#490](https://github.com/laravel/horizon/pull/490))
- Updated vue-router to v3.0 ([#493](https://github.com/laravel/horizon/pull/493))
- Optimized Horizon SVG logo ([#489](https://github.com/laravel/horizon/pull/489))

### Fixed
- Fix findFailed method ([#478](https://github.com/laravel/horizon/pull/478))
- Fix storing floats in Redis ([#477](https://github.com/laravel/horizon/pull/477))
- Fix incorrect processes count ([#481](https://github.com/laravel/horizon/pull/481))
- Fix jobs per minute over estimation ([#502](https://github.com/laravel/horizon/pull/502))
- Prevent horizontal scrolling in Dashboard supervisors section ([#506](https://github.com/laravel/horizon/pull/506))

## [v2.0.3 (2019-01-22)](https://github.com/laravel/horizon/compare/v2.0.2...v2.0.3)

### Changed
- Updated overview stats labels on the dashboard ([#461](https://github.com/laravel/horizon/pull/461))
- Use router-link for recent failed jobs ([#466](https://github.com/laravel/horizon/pull/466))

### Fixed
- Check for existence of `stats` before calling toLocaleString ([#469](https://github.com/laravel/horizon/pull/469))

## [v2.0.2 (2019-01-10)](https://github.com/laravel/horizon/compare/v2.0.1...v2.0.2)

### Fixed
- Update outdated compiled assets ([2a420af](https://github.com/laravel/horizon/commit/2a420af4bb3d79785ef7ff7cd27f75a1c027ab19))

## [v2.0.1 (2019-01-10)](https://github.com/laravel/horizon/compare/v2.0.0...v2.0.1)

### Added
- Added memory usage to the config ([#463](https://github.com/laravel/horizon/pull/463))

### Changed
- Format numbers on the stats dashboard for better readability ([#462](https://github.com/laravel/horizon/pull/462))

### Fixed
- Fixed invalid `doctype` declaration ([#448](https://github.com/laravel/horizon/pull/448))

## [v2.0.0 (2018-11-14)](https://github.com/laravel/horizon/compare/v1.4.3...v2.0.0)

### Added
- Added `horizon:install` command  ([#422](https://github.com/laravel/horizon/pull/422))
- Added middleware to the config ([#432](https://github.com/laravel/horizon/pull/432))

### Changed
- Added new application level `HorizonServiceProvider` and authorization method for consistency with Nova and Telescope ([#422](https://github.com/laravel/horizon/pull/422))