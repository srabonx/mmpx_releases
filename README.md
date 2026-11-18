# MMPX Studio — downloads

MMPX Studio is the AI-native editor for small, instant-loading web games and playable ads. This repository holds
its desktop downloads: **MMPX Hub**, the app you install, and the editor versions Hub installs for you.

## Get started

1. Open the [latest release](https://github.com/srabonx/mmpx_releases/releases/latest).
2. Download **`MMPX-Hub-Setup-<version>-x64.exe`** and run it. It installs for your user only; no administrator
   rights are needed.
3. Start **MMPX Hub** from the Start menu and sign in with your MMPX Studio account.
4. Open or create a project. Hub opens it in the editor version it was saved with.

The Setup program brings the current editor version with it, so you can start working right away.

### "Windows protected your PC"

Windows may show this message the first time you run the Setup program. Click **More info**, then **Run anyway**.
Every editor version and Hub update is still checked before it installs: each one is signed with the MMPX Studio
release key, and its download must match its published checksum.

## What's in a release

| File | What it is |
|---|---|
| `MMPX-Hub-Setup-<version>-x64.exe` | The installer: MMPX Hub and editor `<version>`. This is the one to download. |
| `MMPX-Hub-Update-<version>-x64.exe` | Hub's own update. Hub downloads and runs it when you click **Update and restart**. |
| `mmpx-studio-<version>-win32-x64.zip` | Editor `<version>`. Hub downloads it from its **Installs** page. |

You never need to download the update or the editor zip yourself: Hub does that, and checks each one first.

## Editor versions

- Several editor versions can be installed side by side. Hub's **Installs** page lists them, offers new ones with
  what changed in each, and removes the ones you no longer need.
- A project remembers the editor version it was saved with, and Hub opens it in that version. A project saved with
  a version you don't have offers to install it.
- When a newer editor or a newer Hub is out, Hub tells you.

## More from MMPX Hub

- **Open from File Explorer:** right-click a project folder and choose **Open in MMPX Studio**.
- **Your own AI tool:** connect an AI tool you already use (Claude Code, or any client that speaks the Model
  Context Protocol) once to Hub's address, shown on its Installs page. It reaches every editor you open from Hub.

## System requirements

- Windows 10 or 11, 64-bit
- A graphics card with WebGL 2 (any from the last several years)
- About 600 MB of disk space per editor version

## Uninstalling

Remove **MMPX Hub** from **Settings → Apps → Installed apps**. Hub and every editor version it installed are
removed. Your projects and settings stay where they are.
