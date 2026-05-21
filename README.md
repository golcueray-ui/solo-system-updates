# Solo System Updates

Canonical manifest:

```text
https://raw.githubusercontent.com/golcueray-ui/solo-system-updates/main/latest.json
```

The single live update manifest is `latest.json` at this repository root.

APK release asset format:

```text
https://github.com/golcueray-ui/solo-system-updates/releases/download/v2.0.0/solo-system-v2.0.0.apk
```

For each release, upload the APK asset first, calculate SHA256 for that exact file, then update `latest.json` with the matching `apkUrl` and `sha256`.
