# MMM-Fuel Changelog

## [2.0.1]

### Fixed

* Rendering of ellipsis with config `shortenText` active https://github.com/fewieden/MMM-Fuel/issues/36

## [2.0.0]

### Added

* Nunjuck templates
* Provider for NSW Australia

### Changed

* Config files
* async/await on the node side of the module.
* fs-extra for promised based filesystem access.
* Replaced request with node-fetch.
* eslint recommended instead of airbnb ruleset.

### Removed

* Documentation on doclets.io (unmaintained).
* Distance conversion
* Modals (help, map)

## [1.1.1]

### Added

* Disabled markdownlint rule `MD024` (no-duplicate-header)
* Config option `toFixed` to show only 2 decimals for the price.

### Changed

* Coordinate.to() throws exception if start point is not set.

## [1.1.0]

### Added

* API provider development [Guide](apis).
* API provider `spritpreisrechner.at`.
* Disabled markdownlint rule `MD026` (no-trailing-punctuation)
* Disabled eslint rule `no-console`
* Documentation
* [Doclets.io](https://doclets.io/fewieden/MMM-Fuel/master) integration
* Contributing guidelines
* Issue template
* Pull request template

### Changed

* Outsourced API provider `tankerkoenig.de`.

## [1.0.0]

Initial version
