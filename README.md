# Tanimawo AI for Mac: download

The **Tanimawo AI Academy** student app for MacBooks and iMacs. It is the app at
[app.tanimawoai.com](https://app.tanimawoai.com) in its own window: Code Lab, My Websites, Connect, notifications and
everything else, and you stay signed in.

## ⬇️ Download (click one)

| Your Mac | Click to download |
|---|---|
| **Apple chip** (M1, M2, M3, M4; most Macs from 2021 on) | **[Download for Apple chip Mac (.dmg, 133 MB)](https://github.com/Samsontanimawo/Tanimawo-AI-macOS/releases/latest/download/Tanimawo-AI-1.0.3-mac-arm64.dmg)** |
| **Intel chip** (older Macs) | **[Download for Intel Mac (.dmg, 140 MB)](https://github.com/Samsontanimawo/Tanimawo-AI-macOS/releases/latest/download/Tanimawo-AI-1.0.3-mac-x64.dmg)** |

Not sure which Mac you have? Apple menu  → **About This Mac**: "Chip Apple M…" = Apple chip, "Processor Intel" = Intel.
Then follow **Install** and **The first time you open it** below.

## Install

1. Open the downloaded `.dmg` file (double-click it).
2. Drag **Tanimawo AI** onto the **Applications** folder.
3. Open **Applications** and double-click **Tanimawo AI**.

## The first time you open it

The app is not registered with Apple yet, so macOS asks you to confirm once:

1. macOS says it can't check the app. Click **Done** (or **OK**).
2. Open the Apple menu  → **System Settings** → **Privacy & Security**.
3. Scroll down to the message about **Tanimawo AI** and click **Open Anyway**, then **Open Anyway** again
   (type your Mac password if asked).

From then on it opens normally from Applications, Launchpad or the Dock.

### "Tanimawo AI is damaged and can't be opened"

This means macOS blocked the download. It is not really damaged. Fix it once:

1. Open **Terminal** (Applications → Utilities → Terminal).
2. Paste this line and press Return:

   ```
   xattr -dr com.apple.quarantine "/Applications/Tanimawo AI.app"
   ```
3. Open Tanimawo AI again.

## Updates

The app always shows the latest version of the Academy app, so you do **not** need to download again for new lessons
or features. From version 1.0.3 the app also tells you when a new version of the app itself is out and shows a
**Download** button (or choose **Help → Check for updates**): download it and drag it into Applications, replacing the
old one. You stay signed in. (A Mac app can only replace itself once it is signed with an Apple Developer ID.)

## Help

Ask in the Telegram community group: [t.me/DrDanielFreeAIChat](https://t.me/DrDanielFreeAIChat), or email
tanimawoaiacademy@gmail.com.

Windows version: [Tanimawo-AI-Windows](https://github.com/Samsontanimawo/Tanimawo-AI-Windows).

## Change log

Newest first. Add one line per change.

- **2026-10-09** 1.0.3: the app tells you when a new version is out and shows a Download button (Help → Check for updates too); it reads the newest release here. Download links point to 1.0.3.
- **2026-10-08** 1.0.2: the app icon in the Dock is the Academy robot with its cap, no text. Download links point to 1.0.2.
- **2026-10-08** Direct download links at the top of the page (the files were only on the Releases page).
- **2026-10-08** First public Mac download: Tanimawo AI 1.0.1 (Apple chip and Intel). Built by the private
  Tanimawo_AI-desktop-app repo; only the installers are published here.
