# Changelog
All notable changes to this project will be documented in this file.

## [1.0.0] - 2024-03-XX

### Added
- Initial release
- Laravel 12.x support
- PHP 8.2+ requirement

### Compatibility
- Supports Laravel 10.x, 11.x, and 12.x
- Requires PHP 8.2 or higher

## [2.0.0] - 2024-03-XX

### Added
- Laravel 12.x support
- PHP 8.2+ requirement

### Changed
- Updated minimum Laravel version to 12.0
- Updated composer dependencies
- Updated illuminate packages to support Laravel 12

### Compatibility
- Now supports Laravel 10.x, 11.x, and 12.x
- Requires PHP 8.2 or higher

## [1.0.9] - Previous version

## [1.0.8] - 2024-07-15
### Added
- Support for Multi-Tenancy ([#24](https://github.com/ringlesoft/laravel-process-approval/issues/24))
- Ability to return a record to the previous step ([#18](https://github.com/ringlesoft/laravel-process-approval/issues/18))
- Method for seeding the database with approval flows and steps
- Support for Multilanguage

### Fixed
- Resolved compatibility issue with PostgreSQL by removing backticks from SQL queries

### Changed
- Deprecated `getApprovalSummaryUI()` method in favor of `<x-ringlesoft-approval-status-summary>` component
- `web` middleware is applied to the ApprovalController by default

### Additional
- Added testing branch `tests`

## [1.0.7] - 2024-04-17
- Support for Laravel 11 [#19](https://github.com/ringlesoft/laravel-process-approval/issues/19).
- Multiple improvements
- A few bug fixes

## [1.0.6] - 2024-02-03
- Now you can publish specific files (approvals-config, approvals-migrations and approvals-views) using the `--tag` options.

## [1.0.5] - 2023-11-23
- A few bug fixes

## [1.0.4] - 2023-11-15
- Now you can specify middleware to be applied to the ApprovalController
- Introduced API access. You can now submit your own approval form via api for SPAs.
- More exception classes
- A lot of bug fixes

## [1.0.3] - 2023-11-13
- Minor bug fixes

## [1.0.2] - 2023-11-13
- Minor bug fixes

## [1.0.1] - 2023-11-01
- Tailwind CSS Support: We've added support for Tailwind CSS as an optional choice for the UI component. Customize your user interface with ease.
- Laravel/Prompts for CLI: We now provide Laravel prompts for the Command-line Interface (CLI), simplifying your interactions with the package through the command line.
- New Facade: A new Facade is introduced, allowing you to work with Approval Flows programmatically, providing more flexibility in your workflows.
- This release includes multiple bug fixes and general improvements to enhance the stability and functionality of the package.
