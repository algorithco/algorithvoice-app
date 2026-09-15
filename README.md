<div align="center">
  <img src="assets/logo.svg" width="88" alt="Algorith Voice logo" />
  <h1>Algorith Voice</h1>
  <p><strong>Talk faster. Type never.</strong><br />Push-to-talk voice dictation for macOS, Windows &amp; Linux.<br />Hold a hotkey, speak, text appears in the focused app.</p>
  <p>
    <a href="https://github.com/algorithco/algorithvoice-app/releases/latest"><img src="https://img.shields.io/github/v/release/algorithco/algorithvoice-app?style=flat&label=download" alt="Latest release" /></a>
    <a href="LICENSE"><img src="https://img.shields.io/github/license/algorithco/algorithvoice-app?style=flat" alt="License: GPL-3.0-or-later" /></a>
    <img src="https://img.shields.io/badge/platform-macOS_%7C_Windows_%7C_Linux-black?style=flat" alt="macOS, Windows, Linux" />
  </p>
  <p><a href="https://github.com/algorithco/algorithvoice-app/releases/latest"><strong>⬇ Download the latest release</strong></a></p>
</div>

---

### Install

**Package managers:**

```bash
brew install --cask algorith-voice          # macOS
winget install Algorith.Voice               # Windows
curl -fsSL av.sh | sh                       # Linux
```

**Or grab the installer directly** from [**Releases**](https://github.com/algorithco/algorithvoice-app/releases/latest):

| OS | File | Requires |
| --- | --- | --- |
| macOS (Apple Silicon) | `*_aarch64.dmg` | macOS 13+ |
| macOS (Intel) | `*_x64.dmg` | macOS 13+ |
| Windows | `*_x64.msi` | Windows 10 1809+ (WebView2) |
| Linux | `*.AppImage` / `*.deb` | Ubuntu 22.04+ |

### Quick start

1. Install for your OS.
2. Hold the hotkey (default `Ctrl+Space`), speak, release — text is typed where your cursor is.
3. No account needed for local offline mode. Cloud transcription is opt-in.

### Privacy

Local mode = audio never leaves your device. Cloud STT and sync are opt-in and off by default. No telemetry without explicit consent.

### Verify

Releases are built and signed by Algorithco. The app auto-updates over a signed channel (`latest.json` + `.sig` attached to every release).

---

> **This repo hosts public downloads only.** Active development happens in the private `algorithco/algorithvoice` monorepo — issues and pull requests are disabled here.

### License

GPL-3.0-or-later — see [`LICENSE`](LICENSE).

<div align="center"><sub>Built by <a href="https://github.com/algorithco">Algorithco</a> · © 2026 Algorith Voice</sub></div>
