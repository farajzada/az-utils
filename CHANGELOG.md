# Changelog

All notable changes to this project are documented here. The format is based on
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and this project adheres
to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.1]

### Changed

- Repository, homepage and issue URLs now point to `github.com/farajzada/az-utils`.

## [0.1.0]

### Added

- Initial release: 15 modules covering Azerbaijan-specific validators, formatters
  and utilities — `iban`, `fin`, `voen`, `phone`, `card`, `swift`, `currency`,
  `number`, `percent`, `dates`, `text`, `case`, `slug`, `postal`, `plate`.
- Highlights: IBAN validate/generate (ISO 7064 MOD-97), `numberToWordsAz` and
  `ordinalAz` (vowel harmony), Azerbaijani-correct casing (İ/ı), Luhn card check,
  manat/qəpik and percent formatting, and a large date-utility set.
- Zero runtime dependencies; ships ESM + CJS + type declarations. 340+ tests.
