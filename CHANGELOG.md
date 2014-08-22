# Change Log

All notable changes to this project are documented in this file.


## 2.1.0 - Work In Progress

### Removed

* Just-Install will no longer self-install by copying itself to `%WinDir%\just-install.exe`, users
  must manually place it there or use the installation script given on the README.md file.


## 2.1.0 - Work In Progress

### Added

* Add support for wrapped installers (e.g. MSI file in a ZIP container). To see how to use this
  feature check out the "colemak" and "smartkey" entries from the registry.
* Add support for extracting ZIP files to an arbitrary location on disk. To see how this feature
  works, see the "depends" and "sysinternals" entries from the registry.

### Fixed

* Now honoring the "arguments" array for "custom" installers.
* Just-Install exits with an error if it fails to parse the registry.


## 2.0.1 - 2014-08-12

* Embedded manifest to require elevation.
* Embedded the icon in the executable again.


## 2.0.0 - 2014-08-5

* New command line interface, run `just-install --help` for help.
* Does not require the Visual C++ 2008 Runtime to be installed anymore.
* Antivirus program should not flag just-install as a virus anymore.
* More solid self-update functionality.
* New catalog file format.
* Rewritten in Go.
