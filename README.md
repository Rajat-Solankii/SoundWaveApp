# 🎵 SoundWave

[![Latest Release](https://img.shields.io/badge/Release-v1.2.0-00F0FF?style=for-the-badge&logo=github)](https://github.com/Rajat-Solankii/SoundWaveApp/releases/latest)
[![Android Compatibility](https://img.shields.io/badge/Android-10%20to%2015%2B%20%2F%2017-818CF8?style=for-the-badge&logo=android)](https://github.com/Rajat-Solankii/SoundWaveApp/releases/latest)
[![Official Website](https://img.shields.io/badge/Website-SoundWave-FF2E93?style=for-the-badge&logo=vercel)](https://sound-wave-website-eta.vercel.app)

---
**A Next-Generation, High-Fidelity Music Experience for Android.**

SoundWave is a feature-rich music player designed to bring together all your favorite music sources into one beautiful, acrylic-themed interface. Whether streaming from global platforms, listening with friends in real-time Jam sessions, or playing your high-res lossless local collection, SoundWave handles it with sample-accurate audio and intelligent playback recovery.

🌐 **Website:** [sound-wave-website-eta.vercel.app](https://sound-wave-website-eta.vercel.app)

---

## ✨ Key Features

### 👥 SoundWave Jam (Collaborative Group Listening)
*   **Dual Sync Engines**: Sub-millisecond Local Wi-Fi (LAN) peer sync + global Cloud sync via Firebase & Ably.
*   **Zero-Setup Guest Join**: Friends can jump directly into your Jam session with zero configuration or API keys needed.
*   **Spotify-Style Room Codes**: Instant 6-character Crockford alphanumeric room codes (e.g. `X8K2M4`) and QR code invites.
*   **NTP Clock Drift Tuning**: Cristian's clock synchronization algorithm for sample-accurate shared playback across all connected devices.

### 🎧 High-Fidelity Audio & Smart Playback
*   **Media Interruption Watchdog**: SoundWave automatically resumes with audible sound when you pause an Instagram Reel or exit external media back to the home screen.
*   **AudioTrack Reconstruction**: Eliminates AudioFlinger preemption stalls and silent playback bugs when returning from video apps.
*   **ReplayGain & Volume Normalization**: Keeps volume levels smooth and consistent across tracks without abrupt jumps.
*   **10-Band Equalizer & Spatial Virtualizer**: Fine-tune your sound with professional presets (Bass Boost, Smooth, Clear, Vocal, etc.).
*   **Seamless Crossfade**: Enjoy gapless transitions with configurable crossfade curves.

### 🚀 Smart Streaming & Sources
*   **Multi-Source Integration**: Stream seamlessly from YouTube, JioSaavn, SoundCloud, and Spotify.
*   **Offline Mode**: Scan and play your local device music alongside online streams.
*   **Real-Time Synced Lyrics**: LRCLIB integration with millisecond offset tuning.
*   **AI DJ & Assistant**: Personalized recommendations powered by Gemini and DeepSeek.

### 🎨 Personalization & Dynamic Theme
*   **Material You Dynamic Palette**: HSL artwork color extraction and stunning acrylic blur backdrops.
*   **Regional Trends**: Localized music discovery across India, US, UK, and global charts.
*   **Language Focused**: Support for 100+ artists across Hindi, Punjabi, English, Tamil, Telugu, and more.

### 🔄 Built-in Update System
*   **Home Screen Update Banner**: Direct in-app alerts when a new release is available, with one-tap downloads and a "Don't show again" option for skipped versions.
*   **Critical Force-Update Support**: Protects users by prompting immediate updates for essential security and API compatibility releases.

---

## 📥 Installation

1.  Navigate to the [Latest Release](https://github.com/Rajat-Solankii/SoundWaveApp/releases/latest) section.
2.  Download `app-universal-release.apk` (or the architecture-specific APK for your device).
3.  Open the APK on your Android device and follow the installation prompts.
    *   *Note: If prompted, enable "Allow installation from unknown sources" in your device settings.*

---

## 🛠️ Update System (Internal)
This repository hosts the `update.json` file used by the app's internal update checker.

**To push an update:**
1.  Upload a new APK to a GitHub Release (`v1.2.0`).
2.  Update `versionCode` and `versionName` in `update.json`.
3.  Provide the direct download URL in `updateUrl`.

---

## ❤️ Developed By
**Rajat Solanki**  
*Enjoy your music experience with SoundWave!*

---

### 🛡️ License
*This project is for personal use and educational purposes. All music content belongs to their respective owners.*
