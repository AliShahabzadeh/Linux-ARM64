# Linux-ARM64

## Overview
This repository serves as a curated collection of links to various Linux distributions available for the ARM64 architecture. These distributions can be used within an emulator on Apple Silicon devices.

<img src="https://raw.githubusercontent.com/AliShahabzadeh/Linux-ARM64/main/src/Screenshots/Header.png" width="500" />

## Available Linux Distributions

### Mainstream distributions:

<details>
  <summary>Ubuntu</summary>
  </br><p><b>Links:</b></p>
  <a href="https://ubuntu.com/download/server/arm" target="_blank">Ubuntu Server</a></br>
  </br><p><b>   Notes:</b></p>
  - To install Ubuntu Desktop, you must first install Ubuntu Server and then manually add the Ubuntu Desktop modules.
</details>

<details>
  <summary>Debian 12</summary>
  </br><p><b>Links:</b></p>
  <a href="https://cdimage.debian.org/debian-cd/current/arm64/iso-cd/" target="_blank">Debian 12 - Net Install</a></br>
  <a href="https://cdimage.debian.org/debian-cd/current/arm64/iso-dvd/" target="_blank">Debian 12 - DVD</a></br>
  </br><p><b>Notes:</b></p>
  - When using the Net Install .iso file, the network driver may not be recognized in Parallels Desktop.</br>
  - To prevent this issue, it is recommended to use the DVD .iso file instead.
</details>

<details>
  <summary>RedHat</summary>
  </br><p><b>Links:</b></p>
  <a href="https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux/arm/trial" target="_blank">RedHat Enterprise Linux for ARM64</a></br>
  </br><p><b>Notes:</b></p>
  - The ARM64 version of RedHat is not considered part of the Developer program for this project to be available for free.</br>
  - The trial period lasts for 60 days.
</details>

<details>
  <summary>Fedora</summary>
  </br><p><b>Links:</b></p>
  <a href="https://alt.fedoraproject.org/alt/" target="_blank">Fedora Alternative Architectures</a></br>
  </br><p><b>Notes:</b></p>
  - The version to download is called 'Everything' which provides a .iso file.
</details>

<details>
  <summary>Arch Linux</summary>
  </br><p><b>Links:</b></p>
  <a href="https://release.archboot.com/aarch64/latest/iso/" target="_blank">ArchBoot</a></br>
  </br><p><b>Notes:</b></p>
  - Installation is performed using ArchBoot.</br>
  - ArchBoot does not support `archinstall`
</details>

<details>
  <summary>Gentoo Linux</summary>
  </br><p><b>Links:</b></p>
  <a href="https://www.gentoo.org/downloads/" target="_blank">Gentoo</a></br>
</details>

<details>
  <summary>Void Linux</summary>
  </br><p><b>Links:</b></p>
  <a href="https://voidlinux.org/download/#arm%20platforms" target="_blank">Void Linux</a></br>
  </br><p><b>Notes:</b></p>
  - The related section to download the .iso file is 'apple silicon (asahi)'.</br>
  - The ARM64 version of Void Linux is designed to be used primarily with Asahi which means as a separate partition on your system.
</details>

### Derived distributions:

<details>
  <summary>Kali Linux (Debian based)</summary>
  </br><p><b>Links:</b></p>
  <a href="https://www.kali.org" target="_blank">Kali Linux</a></br>
</details>

<details>
  <summary>Rhino Linux (Ubuntu based)</summary>
  </br><p><b>Links:</b></p>
  <a href="https://rhinolinux.org/download" target="_blank">Rhino Linux</a></br>
</details>

<details>
  <summary>Rocky Linux (RedHat based)</summary>
  </br><p><b>Links:</b></p>
  <a href="https://rockylinux.org/download" target="_blank">Rocky Linux</a></br>
</details>

## Unix-Like operating systems

<details>
  <summary>Free BSD</summary>
  </br><p><b>Links:</b></p>
  <a href="https://download.freebsd.org/releases/arm64/aarch64/ISO-IMAGES/14.2/" target="_blank">Free BSD</a></br>
</details>

## Validity
> [!IMPORTANT]
> The distributions listed here have been tested on Parallels Desktop. Compatibility with other emulators or hardware may vary.

## Update Policy
This list is periodically reviewed and updated to include new Linux distributions as they become available.

## Contribution
If you know of additional Linux distributions that support ARM64 and would like to add them to this list, feel free to submit a pull request.
