<div align="center">

### anirust
![version](https://img.shields.io/badge/version-1.0.0-e8e8e8?style=flat-square&labelColor=141414)
![windows](https://img.shields.io/badge/Windows-x64%20%7C%20x86-e8e8e8?style=flat-square&labelColor=141414&logo=windows&logoColor=e8e8e8)
![linux](https://img.shields.io/badge/Linux-amd64-e8e8e8?style=flat-square&labelColor=141414&logo=linux&logoColor=e8e8e8)
![build](https://img.shields.io/badge/signed-minisign-e8e8e8?style=flat-square&labelColor=141414)

</div>

### Goals
Watch anime in one window — no browser tabs, no pop-ups.
Own player instead of a third-party iframe: intro skip, autoplay next, resume.
Catalog with descriptions, nothing else on screen.
### Install
```bash
# Debian / Ubuntu
sudo apt install ./anirust-1.0.0-linux-amd64.deb

# AppImage
chmod +x anirust-1.0.0-linux-amd64.AppImage
./anirust-1.0.0-linux-amd64.AppImage
```
### Verify
```powershell
Get-FileHash .\anirust-1.0.0-windows-x64-setup.exe -Algorithm SHA256
```
```bash
rsign verify -p anirust.pub anirust-1.0.0-windows-x64-setup.exe
```
Hashes in `SHA256SUMS.txt`, key in `anirust.pub`.
