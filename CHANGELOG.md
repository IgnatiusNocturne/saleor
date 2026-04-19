# Changelog

All notable, unreleased changes to this project will be documented in this file. For the released changes, please visit the [Releases](https://github.com/saleor/saleor/releases) page.

# 3.24.0 [Unreleased]

### Breaking changes

### GraphQL API

### Webhooks

### Other changes
- Fixed `WeightScalar.parse_value()` to raise `GraphQLError` with descriptive messages instead of crashing with `TypeError` when weight inputs contain null, negative, or invalid values. Fixes #18680.

#### Search improvements

### Deprecations
