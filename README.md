# CardOS Packages

Official package repository for **CardOS** (M5Stack Cardputer ADV).
Maintained by @grisamal.

Packages are managed using pacman:
`ash
pacman -Sy            # Update package database
pacman -S <package>   # Install package
pacman -R <package>   # Remove package
pacman -Syu           # Upgrade all installed packages
`

## Structure
- \packages.json\: Index of available packages with versions, descriptions, and SHA-256 hashes.
- \in/\: Ready-to-download executable packages (ELF binaries and scripts).
- \pkgs/\: Package source code and recipes.
- \.github/workflows/\: GitHub Actions CI/CD pipeline for building and publishing packages.
