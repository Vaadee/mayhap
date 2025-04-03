# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [0.2.0] - 2024-04-03
### Added
- `verbose` parameter to the `@maybe` decorator to control whether the "did not execute" message is printed.
- Tests to verify `verbose=True` and `verbose=False` behaviors.
- README examples updated to reflect new usage.

### Changed
- License changed from MIT to GPL-3.0-only.

---

## [0.1.0] - 2024-04-01
### Added
- Initial release with support for conditional function execution based on:
  - Uniform distribution
  - Weighted distribution
  - Normal distribution
  - Exponential distribution
  - Bernoulli distribution
  - Custom function
