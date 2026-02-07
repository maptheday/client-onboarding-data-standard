# Changelog

All notable changes to the Client Onboarding Data Standard will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Planned for 1.1.0
- Webhook specification for real-time notifications
- Multi-location/franchise support
- International address format enhancements
- Enhanced pet medical data schema
- Bulk import specification

### Under Consideration
- Service history data exchange
- Photo and media attachment standards
- Route optimization data format
- Two-way sync specification

## [1.0.0] - 2026-02-06

### Added
- Initial release of CODS specification
- Core client onboarding schema
  - Client contact information
  - Service address with property details
  - Pet information array
  - Service request configuration
  - Pricing and payment data
  - Client preferences
  - Legal agreements tracking
  - Marketing attribution metadata
- API specification
  - POST /api/v1/cods/onboarding endpoint
  - Request/response formats
  - Authentication methods
  - Error handling standards
- Validation rules
  - Required field validation
  - Format validation (email, phone, dates)
  - Business logic validation
  - Partial save support
- Extensibility framework
  - Custom fields support
  - Vendor-specific extensions
- Version compatibility guidelines
- Security considerations
- JSON schema for validation
- Example implementations
  - Complete onboarding example
  - Minimal required fields example
  - Error response examples
- Documentation
  - Full technical specification
  - API reference
  - Implementation guide
  - Migration guide
  - FAQ
- Validation tools
  - JSON schema validator
  - Example data
  - Test fixtures
- MIT License

### Schema Highlights
- Support for multiple pets per client
- Flexible service frequency options
- Property access details (gate codes, parking)
- Comprehensive preference management
- Marketing attribution tracking
- Terms of service acceptance logging

### API Features
- Standardized success/error responses
- Idempotency support
- Client portal auto-login
- Partial save for lead capture
- Next steps guidance
- Multi-notification tracking

## Version History Summary

- **1.0.0** (2026-02-06) - Initial stable release

## Deprecation Notices

None currently.

## Breaking Changes

None currently.

## Migration Guides

### From Pre-Release to 1.0.0
Not applicable - this is the first public release.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for how to propose changes and additions.

---

[Unreleased]: https://github.com/yourusername/cods/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/yourusername/cods/releases/tag/v1.0.0
