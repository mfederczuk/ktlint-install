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

The script downloads a `ktlint` JAR and then replaces the existing `ktlint` program found on the `PATH` with the newly
downloaded one.  
If no `ktlint` program is found on the `PATH` (e.g.: it's not installed in the first place), then the default location
for it to get installed in is `/usr/local/bin`.

[ktlint]: https://github.com/pinterest/ktlint

## Usage ##

Simply execute the script with the version name of `ktlint` that you want to install:

```sh
ktlint-install 0.47.0
```

... or give the argument "`latest`" to install the latest release of `ktlint`.

```sh
ktlint-install latest
```

## Download & Installation ##

Download and/or installation must be done manually.

Simply download the [`ktlint-install`](ktlint-install) file and set the executable bit.  
Optionally move the file into a directory that is inside your `PATH` environment variable, so that it is possible to
execute the script from anywhere.

## Contributing ##

Read through the [Contribution Guidelines](CONTRIBUTING.md) if you want to contribute to this project.

## License ##

**ktlint-install** is licensed under both the [**Mozilla Public License 2.0**](LICENSES/MPL-2.0.txt) AND the
[**Apache License 2.0**](LICENSES/Apache-2.0.txt).  
For more information about copying and licensing, see the [`COPYING.txt`](COPYING.txt) file.

_(note that this project is **not** affiliated with ktlint or Pinterest Inc.)_
