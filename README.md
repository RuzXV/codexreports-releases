# Codex Reports - Releases

Public release artifacts for Codex Reports, a Rise of Kingdoms mail and report manager.

Download the latest installer:
https://github.com/RuzXV/codexreports-releases/releases/latest

This page is the only place Codex Reports is published. If someone sends you the installer
as a file, or a link to another site, get it from here instead. A copy from anywhere else
may have been changed.

## Windows

Download the file ending in `-setup.exe` and run it.

If Windows shows "Windows protected your PC", click **More info**, then **Run anyway**.
Windows shows this for apps without a paid signing certificate.

## Mac (Apple chip)

Download the `.dmg`, open it and drag Codex Reports into Applications.

The first time you open it, macOS says it can't check the app. Open **System Settings**,
**Privacy & Security**, scroll down and click **Open Anyway**.

## Updates

Installed copies update automatically on next launch. The `latest.json` and
`updater-payload_*.zip` files belong to the built-in updater; you never need to download them.

## Checking your download (optional)

From version 0.52.0 on, each release lists a SHA-256 fingerprint for its downloads. To check
a file, run `Get-FileHash` on it in PowerShell (Windows) or `shasum -a 256` on it in Terminal
(Mac). The result should match the fingerprint on the release page.
