Changelog
=========

## [11.1.0](https://github.com/ckeditor/ckeditor5-paste-from-office/compare/v11.0.4...v11.1.0) (2019-08-26)

### Features

* Prevent of bolding entire content pasted from Google Docs. Closes [#61](https://github.com/ckeditor/ckeditor5-paste-from-office/issues/61). ([8102de3](https://github.com/ckeditor/ckeditor5-paste-from-office/commit/8102de3))
* Provide support for pasting lists from Google Docs. Closes [#69](https://github.com/ckeditor/ckeditor5-paste-from-office/issues/69). ([6ad2a62](https://github.com/ckeditor/ckeditor5-paste-from-office/commit/6ad2a62))

### Other changes

* The issue tracker for this package was moved to https://github.com/ckeditor/ckeditor5/issues. See [ckeditor/ckeditor5#1988](https://github.com/ckeditor/ckeditor5/issues/1988). ([22edb90](https://github.com/ckeditor/ckeditor5-paste-from-office/commit/22edb90))


## [11.0.4](https://github.com/ckeditor/ckeditor5-paste-from-office/compare/v11.0.3...v11.0.4) (2019-07-10)

Internal changes only (updated dependencies, documentation, etc.).


## [11.0.3](https://github.com/ckeditor/ckeditor5-paste-from-office/compare/v11.0.2...v11.0.3) (2019-07-04)

Internal changes only (updated dependencies, documentation, etc.).


## [11.0.2](https://github.com/ckeditor/ckeditor5-paste-from-office/compare/v11.0.1...v11.0.2) (2019-06-05)

### Other changes

* Loosen a dependency of a clipboard plugin in the paste from Office plugin so that it can be overridden. Closes [#56](https://github.com/ckeditor/ckeditor5-paste-from-office/issues/56). ([561f22b](https://github.com/ckeditor/ckeditor5-paste-from-office/commit/561f22b))


## [11.0.1](https://github.com/ckeditor/ckeditor5-paste-from-office/compare/v11.0.0...v11.0.1) (2019-04-10)

Internal changes only (updated dependencies, documentation, etc.).


## [11.0.0](https://github.com/ckeditor/ckeditor5-paste-from-office/compare/v10.0.0...v11.0.0) (2019-02-28)

### Bug fixes

* Ensured correct lists ordering for separate list items with the same `mso-list` id. Closes [#43](https://github.com/ckeditor/ckeditor5-paste-from-office/issues/43). ([4ebc363](https://github.com/ckeditor/ckeditor5-paste-from-office/commit/4ebc363))
* Handle "spacerun spans" with mixed whitespaces. Closes [#49](https://github.com/ckeditor/ckeditor5-paste-from-office/issues/49). Closes [#50](https://github.com/ckeditor/ckeditor5-paste-from-office/issues/50). ([7fb132f](https://github.com/ckeditor/ckeditor5-paste-from-office/commit/7fb132f))

  Huge thanks to [Matt Kobs](https://github.com/kobsy) for this contribution!

### BREAKING CHANGES

* Upgraded minimal versions of Node to `8.0.0` and npm to `5.7.1`. See: [ckeditor/ckeditor5#1507](https://github.com/ckeditor/ckeditor5/issues/1507). ([612ea3c](https://github.com/ckeditor/ckeditor5-cloud-services/commit/612ea3c))


## [10.0.0](https://github.com/ckeditor/ckeditor5-paste-from-office/tree/v10.0.0) (2018-12-05)

Initial implementation of the Paste from Office feature.
