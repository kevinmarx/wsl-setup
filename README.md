# wsl-setup
Set up Ubuntu environment within WSL

### Install Ubuntu 18.04LTS from the Windows Store
- https://www.microsoft.com/store/productId/9N9TNGVNDL3Q

### Enable WSL
- Open PowerShell with admin rights
```powershell
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
```
- restart windows

### Open Ubuntu Shell
- create linux user and password (use windows alias)

## Environment Setup

### Installing Homebrew (Linux)
https://docs.brew.sh/Homebrew-on-Linux
