# Solo System Updates

Canonical manifest:

```text
https://raw.githubusercontent.com/golcueray-ui/solo-system-updates/main/latest.json
```

The single live update manifest is `latest.json` at this repository root.

APK URL currently used by `latest.json`:

```text
https://raw.githubusercontent.com/golcueray-ui/solo-system-updates/main/solo-system-v3.0.0.apk
```

For each release, upload or commit the APK first, calculate SHA256 for that exact file, then update `latest.json` with the matching `apkUrl` and `sha256`.
