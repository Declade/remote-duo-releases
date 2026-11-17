# Remote Duo for Mac — downloads

This repository holds only the **direct-download builds of Remote Duo for Mac** and the small version file the app
reads to offer updates. It contains no source code.

- **Download:** [latest release](https://github.com/Declade/remote-duo-releases/releases/latest) → `RemoteDuo-<version>-b<build>.zip`
  → unzip → move **Remote Duo.app** to Applications → open it.
- Every build is signed with Developer ID (Lucairn UG, team 892Z9CYN6U) and notarized by Apple.
- `manifest.json` (attached to each release): version, build number, download URL, SHA-256 and size of the zip.
  The app's "Update now" installs a build only if the downloaded file matches that SHA-256 **and** the app inside is
  signed by team 892Z9CYN6U, notarized, and accepted by Gatekeeper.
- Releases marked "Pre-release" are test builds with a different bundle ID; the app never offers them.
