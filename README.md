# Apps Launcher releases

Built files only (no source code).

- `AppsLauncher-Setup.exe` - run this once to install Apps Launcher (Windows 10/11, no admin needed).
- `app/version.json` - latest version; the launcher reads it to update itself.
- `app/<version>/AppsLauncher-<version>.zip` - update package used by the launcher.
- `website/site.tar.gz` + `website/version.txt` (`<version> <sha256>`) - the kankon.net website; the Synology NAS checks it every 5 minutes and installs new versions by itself.
