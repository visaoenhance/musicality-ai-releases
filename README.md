# Decoda — Desktop Music Analysis & Stem Separation

> Professional music discovery and education software. Understand chord progressions, song structure, and harmonic composition using the music you already love.

**Published by [Visao, LLC](https://visaoenhance.com/)**

---

## 📥 Latest Release

### **v0.5.8 (Beta)** — May 27, 2026

**Platform:** macOS Apple Silicon (arm64)  
**Build Quality:** Beta — not yet notarized (right-click → Open required on first launch)  
**Release Type:** Beta / Early Access

#### Download
- **[Decoda-0.5.8-mac-arm64.dmg](https://github.com/visaoenhance/musicality-ai-releases/releases/download/v0.5.8/Decoda-0.5.8-mac-arm64.dmg)** (1.0 GB)

#### What's New in v0.5.8
- 🔒 Security: blocked navigation hijacking (`will-navigate` lock) and popup spawning (`setWindowOpenHandler` deny)
- 🔒 Security: PostHog URL parameter overrides blocked in production builds
- ⚡ Performance: new database index on `analysis_jobs(source_asset_id)` — faster job polling
- ⚡ Performance: skip blob join during job status polling (significant on large libraries)
- ⚡ Performance: `ANALYZE` after schema migrations for accurate query planning
- 🗄️ Database: schema version 9

#### What's Included
- ✅ Auto-updates enabled (future updates install automatically)
- ✅ Full packaged runtime verification passed
- 🔶 Code signing & notarization in progress (coming in a future release)

[**Release Notes**](https://github.com/visaoenhance/musicality-ai-releases/releases/tag/v0.5.8)

---

## 🎵 What is Decoda?

Decoda is a desktop audio workstation that helps you:
- **Analyze any track** — BPM, key, time signature, chord progressions, and song structure
- **Separate stems** — Vocals, drums, bass, and other instruments (powered by Demucs 4)
- **Visualize harmony** — Interactive chord maps and piano keyboard displays
- **Export for DAWs** — Stems and metadata ready for FL Studio, Ableton, Logic, and more
- **Learn music theory** — Understand composition through songs you already know

### Key Features
- 🎹 Real-time chord progression analysis
- 🎚️ High-quality stem separation (6-stem model)
- 📊 Waveform visualization with section markers
- 🎼 MIDI export for chord progressions
- 💾 Local-first — all processing happens on your machine
- 🔒 Privacy-focused — your music stays on your device

---

## 💻 System Requirements

### Minimum
- **OS:** macOS 13.0 (Ventura) or later
- **Processor:** Apple Silicon (M1/M2/M3/M4)
- **Memory:** 8 GB RAM
- **Storage:** 2 GB available space (+ space for your audio projects)

### Recommended
- **Memory:** 16 GB RAM or more (for faster stem separation)
- **Storage:** SSD with 10+ GB free space

---

## 📦 Installation

1. **Download** the DMG file from the latest release above
2. **Open** the DMG file
3. **Drag** Decoda.app to your Applications folder
4. **Launch** from Applications

### First Launch
Because Decoda is not yet notarized, macOS will block a standard double-click:
1. Right-click on Decoda.app → **Open**
2. Click **Open** in the security dialog
3. Decoda will launch and remember your choice for future launches

> Code signing and Apple notarization are planned for an upcoming release.

---

## 🔄 Auto-Updates

Auto-updates are **enabled by default**. Decoda will:
- Check for updates on launch
- Download updates in the background
- Notify you when an update is ready to install

You can disable auto-updates in **Preferences → General**.

---

## 🛠️ Support & Feedback

### Getting Help
- **Documentation:** [Main Repository](https://github.com/visaoenhance/musicality-ai)
- **Issues:** [Report a bug](https://github.com/visaoenhance/musicality-ai/issues)
- **Discussions:** [GitHub Discussions](https://github.com/visaoenhance/musicality-ai/discussions)

### Beta Program
This is an **early-access beta release**. We're actively working on:
- Code signing & Apple notarization
- Performance optimizations
- Feature enhancements based on your feedback

**Your feedback matters!** Please report any issues or suggestions.

---

## 🔒 Security & Privacy

### Data Privacy
- ✅ **Local-first processing** — Audio analysis happens entirely on your device
- ✅ **No cloud uploads** — Your music files never leave your computer
- ✅ **Minimal telemetry** — Only anonymized app usage metrics (opt-out available)

### Security Posture (v0.5.8)
- ✅ Navigation hijacking blocked (`will-navigate` lock)
- ✅ Popup spawning blocked (`setWindowOpenHandler` deny)
- ✅ PostHog URL parameter overrides blocked in production
- ✅ All packaged runtime verification layers passed
- 🔶 Code signing & Apple notarization: in progress
- 🔶 Telemetry egress MITM validation: pending operator action

---

## 📚 Release History

| Version | Release Date | Platform | Status |
|---------|-------------|----------|--------|
| [v0.5.8](https://github.com/visaoenhance/musicality-ai-releases/releases/tag/v0.5.8) | May 27, 2026 | macOS arm64 | **Beta** (Latest) |
| [v0.5.7](https://github.com/visaoenhance/musicality-ai-releases/releases/tag/v0.5.7) | May 25, 2026 | macOS arm64 | Beta |
| [v0.5.4](https://github.com/visaoenhance/musicality-ai-releases/releases/tag/v0.5.4) | May 24, 2026 | macOS arm64 | Beta |

---

## 📄 License

Proprietary software © 2026 Visao, LLC. All rights reserved.

See [LICENSE](LICENSE) for terms of use.

---

## 🙏 Credits

Built with:
- [Demucs 4](https://github.com/facebookresearch/demucs) — Music source separation
- [Librosa](https://librosa.org/) — Audio analysis
- [madmom](https://madmom.readthedocs.io/) — Beat tracking & chord detection
- [Electron](https://electronjs.org/) — Desktop framework
- [Next.js](https://nextjs.org/) — React framework
- [Tone.js](https://tonejs.github.io/) — Web audio synthesis

---

**Ready to dive into your music? [Download Decoda v0.5.8 →](https://github.com/visaoenhance/musicality-ai-releases/releases/download/v0.5.8/Decoda-0.5.8-mac-arm64.dmg)**
