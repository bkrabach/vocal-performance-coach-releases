# Vocal Performance Coach — Android releases

Download the latest APK from [Releases](https://github.com/bkrabach/vocal-performance-coach-releases/releases/latest).
Android 8.0 or later is required. This repository distributes binaries; application source is private.

Public builds use a persistent development signing certificate. If you previously installed
an APK from a private CI debug artifact, it has a different signing key: preserve anything
needed from the app, uninstall that old build, and install the public APK once.
Uninstalling removes local app data. Subsequent public builds can update the existing app.

Use the Updates card inside the app to check for a new build, allow installation from
this app when Android requests it, and confirm installation. A current build reports up to date.

Release tags are `build-N`; APK version codes match N. Every APK is tested and its
package, version, and signing certificate are verified before publication.

Signing certificate SHA-256:
`632bb4e091fb3ee5cd280115cab833e053167bbfa73bfd12274a794412472200`.
Release notes include the APK SHA-256 checksum.
