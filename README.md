# VoxiPrompter

**The speech-guided teleprompter that runs entirely on your device.**

No cloud services. No subscriptions. No accounts. Just you and your script.

VoxiPrompter listens to your microphone, matches your voice against your script, and advances the teleprompter automatically -- all in real time. The on-device AI speech recognition model downloads once (~250 MB) and works 100% offline after that.

**[voxiprompter.com](https://voxiprompter.com)** -- macOS, Windows, Linux

---

## Download v0.8.16

| Platform | Installer |
|---|---|
| macOS (Apple Silicon) | [VoxiPrompter_0.8.16_aarch64.dmg](https://github.com/voxiteam/voxiprompter/releases/latest/download/VoxiPrompter_0.8.16_aarch64.dmg) |
| Windows (x64) | [VoxiPrompter_0.8.16_x64-setup.exe](https://github.com/voxiteam/voxiprompter/releases/latest/download/VoxiPrompter_0.8.16_x64-setup.exe) |
| Linux (x64 .deb) | [voxiprompter_0.8.16_amd64.deb](https://github.com/voxiteam/voxiprompter/releases/latest/download/voxiprompter_0.8.16_amd64.deb) |
| Linux (x64 AppImage) | [voxiprompter_0.8.16_amd64.AppImage](https://github.com/voxiteam/voxiprompter/releases/latest/download/voxiprompter_0.8.16_amd64.AppImage) |

All installers are also available on the [latest release page](https://github.com/voxiteam/voxiprompter/releases/latest).

> **macOS note:** VoxiPrompter is not yet code-signed. If macOS reports the app is "damaged," open Terminal and run:
> ```
> xattr -cr /Applications/VoxiPrompter.app
> ```

---

## How It Works

1. **Paste your script** into VoxiPrompter
2. **Press Space** to start listening
3. **Speak naturally** -- the teleprompter follows your voice

The AI model downloads automatically the first time you start listening. After that, everything works offline with zero latency.

---

## Features

**On-Device Speech Recognition**
- AI-powered voice matching scrolls the teleprompter in real time
- 8 languages: English, Indonesian, Chinese, Japanese, Russian, Arabic, Thai, Vietnamese
- Speaking Pace presets (Fast / Normal / Slow) adapt to your delivery style
- Works completely offline after the one-time model download

**Auto-Scroll Mode**
- Constant-speed scrolling without using a microphone
- Adjustable speed from 1x (slow crawl) to 10x (speed read)
- Start, pause, and resume with the Space key or Start button
- Perfect for pre-recorded content, rehearsals, or music lyrics

**Live Production & OBS Integration**
- Browser Source overlays for teleprompter display and live captions in OBS Studio
- OBS dock panel for controlling VoxiPrompter from within OBS
- Script markers trigger OBS commands hands-free:
  - `[SCENE: name]` -- switch scenes
  - `[SHOW: source]` -- show a source
  - `[HIDE: source]` -- hide a source
- Compatible with OBS Studio, Streamlabs, XSplit, vMix, Twitch Studio, Ecamm Live

**Controls & Navigation**
- Click any word in the live monitor to jump the cursor there
- Mobile remote control from your phone over Wi-Fi (scan the QR code)
- Cursor position preserved between sessions
- Built-in auto-updater keeps you on the latest version

---

## Keyboard Shortcuts

| Key | Action |
|---|---|
| Space | Start / Stop listening or auto-scroll |
| Home | Reset cursor to beginning |
| Left Arrow | Back 10 words |
| Right Arrow | Forward 10 words |

---

## Pricing

| | Free | Pro |
|---|---|---|
| Price | **$0** | **$99** one-time |
| Launch price | -- | **$59** with code **LAUNCH40** |
| Script length | Up to 1,500 characters | Unlimited |
| All features | Yes | Yes |

Single-machine license. Transferable between machines -- deactivate on one, activate on another. Fully offline after activation.

**[Get Pro for $59 (launch price)](https://store.voxiprompter.com/buy/52430574-955b-486e-9af5-d96d800dd6df?discount=LAUNCH40)**

---

## Support
- **Website & documentation:** [voxiprompter.com](https://voxiprompter.com)
- **Contact support:** [voxiprompter.com/support](https://voxiprompter.com/support)
- **Bug reports:** [github.com/voxiteam/voxiprompter/issues](https://github.com/voxiteam/voxiprompter/issues)
---

(c) 2026 VoxiPrompter. All rights reserved.
