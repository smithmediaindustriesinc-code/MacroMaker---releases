# MacroMaker — releases

Public distribution for **MacroMaker**, a Windows macro recorder, player, and
auto-clicker. This repository holds only release installers and the version
manifest — **no source code**.

## Install

Download **`MacroMakerInstaller.exe`** from the [latest release](https://github.com/smithmediaindustriesinc-code/MacroMaker---releases/releases/latest).
It lets you pick which version to install (pre-releases are hidden behind an
opt-in toggle) and fetches that version's installer.

Or grab a specific `MacroMakerSetup<version>.exe` directly from the
[releases list](https://github.com/smithmediaindustriesinc-code/MacroMaker---releases/releases).

Installs per-user (no administrator prompt).

## Release tiers

| Tier | Meaning |
|------|---------|
| **latest** | current stable release |
| **outdated** | older stable releases, kept for rollback |
| **pre-release** | betas / previews — opt in |

## `versions.json` / `versions.txt`

Machine-readable manifests, newest first. `versions.json` is used by the in-app
updater (Version tab); `versions.txt` by the installer bootstrapper.

## Note on automation tools

MacroMaker replays keyboard and mouse input. Automating input in online games or
other services may violate their terms of service, and anti-cheat software may
detect or block injected input. Use responsibly.
