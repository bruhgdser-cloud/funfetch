# FunFetch ─‿─

A lightweight, fast, and fun system information fetching utility written in pure Bash. It displays your system specs alongside a friendly ASCII smile.

## Features
- Super fast execution (no heavy external dependencies).
- Accurately detects OS, Window Manager (WM) / Desktop Environment, CPU, GPU, and RAM usage.
- Uses standard ANSI colors for a clean terminal look.

## Installation for Arch Linux

Choose **one** of the two convenient methods below to install the package on your system:

### Method 1: Instant Installation (Recommended)
Install directly using the precompiled binary package without building from source:

```bash
git clone https://github.com
cd funfetch
sudo pacman -U funfetch-1.0.0-1-any.pkg.tar.zst
```

### Method 2: Build from Source (Using makepkg)
If you prefer to package it yourself using the native Arch Linux build system:

```bash
git clone https://github.com
cd funfetch
makepkg -si
```

## How to Run

Once installed, simply type the following command in your terminal:

```bash
funfetch
```

## Dependencies
The script relies on basic system tools which are usually pre-installed on Arch Linux:
- `bash`
- `util-linux` (for `lscpu`)
- `pciutils` (for `lspci`)
- `procps-ng` (for `free` and `ps`)
