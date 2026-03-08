# ◎ UNSTUCK — Mood & Creativity Reset App

> **No affirmations. No fluff. Just a thing to actually do.**

🔗 **Live App:** [C9Shikha18.github.io/unstuck](https://your-username.github.io/unstuck)
📱 **Works offline** · Installable on Android & iPhone · No app store needed

---

## The Problem

Most people have days where they feel stuck creatively blocked, emotionally flat, spinning with too many thoughts, or too anxious to start anything. The current solutions fall into two camps:

- **Wellness apps** (Calm, Headspace) — beautiful, passive, and easy to close without doing anything
- **Productivity apps** (Todoist, Notion) — great for structured work, useless when your brain won't cooperate

Neither solves the real problem: **getting from "stuck" to "doing something" in under 5 minutes.**

---

## User Research

Before building, I talked to 8 people across different jobs and age groups about what they do when they feel creatively or emotionally stuck during the day.

**Key findings:**

- 7 of 8 said they open their phone when stuck but end up scrolling, which makes it worse
- "Journaling prompts" were universally described as something people *intend* to do but never actually follow through on
- The most effective unstuck moments people recalled were **weird, specific, physical actions** not reflection
- People want honesty, not motivation. *"I don't need to be told I've got this. I need someone to tell me what to do right now."*
- The #1 barrier to starting: **not knowing the first step**

**The insight:**  
People don't need more content or inspiration. They need a **forcing function** a specific, low-stakes action that breaks the inertia.

---

## The Solution

UNSTUCK is a **daily creative sprint app** built around a 3-part habit loop:

```
CUE → Pick your current state honestly
ROUTINE → Get a raw reframe + weird creative challenge
REWARD → Complete the sprint, see your streak grow
```

### Core Features

| Feature | Why it exists |
|---|---|
| **8 honest mood states** | Real descriptions people actually recognize in themselves (not "stressed" or "sad") |
| **3 sprint lengths** | 2, 5, or 10 min — removes the "I don't have time" excuse |
| **First Step** | Every challenge shows the single first action removes all friction |
| **Sprint timer** | Forces time-boxing; scratchpad lets you capture output |
| **Streak tracker** | Builds the daily habit through visible progress |
| **Sprint log** | Saves every session with your notes creates a personal creative record |
| **Stats dashboard** | Weekly chart, mood breakdown, challenge type patterns |
| **Sound design** | Distinct audio feedback for every interaction + satisfying completion sound |

---

## Design Decisions

**Why offline-first?**  
The most important moment to use this app is when you're feeling low or stuck exactly when you might have bad wifi, be on the go, or not want to wait for anything to load. Every feature works with zero internet after first install.

**Why brutalist design?**  
The target user is already overstimulated. Calm pastels and rounded corners signal "another wellness app." The raw, high-contrast aesthetic signals: *this is different, this is direct.* It also fits the brand promise no fluff.

**Why built-in challenges instead of AI?**  
Early version used an AI API. Removed it for v2 because: 
(1) offline requirement
(2) latency broke the "get unstuck now" feeling
(3) 80+ hand-crafted challenges across 8 moods × 3 intensities gave more consistent quality and zero cost.

---

## Metrics I'd Track (If This Were a Real Product)

| Metric | Target | Why |
|---|---|---|
| Day-1 retention | > 40% | First day return = habit formation started |
| Day-7 streak rate | > 20% | Weekly habit = sticky product |
| Sprint completion rate | > 65% | Measures if challenges are well-calibrated |
| Sessions per active day | > 1.5 | Multiple sessions = real daily use |
| Avg sprint length chosen | Monitor split | Tells us if 2-min is a crutch or a gateway |
| Mood distribution | Monitor | Reveals most underserved emotional states |

---

## Tech Stack

| Layer | Choice | Reason |
|---|---|---|
| Frontend | Vanilla HTML/CSS/JS | Zero dependencies, instant load, works offline |
| Offline | Service Worker + Cache API | Full PWA — installs on home screen |
| Storage | localStorage | No backend needed, private by default |
| Sound | Web Audio API | Synthesized programmatically, no audio files to load |
| Fonts | Google Fonts (Anton + DM Sans) | Cached after first load |
| Hosting | GitHub Pages | Free, fast, no server maintenance |

---

## Install on Your Phone

**Android:**
1. Open the live URL in Chrome
2. Tap ⋮ menu → "Add to Home Screen"

**iPhone:**
1. Open the live URL in **Safari**
2. Tap the Share button → "Add to Home Screen"

After install, the app works fully offline. Your data never leaves your device.

---

## About This Project

Built as a **product management portfolio project** to demonstrate:
- User research → insight → product decision making
- Habit loop product design (Cue → Routine → Reward)
- Shipping a complete, polished product end-to-end
- Technical fluency: PWA, offline-first, Web Audio API

**Background:** I'm transitioning from 5+ years as a Windows Systems Administrator into Product Management. This project draws on real observations from working in high-stress IT/Software environments where people are constantly context-switching, alert-fatigued, and never taught how to reset.

---

*Built by Shikha Choudhury · [LinkedIn](https://www.linkedin.com/in/shikha-choudhury/) · [Email](mailto:shikh009.product@gmail.com)*
