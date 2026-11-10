# FimawDesk for Linux

Linux packages are published in this folder.

- **`.deb`** — Debian / Ubuntu. Install with `sudo dpkg -i fimawdesk-<version>.deb` or `sudo apt install ./fimawdesk-<version>.deb`.
- **`.rpm`** — RHEL / Fedora / openSUSE. `sudo rpm -i fimawdesk-<version>.rpm` or `sudo dnf install ./fimawdesk-<version>.rpm`.
- **`.zst`** — Arch. `sudo pacman -U fimawdesk-<version>.zst`.
- **`.AppImage`** — any distro. Make it executable (`chmod +x`) and run `./fimawdesk-<version>.AppImage`.
- **`.flatpak`** — Flatpak. Install via your Flatpak store or `flatpak install fimawdesk-<version>.flatpak`.

Pick the architecture that matches your system: `x86_64` (most common) or `aarch64` (ARM).
