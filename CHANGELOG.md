# Changelog

## [Unreleased]

### Added

- nothing added

### Changed

- Changed sample datamodel with a simpler one
- Added mini term sheet for README.md
- Reduced log level for legacy behavior
- Explicitly pass exception for legacy behavior

### Removed

- nothing removed

## [1.5.0] - 2020-03-10

### Added

- CSV Export added in admin actions

## [1.4.0] - 2020-03-04

### Added

- Fix error when an user not authenticated access the admin views

## [1.3.0] - 2020-03-03

### Changed

- In CharField and TextField serializers, the field is required only if `blank` is `False` AND default value is not an empty string. Otherwise it is not required.
- admin view rearranged

## [1.2.0] - 2020-02-21

## [1.1.1] - 2020-02-21

## [1.1.0] - 2020-02-21

### Changed

- fixed password change token expiry computation
- fixed register serializer to allow null values of url_format and email_format
- register email subject in settings

## [1.0.1] - 2020-02-21

## [1.0.0] - 2020-02-20

### Added

- concrete datastore doc is up to date.
- Open the sources.
