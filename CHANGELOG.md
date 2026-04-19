# Changelog

All notable, unreleased changes to this project will be documented in this file. For the released changes, please visit the [Releases](https://github.com/saleor/saleor/releases) page.

# 3.24.0 [Unreleased]

### Breaking changes

### GraphQL API

### Webhooks

### Other changes
- Fixed `transactionCreate` and `transactionUpdate` mutations to return a validation error instead of a 500 Internal Server Error when `pspReference` or `message` inputs exceed 512 characters. Fixes #12696.

#### Search improvements

### Deprecations
