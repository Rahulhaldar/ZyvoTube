<div align="center">

<img src="https://zyvotube.in/assets/Banner.png" alt="ZyvoTube" width="100">

# 🎬 ZyvoTube

### Watch. Explore. Zyvo.

**A lightweight Android video experience built around discovery, playback, Shorts and downloads.**

<p>
  <a href="https://github.com/Rahulhaldar/ZyvoTube/releases/latest">
    <img src="https://img.shields.io/github/v/release/Rahulhaldar/ZyvoTube?display_name=tag&style=for-the-badge&color=ed0716&label=LATEST%20RELEASE" alt="Latest Release">
  </a>
  <img src="https://img.shields.io/badge/Android-API%2024%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android">
  <img src="https://img.shields.io/badge/Kotlin-Android-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin">
  <img src="https://img.shields.io/badge/Jetpack%20Compose-UI-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" alt="Jetpack Compose">
</p>

<p>
  <a href="https://zyvotube.in">🌐 Website</a>
  ·
  <a href="https://github.com/Rahulhaldar/ZyvoTube/releases">📦 Releases</a>
  ·
  <a href="https://github.com/Rahulhaldar/ZyvoTube/issues">🐛 Issues</a>
</p>

</div>

---

## 🧭 What is ZyvoTube?

**ZyvoTube** is an independently developed Android video application focused on keeping the everyday video experience simple, fast and lightweight.

The project is designed around a few core ideas:

- 🎬 **Watch** without unnecessary clutter
- 🔎 **Explore** content quickly
- 📱 **Scroll** through Shorts
- ⬇️ **Download** supported video and audio
- 🎵 **Keep M4A audio** in a player-friendly format
- 🔊 **Continue playback** in the background
- 🖼️ **Use Picture-in-Picture** when multitasking
- 🧹 **Keep storage clean** with the built-in cache cleaner

> **ZyvoTube is built as a personal independent project by Rahul Haldar.**

---

# 🚀 ZyvoTube v1.0.0

<div align="center">

### The first public ZyvoTube release

| Release Detail | Value |
|---|---|
| 📱 Version | **1.0.0** |
| 🔢 Version Code | **1** |
| 📦 Package | `com.zyvotube.rahul` |
| 💾 APK Size | **~8.58 MB** |
| 🏷️ Release | **v1.0.0** |
| 📅 Status | **Latest** |

<br>

<a href="https://github.com/Rahulhaldar/ZyvoTube/releases/download/v1.0.0/ZyvoTube-1.0.0-release.apk">
  <img src="https://img.shields.io/badge/⬇%20DOWNLOAD%20ZYVOTUBE%20v1.0.0-ed0716?style=for-the-badge&logo=android&logoColor=white" alt="Download ZyvoTube">
</a>

</div>

### 🔐 Release Verification

**SHA-256**

```text
6f7076e2a26e10935782101937d47589320e15eb949439eef55c3d504543c771
```

Use the SHA-256 value above to verify that a downloaded APK matches the published release.

---

# ✨ What You Can Do

## 🎬 Watch

ZyvoTube puts the player first.

- Smooth video playback
- Dedicated fullscreen experience
- Playback controls
- Seeking and duration controls
- Captions support where available
- Playback speed controls where supported
- Related content
- Watch history
- Continue watching
- Background playback
- Picture-in-Picture

---

## 📱 Shorts

A dedicated vertical video experience for quick discovery.

- Vertical swipe-based feed
- Automatic progression to the next Short
- Short-form playback
- Download support where available
- Background playback support
- Fast content switching
- Session-level duplicate protection
- Preloading for nearby content

> ZyvoTube's Shorts experience is designed to feel quick without turning the whole app into a heavy client.

---

## 🔎 Search & Discovery

Find content without digging through complicated menus.

- Video search
- Shorts discovery
- Channel discovery
- Search result filtering
- Related content
- Thumbnail loading
- Metadata caching
- Independent feed state
- Pagination support

---

# ⬇️ Download System

ZyvoTube includes a focused download experience for supported media.

### 🎥 Video Downloads

- Supported video downloads
- Download progress
- Success and failure states
- Download notifications
- File validation
- Local device storage integration

### 🎵 M4A Audio Downloads

Audio is intentionally kept lightweight.

- Direct **M4A** audio downloads
- No FFmpeg dependency required for the current M4A pipeline
- Player-friendly audio files
- Music-player visibility on supported Android devices
- Background playback support

> **M4A is the current preferred audio format in ZyvoTube.**

---

# 🔊 Background Playback

Continue listening while using other parts of your phone.

- Media playback continues outside the main screen
- System media controls
- Notification playback controls
- Resume playback position
- Audio-focused playback

---

# 🖼️ Picture-in-Picture

Watch while doing something else.

ZyvoTube supports Android Picture-in-Picture for compatible playback flows, allowing the video to continue in a floating player while another app is being used.

---

# 🧹 Cache Cleaner

ZyvoTube includes a dedicated cache-cleaning system.

### What it manages

- App cache
- External app cache
- Cache size detection
- Manual cleaning
- Automatic cleanup checks

### Safety design

The cleaner is intended to target cache locations only.

Completed user downloads and important app files are not treated as disposable cache.

---

# 🎨 ZyvoTube Design

The visual direction is intentionally different from a basic Android media app.

### Brand

**ZyvoTube**

### Visual identity

- Crimson / red accent
- Clean dark UI
- Strong typography
- Rounded surfaces
- Modern cards
- Lightweight animations
- Minimal visual noise
- Video-first layouts

### Navigation

The app is organized around the main areas users actually need:

**Home · Shorts · Subscriptions · Notifications · You**

---

# 📸 Screenshots

<div align="center">

### 🏠 Home

<img src="https://zyvotube.in/assets/Home.jpg" alt="ZyvoTube Home" width="220">

<br><br>

### ▶️ Player

<img src="https://zyvotube.in/assets/Play.jpg" alt="ZyvoTube Player" width="220">

<br><br>

### 📱 Shorts

<img src="https://zyvotube.in/assets/Shorts.jpg" alt="ZyvoTube Shorts" width="220">

</div>

> If the screenshot URLs are moved in the website repository later, update these image paths in this README.

---

# 🧩 Technology Stack

| Area | Technology |
|---|---|
| Language | Kotlin |
| UI | Jetpack Compose |
| Android UI | AndroidX |
| Playback | AndroidX Media3 |
| Networking | OkHttp / project networking layer |
| Async | Kotlin Coroutines |
| State | StateFlow |
| Local storage | Android storage APIs |
| Analytics | Firebase Analytics |
| Crash reporting | Firebase Crashlytics |
| Build | Gradle |
| Optimization | R8 + Resource Shrinking |
| Release | Signed Android APK |

---

# 🏗️ High-Level Architecture

```text
┌──────────────────────────────────────────────┐
│                 ZyvoTube UI                  │
│          Jetpack Compose / AndroidX          │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│             Screen State / ViewModel         │
│               StateFlow / Coroutines         │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│             Application Services             │
│ Search · Feed · Playback · Downloads         │
└───────────────┬──────────────┬───────────────┘
                │              │
                ▼              ▼
       ┌────────────────┐  ┌─────────────────┐
       │ Media3 Player  │  │ Download Layer  │
       │ Video / Audio  │  │ Video / M4A     │
       └───────┬────────┘  └────────┬────────┘
               │                    │
               ▼                    ▼
       ┌─────────────────────────────────────┐
       │           Android Device            │
       │ Storage · MediaSession · PiP · OS   │
       └─────────────────────────────────────┘
```

---

# ⚡ Performance & APK Size

One of the project goals is keeping ZyvoTube lightweight.

The current v1.0.0 release uses:

- R8 code shrinking
- Resource shrinking
- Release-only optimization
- No FFmpeg dependency in the current M4A pipeline
- Focused native dependency footprint
- Lightweight release packaging

### Current release size

**~8.58 MB**

This is intentional.

> The target for the public ZyvoTube release was approximately **8–9 MB**, rather than shipping an unnecessarily large APK.

---

# 🔐 Package & Release Identity

The public ZyvoTube application identity is:

```text
Application ID:
com.zyvotube.rahul

Version:
1.0.0

Version Code:
1
```

### Important for future updates

Future ZyvoTube updates must keep:

```text
com.zyvotube.rahul
```

and must continue using the same release signing identity.

Changing the application ID would create a different Android application rather than a normal update.

---

# 🛡️ Safety & Distribution

ZyvoTube is distributed through the project's official website and GitHub Releases.

### Official sources

🌐 **Website**

https://zyvotube.in

📦 **GitHub Repository**

https://github.com/Rahulhaldar/ZyvoTube

🚀 **Latest Release**

https://github.com/Rahulhaldar/ZyvoTube/releases/latest

📥 **v1.0.0 APK**

https://github.com/Rahulhaldar/ZyvoTube/releases/download/v1.0.0/ZyvoTube-1.0.0-release.apk

### Android installation

Android may scan APKs installed outside Google Play with Play Protect.

**Keep Play Protect enabled.**

If Android displays a warning, verify the APK source and SHA-256 before continuing.

---

# 📊 Telemetry & Stability

ZyvoTube includes Firebase-based telemetry for project monitoring and stability.

### App events

The project tracks relevant events such as:

- App opens
- Video playback
- Shorts viewing
- Download started
- Download completed
- Download failed
- Background playback

### Crash reporting

Firebase Crashlytics is used for crash and non-fatal issue reporting.

The goal is to use these signals to identify real-world problems and improve future releases.

---

# 🧪 Release Testing Checklist

Before considering a build ready for public distribution:

### Installation

- [ ] Fresh APK installation
- [ ] Play Protect scan
- [ ] App launches correctly
- [ ] Correct package identity
- [ ] Correct version and version code

### Playback

- [ ] Normal video playback
- [ ] Seek
- [ ] Fullscreen
- [ ] Captions where available
- [ ] Playback speed
- [ ] Background playback
- [ ] Picture-in-Picture

### Shorts

- [ ] Shorts feed loads
- [ ] Swipe to next Short
- [ ] No excessive duplicate items
- [ ] Auto progression
- [ ] Download flow

### Downloads

- [ ] Video download
- [ ] M4A download
- [ ] Download progress
- [ ] Download completion
- [ ] Failed download handling
- [ ] Music Player visibility for M4A
- [ ] Download notification

### Storage

- [ ] Cache size detection
- [ ] Clean Now
- [ ] Automatic cache cleanup
- [ ] User downloads remain safe

### Firebase

- [ ] Analytics events
- [ ] Crashlytics initialization
- [ ] Non-fatal reporting

---

# 🗂️ Project Structure

A simplified view of the application architecture:

```text
ZyvoTube/
│
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/
│   │       ├── res/
│   │       └── AndroidManifest.xml
│   │
│   ├── build.gradle.kts
│   └── google-services.json
│
├── gradle/
│
├── build.gradle.kts
├── settings.gradle.kts
└── README.md
```

> The exact source tree can evolve as the project grows.

---

# 🛠️ Development

### Requirements

Recommended development environment:

- Android Studio
- JDK 17
- Android SDK
- Git
- Gradle / Gradle Wrapper

### Build

Clone the repository:

```bash
git clone https://github.com/Rahulhaldar/ZyvoTube.git
cd ZyvoTube
```

Then open the project in Android Studio and allow Gradle to sync.

Build a release using the project's configured Gradle setup.

> Release signing credentials and private keys should never be committed to GitHub.

---

# 📦 Releases

| Version | Status | APK |
|---|---|---|
| **v1.0.0** | 🟢 Latest | ~8.58 MB |

See all releases:

https://github.com/Rahulhaldar/ZyvoTube/releases

---

# 🗺️ Project Direction

Future development may focus on:

- ⚡ Faster startup
- 🎬 Faster video resolution
- 📱 Smoother Shorts transitions
- ⬇️ Better download reliability
- 🎵 Improved audio metadata
- 🧹 Further storage improvements
- 📊 Better stability monitoring
- 🎨 Continued UI polish
- 🔧 Bug fixes based on real-device testing

The project will prioritize stability before adding unnecessary features.

---

# 🤝 Feedback & Bug Reports

Found something broken?

Please create a GitHub issue with:

1. Device model
2. Android version
3. ZyvoTube version
4. What you expected
5. What actually happened
6. Steps to reproduce
7. Screenshot or screen recording when useful

🐛 **Report an issue:**

https://github.com/Rahulhaldar/ZyvoTube/issues

---

# ⭐ Support ZyvoTube

If you find the project useful:

- ⭐ Star the repository
- 🐛 Report reproducible bugs
- 💡 Share useful ideas
- 🧪 Help test releases
- 📢 Share the official website
- 🔧 Contribute where appropriate

Every useful report helps make the next release better.

---

# 👨‍💻 Developer

<div align="center">

<img src="https://github.com/Rahulhaldar.png" width="96" height="96" alt="Rahul Haldar">

## Rahul Haldar

**Creator & Developer of ZyvoTube**

<a href="https://github.com/Rahulhaldar">
  <img src="https://img.shields.io/badge/GitHub-RahulHaldar-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>

<br><br>

**Building ideas into real apps. 🚀**

</div>

---

# ⚠️ Important Notice

ZyvoTube is an independent Android project.

- ZyvoTube is not an official Google or YouTube application.
- YouTube and related trademarks belong to their respective owners.
- Content availability depends on the underlying service and available sources.
- Download availability may vary by content and source.
- Users are responsible for using the application in accordance with applicable laws and service terms.

---

<div align="center">

# ❤️ ZyvoTube

### Watch. Explore. Zyvo.

**Version 1.0.0 · Built by Rahul Haldar**

<br>

<a href="https://github.com/Rahulhaldar/ZyvoTube/releases/latest">
  <img src="https://img.shields.io/badge/GET%20ZYVOTUBE-ed0716?style=for-the-badge&logo=android&logoColor=white" alt="Get ZyvoTube">
</a>

</div>
