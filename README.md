<div align="center">

  <a href="https://github.com/Rohankapoor1904/cherrygram-plus-releases">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2&height=220&section=header&text=🍒%20Cherrygram%20Plus&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38" alt="Cherrygram Plus Banner" width="100%"/>
  </a>

  <p align="center">
    <b>Hardened, High-Performance, Privacy-Centric Telegram Client for Android</b>
  </p>

  <p align="center">
    <a href="https://github.com/Rohankapoor1904/cherrygram-plus-releases/releases/latest">
      <img src="https://img.shields.io/github/v/release/Rohankapoor1904/cherrygram-plus-releases?color=f43f5e&label=LATEST%20RELEASE&style=for-the-badge" alt="Latest Release" />
    </a>
    <img src="https://img.shields.io/badge/Android-8.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android 8.0+" />
    <img src="https://img.shields.io/badge/Architecture-arm64--v8a%20%7C%20v7a%20%7C%20Universal-0284c7?style=for-the-badge" alt="Architecture" />
    <a href="https://github.com/Rohankapoor1904/cherrygram-plus-releases/issues">
      <img src="https://img.shields.io/badge/Bug_Reports-Submit_Issue-10b981?style=for-the-badge&logo=github" alt="Issues" />
    </a>
  </p>

</div>

---

## 📥 Downloads (Latest Stable v10.17.4)

Choose the optimal package for your device architecture:

| Architecture | Recommended Devices | Download Link |
|---|---|---|
| **ARM64-v8a (Recommended)** | Most modern Android devices (2016+) | [⬇️ Download ARM64 APK](https://github.com/Rohankapoor1904/cherrygram-plus-releases/releases/download/v10.17.4/CherrygramPlus-10.17.4-arm64-v8a.apk) |
| **ARMeabi-v7a** | Older 32-bit smartphones and legacy tablets | [⬇️ Download ARMv7 APK](https://github.com/Rohankapoor1904/cherrygram-plus-releases/releases/download/v10.17.4/CherrygramPlus-10.17.4-armeabi-v7a.apk) |
| **Universal (All-in-One)** | Works on all Android CPUs | [⬇️ Download Universal APK](https://github.com/Rohankapoor1904/cherrygram-plus-releases/releases/download/v10.17.4/CherrygramPlus-10.17.4-universal.apk) |

> [!TIP]
> Not sure which APK to pick? If your device was manufactured after 2017, download **ARM64-v8a** for best battery life and highest performance. Otherwise, pick **Universal**.

---

## 🌟 Key Highlights & Exclusive Capabilities

### 🏷 Saved Messages Tags Persistence
- **Local Reaction Tags Preservation**: Restored SQLite reaction tag persistence for Saved Messages in `messages_v2`, preventing tags from resetting upon chat reloading or cache clears.
- **Eager Tag Pre-loading**: Pre-fetches saved reaction tag data upon opening Saved Messages for zero-lag tag filtering.

### 🛡 App Updater & Service Message Hardening
- **Null Safety Guard**: Resolved application crash on updater check caused by null release payload handling.
- **Service Action Filtering**: Filtered out group and channel service actions (member pins, join/leave events, photo changes) from deleted message tags.

### 🛡 Anti-Delete Albums & Media Caption Bubble Rendering
- **Album Background Preservation**: Full message bubble background rendering restored for deleted albums (grouped messages) and media with captions when Anti-Delete is active (`canViewDeletedMessages`).
- **Seamless Group Re-binding**: Retained messages and multi-media group transitions accurately retain bubble layout without disappearing into raw media squares.

### ✨ Liquid Glass & Center Pill Text Centering
- **Pixel-Perfect Centering**: Completely resolved text cutoff and truncation in the top center pill capsule (`🍒 Cherrygra` with `m` cut off and subtitle clipped).
- **Adaptive Header Aesthetics**: Liquid glass shader blur integrated into chat headers and action bars with iOS-style animated unread count badge on the back button (`< 3`).
- **Wallpaper Top Fade Scrim**: Restored wallpaper background fade behind top ActionBar pills and status bar so mobile notification icons, clock, and top headers remain clean and legible.

### 🔲 Seamless Chat Layout & Gap Elimination
- **Bottom Message Alignment**: Restored exact bottom alignment between the chat message list and the chat input bar, eliminating empty gaps above the input bar.

### 🛡 Proactive OOM Watchdog & Memory Optimization
- **Active Heap Monitor**: Background watcher actively tracking memory usage and pruning volatile bitmap/image caches before low-memory crashes occur.
- **Heap Diagnostics**: Live memory metrics table, manual cache pruning, and dynamic warning threshold sliders in Experimental settings.

### 🎁 Hidden & Deleted Star Gifts Store
- **Gifts Discovery**: Discover and purchase hidden or deleted Telegram Star collectible gifts directly within the GiftSheet interface.

### 🔕 Ignore Mentions & Channel Experience
- **Spam Filtering**: Granular filter suppressing mass `@mention` notification pings in busy groups.
- **Wide Channel Bubbles**: Expands channel messages across the screen for comfortable reading.
- **Auto-Play Voice & Video**: Continuous sequential playback for audio notes and video messages.

### ⚡ Extreme Speed Boost 2.0
- **Multi-Stream Acceleration**: Leverages parallel MTProto chunk streaming with up to 16 concurrent network workers.
- **Background Transfers**: Built-in WakeLock & WifiLock guards prevent transfer drops when screen turns off.

### 🎯 120Hz Dynamic Smoothness & High Refresh Engine
- **Micro-Stutter Free**: Frame-pacing sync engine tuned for 90Hz, 120Hz, and 144Hz displays.
- **Native Decoders**: Modernized `AnimatedFileNative` C++ JNI reader and RLottie single-channel ALPHA_8 rendering.

### 👻 Ghost Mode & Stealth Privacy
- **Selective Stealth**: Hide read receipts on incoming messages while maintaining local clean read status.
- **Silent Voice/Video Listening**: Play voice notes and video messages without triggering the sender's listened receipt.

### 🛡 Anti-Delete & Restriction Bypass
- **Deleted Message Retention**: Preserves deleted messages locally so you never miss deleted conversations.
- **Protected Content Saver**: Download and save media from forward-restricted channels and private groups with zero quality degradation.

### 📝 Client-Side Rich Text AST Engine
- **Exact MTProto Compliance**: Zero-shift UTF-16 AST parsing matching Telegram Bot API 10.2 specifications.
- **Advanced Formatting**: Inline LaTeX equations (`Σ $$ formula $$`), interactive table generators, H1–H6 headings, and spoiler blocks.

---

## 📋 Installation Guide

1. Download the preferred APK from the [Releases Tab](https://github.com/Rohankapoor1904/cherrygram-plus-releases/releases/latest) or from the table above.
2. Tap on the downloaded APK in your device notifications or File Manager.
3. If prompted, grant **"Allow from this source"** permission in Android Settings.
4. Tap **Install** and log in to your Telegram account securely.

---

## 💬 Community, Feedback & Support

- **Found a bug or have a suggestion?** Open an issue on our [Official Public Issue Tracker](https://github.com/Rohankapoor1904/cherrygram-plus-releases/issues).
- **Developed & Maintained by**: [Rohan Kapoor](https://github.com/Rohankapoor1904)
