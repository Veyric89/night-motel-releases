# Night Motel — releases

The installers for **Night Motel**, one GitHub release per version. Installed copies of the game check this repository's
latest release when they start and offer the update from the title screen (Settings → Check for updates turns that off).

To install by hand: open the latest release under **Releases** and run `NightMotel-Setup-<version>.exe`. It updates an
existing installation in place; saved games and settings are kept.

No source code lives here. Releases are published with `tools/publish_release.sh` from the game's repository; each release's
notes carry the installer's SHA-256, which the game checks before installing.
