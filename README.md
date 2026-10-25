# lumen-updates

Updates for the Lumen app. The app reads `update.json` here, checks its signature (`update.json.sig`)
and the SHA-256 of each file, then offers the new app or loads the new screens.

Files are produced by `tools/publish-update.mjs` in the Lumen source — don't edit them by hand,
or the signature check will reject them.
