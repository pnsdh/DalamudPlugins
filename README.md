# pnsdh's Dalamud Plugins

A custom [Dalamud](https://github.com/goatcorp/Dalamud) plugin repository for Final Fantasy XIV.

## How to add this repository

1. In-game, type `/xlsettings` to open the Dalamud settings.
2. Go to the **Experimental** tab.
3. Under **Custom Plugin Repositories**, paste this URL into an empty field:

```
https://raw.githubusercontent.com/pnsdh/DalamudPlugins/main/pluginmaster.json
```

4. Click the **+** button, make sure the checkmark is enabled, then click the **Save** icon (bottom-right).
5. Open the plugin installer (`/xlplugins`) and install the plugins listed below.

> ⚠️ Third-party plugins are not verified by the Dalamud/XIVLauncher team. Install only if you trust the source.

## Plugins

| Plugin | Description | Source |
|---|---|---|
| **Passport Checker Reborn (Custom)** | Party Finder member-info overlay adapted for the Korean server (KR world/FFLogs mapping, Korean UI, PlayerTrack-based name recovery). | [pnsdh/PassportCheckerReborn](https://github.com/pnsdh/PassportCheckerReborn) |

## Notes

- Each plugin's source code and Release builds live in its own repository (linked above).
- This repository only hosts `pluginmaster.json`, the manifest Dalamud reads to list the plugins.
- To add another plugin later, append a new entry to the `pluginmaster.json` array with its own `DownloadLinkInstall` pointing at that plugin's GitHub Release.
