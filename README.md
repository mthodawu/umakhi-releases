# Umakhi

Umakhi is a desktop app for construction companies to keep track of **tools and equipment**, **materials and stock**, **projects** (what is happening now, and what is next) and **costs against budget**.

It runs on **Windows** and **macOS**, works offline, and keeps your data on your own computer.

This repository only hosts the installers. There is no source code here.

## Download

1. Open the [latest release](../../releases/latest).
2. Under **Assets**, download the file for your computer:

| Your computer | Download |
|---|---|
| Windows 10 or 11 | `Umakhi-<version>-win-x64.exe` |
| Mac with Apple chip (M1, M2, M3, M4) | `Umakhi-<version>-mac-arm64.dmg` |
| Mac with Intel chip | `Umakhi-<version>-mac-x64.dmg` |

Not sure which Mac you have? Choose the Apple menu, then **About This Mac**. "Chip: Apple M…" means Apple chip; "Processor: Intel" means Intel.

## Install

**Windows:** run the `.exe`. If Windows shows "Windows protected your PC", choose **More info**, then **Run anyway**. This warning appears for new apps that are not yet widely downloaded.

**Mac:** open the `.dmg` and drag Umakhi into **Applications**. The first time, if macOS says it cannot verify the app, right-click (or Control-click) Umakhi in Applications, choose **Open**, then **Open** again. Or go to **System Settings > Privacy & Security** and choose **Open Anyway**.

If macOS says Umakhi is **damaged** and cannot be opened, the app is not damaged: this is how macOS treats downloaded apps that are not yet signed by Apple. Open **Terminal** and run the following once, then open Umakhi again:

```
xattr -cr /Applications/Umakhi.app
```

## Updates

Umakhi checks for new versions by itself. When one is ready, a notification appears under the bell icon with a **Download update** button, then **Restart to install**. Your data is kept.

On a Mac, automatic installation may not be available yet. If you see a message saying so, download the newest `.dmg` from this page and drag it into Applications over the old one. Your data is kept.

## Your data

Umakhi stores everything in a single database file on your computer:

| System | Folder |
|---|---|
| Windows | `%APPDATA%\Umakhi` |
| Mac | `~/Library/Application Support/Umakhi` |

Copy that folder somewhere safe regularly. It is your backup.

## Licence and support

Umakhi is proprietary software. See [LICENSE](LICENSE) for the terms.

For help, [open an issue](../../issues) or contact the person who supplied Umakhi to you.
