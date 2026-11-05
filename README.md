# AI Hub releases

Binary releases for [AI Hub](https://github.com/DunoDrake/ai-hub). Source code lives in the main repository.

## Download

Releases are published as GitHub Releases. Each includes:
- **AI Hub-{version}-mac-arm64.dmg** — macOS ARM64 (Apple silicon) installer
- **AI Hub-{version}-mac-arm64.zip** — macOS ARM64 unpacked app
- **SHA256SUMS** — checksums for all artifacts

To install, download the `.dmg` or `.zip` for your system, then:
- **DMG**: Double-click to mount, drag AI Hub to Applications
- **ZIP**: Double-click to extract, then move AI Hub.app to Applications

For the first run or after moving the app, you may see a security prompt. Right-click the app and select **Open**, or run:
```bash
xattr -dr com.apple.quarantine "/Applications/AI Hub.app"
```

## About

Artifacts are built and signed on macOS. They are **not notarized**; see the security prompt above if needed.

This repository contains releases only — no source code. For issues, feature requests, and contribution, see [ai-hub](https://github.com/DunoDrake/ai-hub).
