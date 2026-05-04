# Systems Engineering Memory Palace 🛕

**Learn the V-Model lifecycle by walking through the Lepakshi Temple - a 16th-century Vijayanagara masterpiece in Andhra Pradesh, India.**

A fun interactive 80s game style memory palace with Lepakshi temple as reference. 

Each temple location maps to a Systems Engineering phase from ISO 15288. Explore room by room, answer SE challenges based on real engineering failures, and build bilingual (EN/DE) vocabulary along the way.

[![Live Demo](https://img.shields.io/badge/Live-Demo-gold?style=for-the-badge)](https://psykris.github.io/systems-engineering-memory-palace/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

---

## 🎮 What is this?

An interactive, retro RPG-styled educational tool that teaches the **V-Model Systems Engineering lifecycle** through a **memory palace** technique - mapping abstract engineering processes to physical locations you can mentally walk through.

| Temple Location | SE Phase | V-Side |
|---|---|---|
| 🐂 Monolithic Nandi | Stakeholder Needs & ConOps | Left (Top) |
| 🏛️ Entrance Gopuram | System Requirements Definition | Left |
| 💃 Natya Mandapam | System Architecture Design | Left |
| 🪨 Hanging Pillar | Detailed Design (V-Pivot) | Bottom |
| 🕉️ Main Shrine | Implementation | Bottom |
| 🐍 Nagalinga | Verification & Testing | Right |
| 💒 Kalyana Mandapam | Validation & Acceptance | Right (Top) |
| 👣 Sita's Footprint | Operations & Lifecycle | Beyond the V |

## ✨ Features

- **Pixel art scenes** for each temple location (SVG-based, no image files)
- **Global EN/DE language toggle** - every label, briefing, quiz, and term switches
- **Side quest challenges** based on real SE failures (Mars Climate Orbiter, Therac-25, Mars Polar Lander)
- **SE Sensei glossary** with bilingual terminology at each location
- **V-Model linkage** showing how each phase connects to its verification pair
- **8-bit chiptune soundtrack** (Web Audio API, no external files) with 3-level volume control
- **Progress tracking** across all 8 locations
- **Print companion** - clean A4 reference sheet via browser print
- **Fully self-contained** - single HTML file, no build tools, no dependencies
- **Responsive** - works on mobile, tablet, and desktop

## 🚀 Try it

**Option 1: GitHub Pages** (recommended)

Visit the [live demo](https://psykris.github.io/systems-engineering-memory-palace/)

**Option 2: Local**

```bash
git clone https://github.com/psykris/systems-engineering-memory-palace.git
cd systems-engineering-memory-palace
open index.html
```

That's it. No `npm install`. No build step. One HTML file.

## 🏗️ Tech Stack

| What | How |
|---|---|
| Rendering | Vanilla HTML/CSS/JS |
| Pixel art | Inline SVG (no image files) |
| Typography | Press Start 2P + VT323 (Google Fonts) |
| Audio | Web Audio API (oscillators, no audio files) |
| Deployment | GitHub Pages (static) |

## 🎓 SE Standards Covered

- **ISO 15288** - System Life Cycle Processes
- **V-Modell XT** - German government IT procurement lifecycle
- **IEEE 29148** - Requirements Engineering
- **ARP 4754A** - Aircraft/System Development Processes
- **IREB CPRE** - Requirements Engineering certification body of knowledge
- **EARS** - Easy Approach to Requirements Syntax
- **FMEA / HARA** - Failure Mode and Hazard Analysis
- **SysML / SAF** - Model-Based Systems Engineering

## 🧠 Why a Memory Palace?

The [method of loci](https://en.wikipedia.org/wiki/Method_of_loci) is one of the oldest and most effective memorization techniques. By anchoring abstract concepts to physical locations you know well, retention improves dramatically.

The Lepakshi Temple works particularly well because:
- Its walking path follows a natural sequence (entrance → inner chambers → exit)
- Each location has distinctive architectural features that create strong visual anchors
- The temple is a real place you can visit (Hindupur, Andhra Pradesh, India)
- Links to explore
- [Wikipedia - Veerabhadra Temple - Lepakshi](https://en.wikipedia.org/wiki/Veerabhadra_Temple,_Lepakshi)
- [Incredible India](https://www.incredibleindia.gov.in/en/andhra-pradesh/anantapur/lepakshi-temple)
- [Lepakshi Temple Official Website](https://lepakshitemple.in/)
- [UNESCO Heritage Site Lepakshi](https://whc.unesco.org/en/tentativelists/6607/)


## 📝 License

MIT - use it, fork it, teach with it.

## 🙏 Credits

- Temple mapping concept inspired by the Lepakshi Veerabhadra Temple, Hindupur, AP, India
- Inspired by Pixel art aesthetic using 16-bit era RPGs and the [Tulasi lyric video](https://www.youtube.com/watch?v=example) by Sumedh K
- The Mentalist TV show where I learned what a Memory Palace is for the first time (And then in Sherlock TV series ;))

---

*"The V-Model tells us WHAT. Agile tells us HOW. The lifecycle tells us WHEN to run the V again."*
