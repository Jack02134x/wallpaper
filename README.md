# Wallpaper Collection

This repository contains a large collection of wallpapers (~9 GB).

This repository uses **Git LFS (Large File Storage)** due to the large file sizes.

⚠️ **IMPORTANT**
- **DO NOT use "Download ZIP"**
- You **must** use Git + Git LFS to download the actual files

---

## ❌ What Does NOT Work

- Download ZIP from GitHub
- Downloading individual files from the website

These methods download **Git LFS pointer files**, not the real wallpapers.

If your files are only a few KB in size, you downloaded them incorrectly.

---

## ✅ Requirements

- Git
- Git LFS
- Stable internet connection
- ~10 GB free disk space

---

## Installation

### Windows

Download and install:
https://git-scm.com/download/win

Verify installation:
```bash
git --version
```

### Linux
```
sudo pacman -S git-lfs        # Arch
sudo apt install git-lfs      # Debian/Ubuntu
sudo dnf install git-lfs      # Fedora
```

### MacOS
```
brew install git-lfs
```

### Git LFS Instalation
``` git lfs install ```

---
## Final Step Getting the wallpaeprs

```
git clone https://github.com/Jack02134x/wallpaper.git
cd wallpaper
git lfs pull
```