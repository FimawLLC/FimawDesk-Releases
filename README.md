# FimawDesk - Releases

**FimawDesk** is a remote-desktop client by [Fimaw LLC](https://www.fimaw.com) — connect, control, and share your computer with no configuration and full control over your own data.

Installers and release builds that end users can download directly are published in **this public repository**. The source code is private and is not distributed here.

## Download

Grab the latest installers from **[GitHub Releases](https://github.com/FimawLLC/FimawDesk-Releases/releases)**, or browse the per-platform folders below.

| Platform | Folder | Formats |
| --- | --- | --- |
| [Windows](releases/windows/) | `releases/windows` | `.exe` (portable), `.msi` (installer) |
| [macOS](releases/macos/) | `releases/macos` | `.dmg` (universal) |
| [Linux](releases/linux/) | `releases/linux` | `.deb`, `.rpm`, `.AppImage`, `.zst` (Arch), `.flatpak` |
| [Android](releases/android/) | `releases/android` | `.apk`, universal `.apk` |
| [iOS](releases/ios/) | `releases/ios` | `.ipa` |

The file names inside each folder look like `fimawdesk-<version>-<arch>.<ext>`; pick the architecture that matches your machine (`x86_64` = 64-bit, `aarch64` = ARM).

## Company

| | |
| --- | --- |
| Company | Fimaw LLC |
| Website | https://www.fimaw.com |
| Desktop app | https://fimaw.com |
| Email | info@fimaw.com · contact@fimaw.com · desk@fimaw.com |
| Social | Facebook / X / Pinterest / Discord: **FimawLLC** ( /FimawLLC · @FimawLLC · #FimawLLC ) |

## How releases work

- Every tagged build in the private source repo triggers an automated publish.
- The publish job downloads the finished installers, drops them into the matching `releases/<platform>/` folder, and creates a public GitHub Release with the binaries attached.
- Older releases are kept; each new publish refreshes the folders and the latest release.

## License & security

FimawDesk is distributed for the benefit of Fimaw LLC users. Verify download integrity using the `.sig` and SBOM published alongside each release. If you install the `.msi`/`.dmg`, your OS will show the signing details.

## Supported platforms

Windows · macOS · Linux · Android · iOS
