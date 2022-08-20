<!--
  Copyright (c) 2022 Michael Federczuk
  SPDX-License-Identifier: CC-BY-SA-4.0
-->

<!-- markdownlint-disable no-duplicate-heading -->

# Changelog #

All notable changes to this project will be documented in this file.
The format is based on [**Keep a Changelog v1.0.0**](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [**Semantic Versioning v2.0.0**](https://semver.org/spec/v2.0.0.html).

## Unreleased ##

### Added ###

* feature to download latest release by giving "`latest`" as argument
* `--prefer-curl` and `--prefer-wget` options

### Fixed ###

* using `curl` to download wouldn't actually download anything because `curl` doesn't follow redirection by default

## [v0.2.0] - 2022-08-03 ##

[v0.2.0]: https://github.com/mfederczuk/ktlint-install/releases/tag/v0.2.0

### Added ###

* proper arguments/options parsing ([`80392c0`])
* `-V`, `--version` option ([`5b27b8f`], [`4eaca1b`])
* `--dry-run` option ([`4fc5c15`])
* `--help` displays a nicer help summary ([`13e4ff6`])
* `-h` option; same as `--help` ([`4eaca1b`])

### Fixed ###

* Typo fix when given a weird version name ([`da77441`])

[`80392c0`]: https://github.com/mfederczuk/ktlint-install/commit/80392c03180f52df9eb8cad862bbde67bf2780af
[`5b27b8f`]: https://github.com/mfederczuk/ktlint-install/commit/5b27b8f491a0ffe94dd6c4a0a384ad1868c9634a
[`4eaca1b`]: https://github.com/mfederczuk/ktlint-install/commit/4eaca1b1904ae8b9193c4ecc15ec48152c374b4a
[`4fc5c15`]: https://github.com/mfederczuk/ktlint-install/commit/4fc5c15300a39814273c9618d6cf107b4a69f309
[`13e4ff6`]: https://github.com/mfederczuk/ktlint-install/commit/13e4ff6d96a120a43cad1873f40ef9822a421428
[`da77441`]: https://github.com/mfederczuk/ktlint-install/commit/da77441d60ac552b35937b6c3d7e0bed97f4940d

## [v0.1.0] - 2022-08-03 ##

[v0.1.0]: https://github.com/mfederczuk/ktlint-install/releases/tag/v0.1.0

Initial Release
