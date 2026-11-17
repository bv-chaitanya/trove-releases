# Trove releases (public mirror)

Public release mirror for **Trove** (app.trove.debrid), the multi-provider debrid library app.

This repo holds the files the in-app updater fetches:

- `latest.json` — {"versionName", "versionCode", "apkUrl", "sha256", "notes"}
- `Trove-v<version>.apk` — the signed release APK for that version

The contents are published automatically by the release workflow in the private bv-chaitanya/trove repo. Nothing here is edited by hand.

No release has been published yet. The first signed release will appear here once the in-app updater and release workflow land (T3).
