# Night Motel — releases

The installers for **Night Motel**. No source code lives here.

- `latest.json` describes the newest version: its number, notes, size and SHA-256. Installed copies of the game read it when
  they start and offer the update from the title screen (Settings → Check for updates turns that off).
- `NightMotel-Setup-<version>.exe` is the installer for that version. Run it by hand to install, or to update an existing
  installation in place; saved games and settings are kept.
- `HISTORY.md` lists every version that was published.

Releases are published with `tools/publish_release.sh` from the game's repository.
