---
title: "Installation"
description: ""
summary: ""
date: 2025-02-20T20:51:12+02:00
lastmod: 2025-02-20T20:51:12+02:00
draft: false
weight: 115
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---


{{< callout context="note" icon="outline/info-circle" >}}
NOTE:

Linutil can be run directly from the command line using the `CLI` installation. It is also available in different packages and can be installed via `Cargo`.

  {{< /callout >}}

- [CLI](#cli)
- [Packages](#package)
    - [Arch Linux](#arch-linux)
    - [OpenSUSE](#opensuse)
    - [Cargo](#cargo)

## CLI 

<strong> *To get started, pick which branch you would like to use, then run the command in your terminal:* </strong>

### Stable Branch (Recommended)
```bash
curl -fsSL https://christitus.com/linux | sh
```
### Dev branch
```bash
curl -fsSL https://christitus.com/linuxdev | sh
```

## Package 

<strong> *Linutil is also available as a package in various repositories:* </strong>


### Arch Linux

Linutil can be installed on [Arch Linux](https://archlinux.org) with three different [AUR](https://aur.archlinux.org) packages:

- `linutil` - Stable release compiled from source
- `linutil-bin` - Stable release pre-compiled
- `linutil-git` - Compiled from the last commit (not recommended)

by running:

```bash
git clone https://aur.archlinux.org/<package>.git
cd <package>
makepkg -si
```

Replace `<package>` with your preferred package.

*If you use [yay](https://github.com/Jguer/yay), [paru](https://github.com/Morganamilo/paru) or any other [AUR Helper](https://wiki.archlinux.org/title/AUR_helpers), it's even simpler:*

```bash
paru -S linutil
```

Replace `paru` with your preferred helper and `linutil` with your preferred package.

### OpenSUSE
  
Linutil can be installed on OpenSUSE with:
```bash
sudo zypper install linutil
```

### Cargo


Linutil can be installed via [Cargo](https://doc.rust-lang.org/cargo) with:

```bash
cargo install linutil_tui
```

