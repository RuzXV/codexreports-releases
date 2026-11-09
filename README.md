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

## Terms and privacy

### Terms of use

Codex Reports is a free tool that reads the Rise of Kingdoms battle reports already saved on
your computer and turns them into stats.

1. **Free to use.** Use it for yourself and your alliance. You can't sell it, rent it or bundle
   it with something you charge for.
2. **Don't take it apart or copy it.** No reverse engineering, decompiling or modifying the app.
   Don't copy its design, screens, code, artwork or icons into another app or website.
3. **It only reads.** The app reads report files the game has already saved on your computer.
   It never changes the game, its files or its network traffic, and it doesn't play for you.
4. **Not official.** Codex Reports isn't made, endorsed or supported by Lilith Games. Rise of
   Kingdoms and its art belong to Lilith Games.
5. **As is.** It's provided as it is, with no promises. Numbers can be wrong, for example when
   the game changes its report format. We're not responsible for decisions made based on them.
6. **Access can change.** We can change, pause or remove access to the app at any time, for
   example for abuse.
7. **These terms can change.** Using the app after a change means you accept the new version.

### Privacy

**Your reports stay on your computer.** Everything the app reads is kept in its own folder on
your computer. Your battle reports are never uploaded.

What the app sends over the internet:

- **Sign-in.** When you sign in with Discord we receive your Discord ID, username and profile
  picture, so the app knows who is signed in. Never your password, email or messages.
- **Error reports.** When something goes wrong the app can send a short technical error
  message, with a random install ID, so bugs get fixed. Your computer user name is removed
  first and report contents are never included. You can turn this off in Settings.
- **Updates and game data.** The app checks for new versions and downloads game data such as
  commander names and pictures. Like any download, the servers it contacts can see your IP
  address.

**Nothing is sold or shared.** Your data isn't sold, used for ads or given to anyone else.

**Deleting your data.** Uninstall the app and delete its data folder to remove everything on
your computer. To have your sign-in removed from our side, ask us and it's deleted.

**Contact:** The King's Codex Discord server.
