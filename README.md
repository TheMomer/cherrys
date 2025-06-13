# 🍒 Cherrys
**Package Manager for Linux, written in Go.**  
Simple. Fast. Customizable. Almost lazy.

⚠️ This package manager is under development, so the repository is empty.

## 🧃 Features (WIP)
- Uses **toml** for configuration and package metadata.
- Supports **asynchronous** downloading of packages
- **No application is used** to create a package server.
- **Clean and minimal** CLI interface
- You can create **any repository** (with binary packages or buildable packages)
- **Simple** syntax

## 🫐 Syntax (WIP)
- Install packages: `cherrys -I/--install <packages>`
- Remove packages: `cherrys -R/--remove <packages>`
- Update packages: `cherrys -Up/--update <packages>`
- Update all packages: `cherrys -UpA/--upgrade`

**You'll need to use sudo, doas, or sup to run these commands.**

Example:
```bash
sudo cherrys -I fastfetch htop
```
