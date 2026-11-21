# Carniclips

Carniclips is a Windows desktop instant replay and clip editor.

## Release status

**Carniclips 1.0.0 is being prepared for its first public release.** A Windows installer candidate and signed updater package have been built, but the production installer and update flow have not yet completed release testing. There is **no public download yet**.

## How updating works

Carniclips uses the signed Tauri updater:

1. Open **Settings** and choose **Check for updates**.
2. Carniclips checks a version manifest hosted with the official GitHub Releases.
3. If a newer version is available, you can choose to install it. An update must not interrupt an active replay recording.
4. Before installing, the app verifies the update package using the public signing key embedded in Carniclips.
5. The Windows installer updates the app. User clips and settings are intended to remain in the app's separate data folder.

**Updates are not live yet.** The GitHub release assets and a real upgrade test must be completed before the updater is considered ready.

Updates are signed for authenticity. This is separate from Windows Authenticode publisher signing.

## Official releases

Once published, Windows installers and release notes will appear on the [GitHub Releases page](https://github.com/0337am/Carniclips/releases).

## Safety

Only download Carniclips from the official repository's Releases page. Never download or share private updater signing keys.
