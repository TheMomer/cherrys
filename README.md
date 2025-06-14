# 🍒 Cherrys
**Package Manager for Linux, written in Go.**  
Simple. Fast. Customizable. Almost lazy.

⚠️ This package manager is under development, so the repository is empty.

## 🧃 Features (WIP)
- Uses **json** for configuration and package metadata.
- Supports **asynchronous** downloading of packages
- **No application is used** to create a package server.
- **Clean and minimal** CLI interface
- You can create **any repository** (with binary packages or buildable packages)
- **Simple** syntax

## 🫐 Syntax (WIP)
- Install packages: `cherrys -I <packages>`
- Remove packages: `cherrys -R <packages>`
- Update packages: `cherrys -Up <packages>`
- Update all packages: `cherrys -UpA`

**You'll need to use sudo, doas, or sup to run these commands.**

Example:
```bash
sudo cherrys -I fastfetch htop
```
