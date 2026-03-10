# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

<details>
<summary>Migration guide from v0.1.X</summary>

<!-- Write migration guide here -->

</details>

### Added

### Changed

### Deprecated

### Removed

### Fixed

### Security

## [0.1.0] - 2025-12-24

### Added

- Initial resume template based on the [JSON Resume](https://jsonresume.org/) schema
- Support for resume sections: work, education, projects, publications, certifications, awards, volunteer, skills, interests, languages, references
- [Nerd Fonts](https://www.nerdfonts.com/) icon support for contact information (email, phone, URL, location)
- Multi-language (i18n) support with built-in translations for: `en-US`, `zh-CN`, `zh-HK`, `zh-TW`, `ja-JP`, `es-ES`, `fr-FR`, `de-DE`, `ru-RU`, `ko-KR`
- Template package with a ready-to-use `main.typ` example

### Changed

- Locale file naming convention updated to `{locale}.jsume.json` (e.g., `en-US.jsume.json`, `zh-CN.jsume.json`)
- Enabled Typst template section in package configuration

<!--
Below are the target URLs for each version
You can link version numbers (in level-2 headings)
to the corresponding tag on GitHub, or the diff
in comparison to the previous release
-->

[Unreleased]: https://github.com/jsume/jsume-typst/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/jsume/jsume-typst/releases/tag/v0.1.0
