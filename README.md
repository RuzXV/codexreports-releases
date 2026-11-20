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

On each release page, under **Assets**, GitHub shows a `sha256` value next to every file. To
check a download, run `Get-FileHash` on it in PowerShell (Windows) or `shasum -a 256` on it in
Terminal (Mac). The result should match that value.

## Terms and privacy

### Terms of use

Codex Reports is a free tool that reads the Rise of Kingdoms mail saved on your computer and
turns it into stats.

1. **Free to use.** Use it for yourself and your alliance. You can't sell it, rent it or bundle
   it with something you charge for.
2. **Don't take it apart or copy it.** No reverse engineering, decompiling or modifying the app.
   Don't copy its design, screens, code, artwork or icons into another app or website.
3. **It only reads the game.** The app reads the mail the game has already saved on your computer. It
   doesn't change how the game works and it doesn't play for you.
4. **Not official.** Codex Reports isn't made, endorsed or supported by Lilith Games. Rise of
   Kingdoms and its art belong to Lilith Games.
5. **ROK Battles.** Signing in uses a ROK Battles account. ROK Battles is a separate service
   with its own terms and privacy policy.
6. **As is.** It's provided as it is, with no promises. Numbers can be wrong, for example when
   the game changes its report format. We're not responsible for decisions made based on them.
7. **Access can change.** We can change, pause or remove access to the app at any time, for
   example for abuse.
8. **These terms can change.** Using the app after a change means you accept the new version.

### Privacy

**Your game mail is shared with ROK Battles.** Codex Reports works with ROK Battles, a
community battle report site. While you are signed in, the game mail saved on your computer
is shared with ROK Battles, so your reports are kept there too. ROK Battles handles it under
its own privacy policy.

What else the app sends over the internet:

- **Sign-in.** You sign in with your ROK Battles account. We receive the Discord ID linked to
  that account and the governors bound to it or shared with it (IDs, names and pictures), so
  the app knows who you are and which governors to show. The app also reads your own
  governors and totals from ROK Battles. We don't receive your password. Older versions sign
  in with Discord, and we receive your Discord ID, name and picture.
- **Leaderboard.** If you choose to share a governor on the leaderboard, its battle stats are
  sent to it and shown there.
- **Error reports.** When something goes wrong the app can send a short technical error
  message, with a random install ID, so bugs get fixed. Your computer user name is removed
  first. The message can
  include ID numbers and item names, such as a governor ID or the name of a bundle. If
  security software blocks or removes part of the app, the message also names the antivirus
  program on your computer and which of the app's own files was affected, so we can find
  what sets it off. You can turn this off in Settings.
- **Updates and game data.** The app checks for new versions and downloads game data such as
  names and pictures. Like any download, the servers it contacts can see your IP address.

**Nothing is sold.** Your data isn't sold or used for ads. It is shared with ROK Battles as
described above and with the services that run the app for us.

**Deleting your data.** Uninstall the app and delete its data folder to remove what is on
your computer. To have what we hold about your sign-in removed, ask us and it's deleted. Mail
already sent to ROK Battles stays with ROK Battles, so ask them about it.

**Contact:** The King's Codex Discord server.
