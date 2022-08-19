<!--
  Copyright (c) 2022 Michael Federczuk
  SPDX-License-Identifier: CC-BY-SA-4.0
-->

# ktlint Installation Script #

[version_shield]: https://img.shields.io/badge/version-0.2.0-informational.svg
[release_page]: https://github.com/mfederczuk/ktlint-install/releases/tag/v0.2.0 "Release v0.2.0"
[![version: 0.2.0][version_shield]][release_page]
[![Changelog](https://img.shields.io/badge/-Changelog-informational.svg)](CHANGELOG.md "Changelog")

## About ##

`ktlint-install` is a POSIX-compliant shellscript for downloading and installing [`ktlint`][ktlint].

[ktlint]: https://github.com/pinterest/ktlint

## Usage ##

Simply execute the script with the version name of `ktlint` that you want to install:

```sh
ktlint-install 0.46.1
```

... or give the argument "`latest`" to install the latest release of `ktlint`.

```sh
ktlint-install latest
```

## Download & Installation ##

Download the [`ktlint-install`](ktlint-install) file and optionally move it into a directory that is inside your
`PATH` environment variable.

## Contributing ##

Read through the [Contribution Guidelines](CONTRIBUTING.md) if you want to contribute to this project.

## License ##

**ktlint Installation Script** is licensed under both the [**Mozilla Public License 2.0**](LICENSES/MPL-2.0.txt) AND the
[**Apache License 2.0**](LICENSES/Apache-2.0.txt).  
For more information about copying and licensing, see the [`COPYING.txt`](COPYING.txt) file.
