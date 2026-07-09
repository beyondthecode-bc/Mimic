<p align="center">
  <img src="images/banner.png" alt="Mimic — automation with a pulse" width="100%">
</p>

<p align="center">
  <strong>Humanized autoclicker and macro tool for macOS</strong><br>
  Clicks that feel human — randomized timing, never a robotic metronome. Build a run in plain English, or sequence multi-point macros on a canvas.
</p>

<p align="center">
  <a href="https://github.com/beyondthecode-bc/Mimic/releases/latest"><img src="https://img.shields.io/github/v/release/beyondthecode-bc/Mimic?style=flat-square&label=Download&color=blue" alt="Latest Release"></a>
  <a href="https://github.com/beyondthecode-bc/Mimic/releases/latest"><img src="https://img.shields.io/github/downloads/beyondthecode-bc/Mimic/total?style=flat-square&label=Downloads&color=brightgreen" alt="Downloads"></a>
  <a href="https://github.com/beyondthecode-bc/Mimic/stargazers"><img src="https://img.shields.io/github/stars/beyondthecode-bc/Mimic?style=flat-square" alt="Stars"></a>
  <img src="https://img.shields.io/github/license/beyondthecode-bc/Mimic?style=flat-square" alt="License">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-macOS%2014%2B-lightgrey?style=flat-square&logo=apple" alt="Platform">
  <img src="https://img.shields.io/badge/chip-Apple%20Silicon-orange?style=flat-square&logo=apple" alt="Apple Silicon">
  <img src="https://img.shields.io/badge/swift-6.1-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift">
  <img src="https://img.shields.io/badge/SwiftUI-native-007AFF?style=flat-square&logo=swift&logoColor=white" alt="SwiftUI">
  <img src="https://img.shields.io/badge/languages-8-green?style=flat-square&logo=translate" alt="Languages">
</p>

<p align="center">
  <a href="https://www.virustotal.com/gui/file/d6208ccd4014984e63e53c4f7409db90773a48b5516cd01ead514109dc28df5d"><img src="https://img.shields.io/badge/VirusTotal-0%2F66%20Clean-brightgreen?style=flat-square&logo=virustotal&logoColor=white" alt="VirusTotal"></a>
  <a href="https://github.com/sponsors/beyondthecode-bc"><img src="https://img.shields.io/badge/Sponsor-%E2%9D%A4-pink?style=flat-square&logo=github" alt="GitHub Sponsors"></a>
  <a href="https://www.buymeacoffee.com/BEYONDTHECODE"><img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=flat-square&logo=buymeacoffee&logoColor=black" alt="Buy Me a Coffee"></a>
</p>

<p align="center">
  Built with Swift and SwiftUI. No Electron, no web views, no bloat.
</p>

---

> [!NOTE]
> **This repository is the Mimic community hub** — signed release downloads,
> translations, and issue tracking. Mimic is a closed-source macOS app; its
> source code is not published here. **[Download Mimic from Releases](https://github.com/beyondthecode-bc/Mimic/releases/latest).**

Mimic is a premium, minimalist macOS autoclicker and lightweight macro tool. Its
signature is that its clicks feel *human* — randomized timing ("jitter") instead
of robotic uniformity — and it runs both single-action ("Sentence") and
multi-point macro ("Map") sequences.

## Features

- **Humanized clicking** — interval jitter so clicks don't land on a robotic
  metronome. Free includes a fixed ±100 ms; **Pro** adds an adjustable amount
  and five distribution presets (Basic, Natural, Cautious, Aggressive, Burst).
- **Sentence mode** — a plain-English builder: *"Press **left click** at the
  **current cursor** every **3 seconds** for **42 times**."*
- **Map mode** — an ordered, looping sequence of click points on a visual canvas,
  with per-step delays.
- **Click or keypress** — repeat a mouse button, or (Pro) press a keyboard key
  each cycle.
- **Targets** — the current cursor (free), or a fixed screen point / the
  frontmost app (Pro).
- **Global hotkeys + Panic-stop** — separate Start/Stop shortcuts, a live
  menu-bar status item, and launch-at-login.
- **Developer-ID signed + notarized** — no Gatekeeper "unidentified developer"
  wall.

Free to download and fully functional. **Mimic Pro ($10 one-time)** removes the
usage interstitial and unlocks unlimited saved routines, the advanced humanizer,
unlimited run length, Map looping, and keyboard/non-cursor targets.

## Screenshots

|  |  |
|---|---|
| ![Sentence mode](images/home-sentence.png) | ![Map mode](images/map-mode.png) |
| **Sentence mode** — build a run in plain English. | **Map mode** — sequence click points on a canvas. |
| ![Routines](images/routines.png) | ![Hotkeys](images/hotkeys.png) |
| **Routines** — save and reuse runs (unlimited with Pro). | **Hotkeys** — set global Start/Stop shortcuts. |
| ![License](images/license-pro.png) | ![Running](images/running.png) |
| **License** — activate Pro across up to 3 Macs. | **Running** — live countdown and status. |

<details>
<summary>More — light mode</summary>

| | |
|---|---|
| ![Light mode](images/home-light.png) | |
| **Light mode** — full light-appearance support. | |

</details>

## Download

Grab the latest signed `.zip` from the [Releases](https://github.com/beyondthecode-bc/Mimic/releases)
page. Each release ships a SHA-256 checksum and is notarized by Apple.

## Requirements

- macOS 14 (Sonoma) or later — Apple Silicon
- Accessibility permission (Mimic guides you through granting it on first launch)

## Get Mimic Pro

[Unlock Mimic Pro — $10 forever](https://beyondthecode.gumroad.com/l/mimic-pro).
Enter your license key in **Settings → License**. One purchase activates up to
**3 Macs**; deactivate any Mac to free a slot.

## Translations

Mimic is localized via XML files in [`languages/`](languages/). To contribute a
translation, copy `English.xml`, translate the values (keep the `key` attributes
unchanged), and open a pull request or a [Translation issue](https://github.com/beyondthecode-bc/Mimic/issues/new?template=translation.md).

## Support

- [Report a bug](https://github.com/beyondthecode-bc/Mimic/issues/new?template=bug_report.md)
- [Request a feature](https://github.com/beyondthecode-bc/Mimic/issues/new?template=feature_request.md)
- Homepage: https://beyondthecode.app

---

Made by [Beyond the Code](https://beyondthecode.app).
