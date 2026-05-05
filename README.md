# ClosetMind App

A weather- and occasion-aware wardrobe management desktop application
with rule-based outfit recommendation.

This repository hosts the **packaged application binaries** for macOS
(`.dmg`) and Windows (`.exe`, planned). Source code lives in a separate
repository.

## Download

Visit the [Releases page](https://github.com/chentzuyuan/ClosetMind_App/releases)
to download the latest version for your platform.

| Platform | File | Notes |
|----------|------|-------|
| macOS    | `ClosetMind-<version>.dmg` | Apple Silicon / Intel |
| Windows  | `ClosetMind-Setup-<version>.exe` | Coming soon |

## What does it do?

Each morning ClosetMind reads your calendar to determine the day's
occasion and pulls in the current weather conditions. It then filters
out unwearable items (dirty or archived) and ranks candidate outfits
using a rule-based scoring engine across three dimensions:

- **Color harmony** — 60/30/10 color theory
- **Fabric compatibility** — same-fabric bonus, mixed-fabric
  reasonableness, warmth adequacy relative to weather
- **Style consistency** — style-tag coherence and style ↔ occasion fit

The output is one best recommended outfit plus 3–5 ranked alternatives,
each with a score breakdown and a human-readable explanation.

## Installation

### macOS

1. Download `ClosetMind-<version>.dmg` from
   [Releases](https://github.com/chentzuyuan/ClosetMind_App/releases).
2. Double-click the `.dmg` to mount it.
3. Drag the **ClosetMind** app icon into your `Applications` folder.
4. The first time you launch it, macOS may ask you to confirm —
   right-click the app and choose **Open**.

### Windows

Coming soon.

## Project information

This is a school project for **EPPS 6354 — Information Management** at
UT Dallas.

Live demo (web version): <https://chentzuyuan.github.io/closetmind.html>

## License

For educational and demonstration purposes.
