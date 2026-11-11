# Changelog

All notable changes to this project are documented here.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

## 2026-11-11 (merge queue ready)

### Changed

- The Changelog workflow now also trigger on `merge_group`, so required checks report on a merge queue's temporary branch. Without this, enabling the queue would leave every required check pending and stall merges (adamsuk/software-factory#312).

## 2026-11-11

### Added

- `.github/factory.yml` lists `changelog / changelog` in `required_checks`, matching the check the `factory-main` ruleset now requires (adamsuk/software-factory#116, #323).

### Added

- CHANGELOG.md, added by [gh-factory](https://github.com/adamsuk/gh-factory).

## 2026-10-31

### Added

- Required target repository field on the task issue form.
