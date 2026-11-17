# RemoteLink updates

This repository only serves updates for the RemoteLink desktop app. The source code is not here.

- `stable/latest.json`: the current version for the stable channel (Tauri's update manifest).
- Releases: the signed Windows installers (`RemoteLink_<version>_x64-setup.exe` + `.sig`).

RemoteLink 0.1.2 and later check `stable/latest.json` and offer the update on their home screen
(Settings → General → *Check for updates*). An update is installed only if its signature matches
the public key built into the app and it was signed for exactly the version announced here.

To install RemoteLink from scratch, download the newest `RemoteLink_<version>_x64-setup.exe` from
[Releases](../../releases) (per user, no administrator rights needed).
