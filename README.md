# 🎧 DJ PROMPTER // Practice Set Runner

A performance prompter and structured practice runner designed for DJs to master set transitions, phrasing, key changes, and high-risk technical cuts. Built for live booth use with dark mode ergonomics and hands-free footswitch support.

---

## ⚡ Features

- 🎯 **Zone-Based Practice Drills**: Categorized practice zones focusing on specific mixing skills:
  - **Zone 1**: Phrasing & Kick Matching
  - **Zone 2**: Harmonic Stress Test
  - **Zone 3**: Looping & Echo Out
  - **Zone 4**: Stinger & Quick Cut
  - **Zone 5**: Harmonic Release
- 🦶 **Hands-Free Footswitch Support**: Bluetooth page-turner / footswitch compatibility for stepping through prompts without taking hands off the decks.
- ⏱️ **Phrase & Blend Timers**: Real-time visual progress bars tailored to specific bar counts and BPM targets.
- 🚨 **Stinger Flash FX**: Full-screen visual alerts for stinger cuts and high-risk transition moments.
- 📋 **Structured Prompt Cards**: Includes setup checklist, trigger point, move sequence, bail out plan, and pass criteria for every transition.
- 📱 **Stage & Booth Ergonomics**: High-contrast, dark-mode responsive layout for laptops, iPads, and mobile screens.

---

## 🚀 Quick Start

### 1. Launch in Browser
Simply open [`runner.html`](file:///Users/stephencoleman/Desktop/djpractice/runner.html) (or `index.html`) directly in any web browser. No backend server required!

```bash
# Option A: Double-click runner.html or open via terminal on macOS
open runner.html
```

```bash
# Option B: Run a quick local HTTP server
npx serve .
# or
python3 -m http.server 8000
```

### 2. GitHub Pages Deployment
1. Go to repository **Settings** > **Pages**.
2. Under **Build and deployment** > **Branch**, select `main` branch and `/ (root)`.
3. Save to publish your DJ prompter online instantly!

---

## ⌨️ Controls & Footswitch Mapping

| Key / Control | Action |
| --- | --- |
| `Space` / `Page Down` | Advance to next step / Start timer |
| `Page Up` | Go to previous step |
| `Up Arrow` / `Down Arrow` | Navigate between transition cards |
| `Escape` | Reset current timer / Clear alerts |

*Note: Compatible with standard AirTurn, PageFlip, and USB/Bluetooth footswitches configured to Send PageDown/PageUp or Space.*

---

## 📁 Repository Structure

```text
djpractice/
├── index.html      # Entry redirect for static web hosting
├── runner.html     # DJ Prompter application engine & practice set data
├── .gitignore      # Git ignore configuration
├── LICENSE         # MIT License
└── README.md       # Project documentation
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
