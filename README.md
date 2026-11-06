<p align="center">
  <img src="https://raw.githubusercontent.com/ChoutesOS/.github/main/assets/banner.png" alt="ChoutesOS" width="100%">
</p>

<h3 align="center">The Arch-based Linux distribution for gaming and everyday computing</h3>

<p align="center">
  <img src="https://img.shields.io/badge/status-maintenance-F2B84B?style=flat-square" alt="Status: maintenance">
  <img src="https://img.shields.io/badge/based%20on-Arch%20Linux-1793D1?style=flat-square&logo=archlinux&logoColor=white" alt="Based on Arch Linux">
  <img src="https://img.shields.io/badge/desktop-KDE%20Plasma%206-1D99F3?style=flat-square&logo=kde&logoColor=white" alt="KDE Plasma 6">
  <img src="https://img.shields.io/badge/kernel-XanMod-5B18E5?style=flat-square&logo=linux&logoColor=white" alt="XanMod kernel">
  <img src="https://img.shields.io/badge/installer-offline-3DBE7C?style=flat-square" alt="Offline installer">
</p>

<p align="center">
  <a href="https://choutes.com"><b>Website</b></a> &nbsp;&middot;&nbsp;
  <a href="https://choutes.com/download.html"><b>Download</b></a> &nbsp;&middot;&nbsp;
  <a href="https://discord.gg/nYdsKv7Fra"><b>Discord</b></a> &nbsp;&middot;&nbsp;
  <a href="https://sociabuzz.com/choutesos/donate"><b>Donate</b></a>
</p>

<br>

ChoutesOS brings the speed and the rolling updates of Arch Linux together with a polished KDE Plasma desktop of its own. Games, drivers, and applications are ready from the first start, and a full-screen installer sets everything up without an internet connection.

> [!IMPORTANT]
> **Maintenance update in progress.** ChoutesOS 2026.11.07 is being prepared with fixes for the installer, the login and lock screens, and the ChoutesOS Store. A new installation image follows after its final tests; please wait for it before installing ChoutesOS.
>
> Already using ChoutesOS 2026.11.06? Keep using it. The fixes arrive as a normal update in the App Store of your system, and installing that update is strongly recommended.

<p align="center">
  <img src="https://raw.githubusercontent.com/ChoutesOS/.github/main/assets/screenshots/desktop.png" alt="The ChoutesOS desktop with the start menu open" width="100%">
</p>

## Highlights

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ChoutesOS/.github/main/assets/features-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ChoutesOS/.github/main/assets/features-light.png">
  <img src="https://raw.githubusercontent.com/ChoutesOS/.github/main/assets/features-dark.png" alt="A desktop of its own; ready for games; Driver Manager; updates in the background; updates you can undo; the ChoutesOS Store" width="100%">
</picture>

## What is inside

| | |
| --- | --- |
| **Base** | Arch Linux, rolling release, with the signed ChoutesOS package repository |
| **Desktop** | KDE Plasma 6 with the ChoutesOS Dark and ChoutesOS Light themes, Bibata cursor, and Contour wallpapers |
| **Kernel** | XanMod (x86-64-v2) by default, with the Arch Linux LTS kernel as a fallback |
| **Installer** | Calamares, full screen, works offline; Wi-Fi and multimedia codecs are optional |
| **Gaming** | Steam, Wine, Proton tools, GameMode, MangoHud, Gamescope, Faugus Launcher, Prism Launcher, Sober |
| **Applications** | The ChoutesOS Store (Flathub and the AUR), Helium browser, Vesktop, Spotify, ZapZap, and the KDE applications |
| **ChoutesOS tools** | Welcome, ChoutesOS Store, Driver Manager, and About ChoutesOS |
| **Safety** | Btrfs snapshots before and after every update, restored with Btrfs Assistant |

## The ChoutesOS Store

<p align="center">
  <img src="https://raw.githubusercontent.com/ChoutesOS/.github/main/assets/screenshots/app-store.png" alt="The ChoutesOS Store" width="100%">
</p>

Applications and games from Flathub and the AUR, with their developers and screenshots. The ChoutesOS Store runs in the background, tells you when updates or a new version of ChoutesOS are ready, and installs everything with one click.

## Built for games

<p align="center">
  <img src="https://raw.githubusercontent.com/ChoutesOS/.github/main/assets/screenshots/gaming.png" alt="Faugus Launcher and ProtonPlus on ChoutesOS" width="100%">
</p>

Windows games run through Proton and Wine, with GameMode for more speed and MangoHud for a performance overlay. Driver Manager installs the NVIDIA driver on GeForce 16, RTX 20, and newer cards, and offers the 580 legacy driver for GeForce 900 and 10 cards.

## System requirements

| | Minimum | Recommended |
| --- | --- | --- |
| **Processor** | 64-bit with x86-64-v2: Intel Core i3 2nd generation, AMD FX, or newer | Intel Core i5 8th generation, AMD Ryzen 5 2000 series, or newer |
| **Memory** | 4 GB | 8 GB or more |
| **Storage** | 40 GB | 120 GB on an SSD |
| **Graphics** | OpenGL 3.3 | Vulkan 1.3: AMD Radeon RX 400 series, Intel Iris Xe or Arc, NVIDIA GeForce 16 series, or newer |

UEFI or BIOS; Secure Boot must be disabled. A USB drive of 8 GB or more is needed for the installation medium.

## Updates

Installed systems stay current through the signed [ChoutesOS package repository](https://github.com/ChoutesOS/packages); a new image is never needed to get updates. The ChoutesOS Store runs in the background: it checks ChoutesOS and your applications at every start, tells you when updates or a new ChoutesOS version are ready, and installs everything with one click. A new ChoutesOS version arrives as a normal update; its number is the date of the release, for example 2026.11.06.

## Help and community

Questions, bug reports, and ideas are handled on the [ChoutesOS Discord server](https://discord.gg/nYdsKv7Fra). When you report a problem, run `choutesos-diag` in Konsole and attach the file `choutesos-diag.txt` from your home folder. ChoutesOS is free; [a donation](https://sociabuzz.com/choutesos/donate) helps to keep it going.

---

<sub>© 2026 ChoutesOS. All rights reserved. ChoutesOS and the ChoutesOS logo are trademarks of ChoutesOS.<br>
ChoutesOS is an independent project and is not affiliated with Arch Linux.</sub>
