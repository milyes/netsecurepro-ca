# NetSecurePro Web CLI Installer

## 📦 Objectif
Ce paquet installe l'interface Web CLI de NetSecurePro IA sur tout système Linux compatible `.deb`, incluant les environnements Termux via proot-distro.

## ✅ Prérequis
- Linux Debian/Ubuntu ou Termux avec `proot-distro`
- `sudo`, `dpkg`, `apt-get` installés

## 🔧 Instructions

### 🔹 Mode classique (Linux Desktop)
```bash
chmod +x install_netsecurepro.sh
./install_netsecurepro.sh
```

### 🔹 Mode Termux (Android)
```bash
pkg install proot-distro
chmod +x install_netsecurepro.sh
./install_netsecurepro.sh
```

## 🔐 Vérification du fichier `.deb`
```bash
sha256sum netsecurepro_web_cli_REAL.deb
```

## 👤 Auteur
Zoubirou Mohammed Ilyes  
[ORCID](https://orcid.org/0009-0007-7571-3178)

## 📁 Fichiers inclus
- `install_netsecurepro.sh`
- `netsecurepro_web_cli_REAL.deb`
- `README.md`
- `SHA256SUM.txt`
