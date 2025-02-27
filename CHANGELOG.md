# Changelog
All notable changes to this project will be documented in this file.

## 2.1.0 – 2023-02-17
### Changed
- Added Nextcloud 26 compatibility

### Fixed
- Fixed an error when Richdocuments has an invalid allow list configured
  [#797](https://github.com/nextcloud/terms_of_service/pull/797)

## 2.0.1 – 2023-02-02
### Fixed
- Compatibility with Richdocuments app
  [#767](https://github.com/nextcloud/terms_of_service/pull/767)

## 1.10.3 – 2023-02-02
### Fixed
- Compatibility with Richdocuments app
  [#769](https://github.com/nextcloud/terms_of_service/pull/769)

## 1.9.4 – 2023-02-02
### Fixed
- Compatibility with Richdocuments app
  [#768](https://github.com/nextcloud/terms_of_service/pull/768)

## 2.0.0 – 2022-10-18
### Added
- Option to change the configuration settings in the administration interface
- Migrated the UI to Vue
- Added compatibility with Nextcloud 25

### Removed
- Removed compatibility with Nextcloud 24

## 1.10.2 – 2022-04-12
### Changed
- Compatibility with Nextcloud 24

## 1.9.3 – 2022-03-03
### Fixed
- Fix an issue with IPs which only return a continent not a country
  [#692](https://github.com/nextcloud/terms_of_service/pull/692)

## 1.9.2 – 2022-01-17
### Fixed
- Fix user_id column length
  [#666](https://github.com/nextcloud/terms_of_service/pull/666)
- Add index for performance
  [#651](https://github.com/nextcloud/terms_of_service/pull/651)

## 1.9.1 – 2021-12-13
### Fixed
- Fix popover being hidden behind the file list
  [#655](https://github.com/nextcloud/terms_of_service/pull/655)

## 1.9.0 – 2021-11-24
### Changed
- Compatibility with Nextcloud 23

## 1.8.1 – 2021-09-21
### Fixed
- Fix text color in terms of registration integration after dependency update
  [#622](https://github.com/nextcloud/terms_of_service/pull/622)

## 1.8.0 – 2021-07-06
### Changed
- Compatibility with Nextcloud 22

## 1.7.1 – 2021-07-06
### Fixed
- Fix link color in terms of registration integration
  [#602](https://github.com/nextcloud/terms_of_service/pull/602)

## 1.7.0 – 2021-04-15
### Added
- Integration into the Registration app
  [#521](https://github.com/nextcloud/terms_of_service/pull/521)
- Compatibility with Nextcloud 21
  [#509](https://github.com/nextcloud/terms_of_service/pull/509)

### Fixed
- Terms of service not working as expected for normal users when enabled on public shares
  [#503](https://github.com/nextcloud/terms_of_service/pull/503)
- Don't block writing skeleton files from LoginFlow and Registration
  [#496](https://github.com/nextcloud/terms_of_service/pull/496)
