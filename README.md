# felfel.ai for Mac, Windows and Linux

The desktop app for [felfel.ai](https://felfel.ai). This repository only hosts the app's downloads.

| Your computer | Download | Needs |
| --- | --- | --- |
| Mac | **[felfel.ai.dmg](https://github.com/afelfel2016-prog/felfel-desktop/releases/latest/download/felfel.ai.dmg)** | macOS 13 Ventura or later · Apple Silicon or Intel |
| Windows | **[felfel.ai-Setup.exe](https://github.com/afelfel2016-prog/felfel-desktop/releases/latest/download/felfel.ai-Setup.exe)** | Windows 10 or 11 · 64-bit |
| Linux | **[felfel.ai.AppImage](https://github.com/afelfel2016-prog/felfel-desktop/releases/latest/download/felfel.ai.AppImage)** or **[felfel.ai.deb](https://github.com/afelfel2016-prog/felfel-desktop/releases/latest/download/felfel.ai.deb)** | 64-bit · Ubuntu 22.04+, Debian 12+, Fedora 38+ or similar |

Free. Sign in with your felfel.ai account.

## What it does

Everything felfel.ai does on the web, plus:

- **Artifacts:** the pages, apps and games felfel.ai builds open in a big viewer, and **Run on localhost** serves them from your computer at `http://127.0.0.1:<port>` with one click.
- **Computer mode** (Mac and Linux; coming to Windows): when you allow it, felfel.ai works on your computer.
  - **Files:** finds, reads and organizes your files, creates folders, and writes or edits documents and code.
  - **Terminal commands:** runs the commands a task needs (installs, builds, tests, git) and reads the output to fix what went wrong.
  - **Local servers:** starts dev servers and serves the sites it builds, then opens them in your browser. Stop them anytime from the Servers menu.
  - **You approve:** changes and commands ask first in a native prompt. A web page can never approve anything for you.

## Install

### Mac

1. Open the downloaded `felfel.ai.dmg`.
2. Drag felfel.ai onto the Applications folder, then eject the disk image.
3. Open it the first time. This early release isn't notarized by Apple yet, so macOS stops the first launch:
   - **macOS 15 Sequoia or later:** open felfel.ai and click **Done**. Go to **System Settings → Privacy & Security**, scroll down, click **Open Anyway** next to the felfel.ai message, and confirm with your password or Touch ID.
   - **macOS 13–14:** Control-click felfel.ai in Applications, choose **Open**, then click **Open** again.

### Windows

1. Run `felfel.ai-Setup.exe`.
2. This early release isn't signed with a Windows certificate yet, so Windows may say **Windows protected your PC**. Click **More info**, then **Run anyway**.
3. felfel.ai installs for your account (no administrator needed) and opens. Find it later in the Start menu.

### Linux

- **AppImage:** make it executable (right-click → Properties → Allow executing, or `chmod +x felfel.ai.AppImage`) and run it. On Ubuntu 22.04 and later, AppImages need FUSE 2: `sudo apt install libfuse2` (`libfuse2t64` on Ubuntu 24.04).
- **.deb** (Ubuntu, Debian): `sudo apt install ./felfel.ai.deb`, then open felfel.ai from your apps.

Then sign in with email, or with Google: on a Mac, macOS opens its own small sign-in window; on Windows and Linux, Google sign-in opens in your browser. Finish there, click **Open the felfel.ai app**, allow your browser to open it, and the app signs in by itself.

More at [felfel.ai/download](https://felfel.ai/download).
