# Changelog

All notable changes will be documented in this file.

## 1.2.0 - 2018-08-01

### Added
- Client: `getAll()`, `startAll()`, `stopAll()`, `addFile()`, `addUrl()` methods.
- Torrent Model: `needsMetaData()`, `getDownloadSpeed()`, `getUploadSpeed()`, `getRecheckProgress()` and `getMetadataPercentComplete()`.
- Model: Optional casting toggle argument to the `get()` method.
- Param Builder: Add custom array wrapper.
- Speed and TrunicateNumber Methods to Formatter and Casting.
- More casting types: timestamp, memory, datarate.

### Changed
- Rename Helper to Formatter.
- Rename `bytes` to `size` casting type.
- Refactor `add()` method. No longer fetches duplicate torrent's additional data.
- `seedRatioLimit()` in Torrent Model now supports integer and `Client` value for global seed ratio limit.
- `get()` method now returns collection to be consistent.
- Param Builder: Encodes strings in UTF-8 format as required by Transmission.
- Param Builder: `ids` argument is now fully compatible as per specs to support `recently-active`.

## 1.1.0 - 2018-07-29

- Bugfixes and Optimization.
- Add Helper Class with Casting and Formatting Methods.
- Add Torrent Model.
- Add `seedRatioLimit()` method.
- Refactor Network Exception.
- Improve typehinting.
- Improve Exception Thrower Plugin.

## 1.0.0 - 2018-07-28

- Initial Release