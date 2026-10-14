# VS Asset Browser

Native Windows asset browser for local textures, HDRIs, models, IES lights and Karma materials.

## Download

Open [the latest release](https://github.com/pollo-xyz/VS-Asset-Browser-releases/releases/latest).

- **Setup.exe**: recommended per-user installation; no administrator rights required. Includes a Start menu shortcut and Windows uninstall entry. Desktop shortcut is optional.
- **windows-x64.zip**: portable package. Extract the whole folder before running `VS-Asset-Browser.exe`.

Requires 64-bit Windows and Microsoft Edge WebView2 Runtime. Packages are currently unsigned; Windows may show a SmartScreen warning. Check the release asset SHA-256 before installation.

Settings and thumbnails are stored in your local user profile, separately from application versions. Uninstall preserves user settings and unmarked personal folders.

The desktop app checks this public repository for newer stable releases without GitHub credentials. Updates are offered for confirmation; an existing running session is not replaced in place.

## Repository scope

This repository contains only download documentation and binary release assets. Application source and development history are maintained in a separate private repository. Public tags refer only to this documentation history.

See each release for explicit changes, requirements and known limitations. DCC bridge integration requires its separate host-side setup; the application does not start or modify a DCC scene automatically.
