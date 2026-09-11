<div align="center">

[![English](https://img.shields.io/badge/README-English-blue)](README.md)
[![Русский](https://img.shields.io/badge/README-Русский-red)](README.ru.md)
[![Oʻzbekcha](https://img.shields.io/badge/README-Oʻzbekcha-green)](README.uz.md)

</div>

# ArcherSec — Open-Source Cloning & Imaging Suite

Free open-source cloning, imaging, and rescue solution. Deploy Windows via PXE, create disk images with PartClone, manage machines through a web GUI. Features: memory/disk testing, disk wipe, AV scan, task scheduling, inventory, remote software installation.

## ℹ️ Legacy Project

This is an early experimental PHP-based security and imaging toolkit, kept for reference and history. It is not actively maintained. The production-grade successor approaches for automation live in the newer repositories (OpsPlaybook and others).

## Capabilities

| Feature | Description |
|---------|-------------|
| PXE Boot | Network boot for deployment |
| Disk Imaging | PartClone-based image creation/restoration |
| Web GUI | Central management interface |
| Hardware Tests | Memory and disk diagnostics |
| Disk Wipe | Secure data erasure |
| AV Scan | Antivirus scanning |
| Inventory | Hardware/software tracking |
| Remote Install | Software deployment to registered machines |
| Task Scheduling | Planned imaging and maintenance jobs |

## Supported OS
Windows XP, Vista, 7, 8, 10 (PXE deploy)

## Components
- `src/` — Core source code (iPXE)
- `bin/` — Installer and binaries
- `lib/` — Platform libraries (Arch, Red Hat, Ubuntu)
- `utils/` — Utility scripts (backup, iPXE, updater)
- `packages/` — Package definitions, services, web UI
- `SELinux/` — Security policies

## Screenshot

![Demo](screenshots/demo.svg)

## Usage

```bash
# Install (run as root; supports Arch, Red Hat, Ubuntu)
cd bin && sudo ./installarcher.sh

# Uninstall
sudo ./installarcher.sh --uninstall
```

After installation the web GUI is served from the Apache document root (default `/archer/`).

## License
GPL-3.0 — see [LICENSE](LICENSE)

## 📬 Contact
📧 **[allumaxmail@gmail.com](mailto:allumaxmail@gmail.com)**

---

<div align="center">

[![English](https://img.shields.io/badge/README-English-blue)](README.md)
[![Русский](https://img.shields.io/badge/README-Русский-red)](README.ru.md)
[![Oʻzbekcha](https://img.shields.io/badge/README-Oʻzbekcha-green)](README.uz.md)

</div>
