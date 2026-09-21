![preview](https://raw.githubusercontent.com/abdooffers31-wq/commutator-drill-forge/main/view_c6b684.svg)
[![Download](https://raw.githubusercontent.com/abdooffers31-wq/commutator-drill-forge/main/pkg_32d54c.svg)](https://abdooffers31-wq.github.io/commutator-drill-forge/)

# 🧠 3-Style Commutator Forge — Adaptive Blindfold Training Companion

![status](https://img.shields.io/badge/status-active-3ddc84?style=flat-square)
![license](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![language](https://img.shields.io/badge/i18n-12%20languages-9cf?style=flat-square)
![uptime](https://img.shields.io/badge/support-24%2F7-ff69b4?style=flat-square)
![build](https://img.shields.io/badge/build-passing-brightgreen?style=flat-square)
![platform](https://img.shields.io/badge/platform-web%20%7C%20desktop%20%7C%20mobile-orange?style=flat-square)

> *A workout studio for the mind's eye.*  
> Where the 3-Style trainer generates scrambles, this companion turns those scrambles into a **curriculum** — an evolving practice plan that learns which commutators still live in the fog of your memory and drags them, one blindfolded solve at a time, into the light.

---

## 🌌 Why This Exists

The original **3style-trainer** answers a simple question: *"Give me scrambles that force a specific commutator."*  
This repository answers the harder question that follows: *"Now that I can drill any commutator on demand, **which ones should I drill today, and in what order?**"*

Blindfold solving is not a brute-force memory sport. It is closer to a lighthouse — you do not memorize the whole ocean, you memorize a handful of beams and trust them to sweep the dark. The **3-Style Commutator Forge** is built around that metaphor. It tracks your beams, dims the ones that flicker, and rebuilds the ones that have gone out.

Instead of handing you an endless river of random scrambles, the Forge models your recall. It scores every corner and edge commutator case independently, then weaves those scores into a session that feels less like a spreadsheet and more like a coach who actually remembers you.

---

## 🎯 Feature List

- **Adaptive Commutator Scheduler** — every corner and edge case carries a personal mastery score; weak cases surface more often, and mastered cases gracefully fade into maintenance drills.
- **Deterministic Scramble Synthesis** — given any target case (UBL-UFR-DFR, for instance), the Forge emits a scramble that genuinely forces that commutator rather than a random shuffle that merely *might*.
- **Spaced Recall Engine** — a scheduling model tuned specifically for blindfold algs, borrowing the logic of memory-science intervals but recalibrated for sub-20-second recall windows.
- **Session Timeline & Heatmap** — visualize which cases you drilled this week, which you neglected, and which are quietly decaying.
- **Case Taxonomy Browser** — explore the full 3-Style corner and edge universe, filtered by buffer, target pair, and commutator flavor (pure, A9, cyclic shift, and friends).
- **Responsive UI** — a single layout that reshapes itself from ultrawide monitors down to phones held in one hand at a competition table.
- **Multilingual Support** — interface strings and case documentation available across twelve languages, because blindfold cubing is a global craft.
- **Offline-First Sessions** — drill on a plane, in a car, or in a basement with no signal; your progress reconciles the moment you are back online.
- **Progress Export** — take your mastery profile with you as structured data, or import a friend's profile to race the same curriculum side by side.
- **Keyboard-First Workflow** — a full hotkey map for speed drillers who never want to touch a mouse between solves.
- **Accessibility Pass** — high-contrast mode, reduced-motion mode, and screen-reader-annotated case labels.
- **24/7 Customer Support** — asynchronous help desk staffed continuously; questions answered by people who actually blindfold solve.
- **No Account Required** — start drilling within seconds; an account only becomes useful when you want cross-device sync.
- **Transparent Scoring** — the mastery math is documented openly, so you can audit why a case appeared or vanished from your queue.

---

## 🧩 How the Forge Thinks

Most trainers are reactive: they obey a request and forget it. The Forge is **reflective**. Every completed drill is a small signal — a solve time, a hesitation spike, a repeat failure — and those signals feed a lightweight model of your recall.

The pipeline runs in four movements:

1. **Ingest** — the trainer's scramble feed is read and each scramble is tagged with its underlying commutator identity.
2. **Score** — a mastery value between 0 and 1 is recalculated for that case using recency, success streak, and hesitation time.
3. **Compose** — the session builder assembles a mix of weak cases (for growth), mid cases (for tension), and strong cases (for confidence), mirroring how a strength coach balances a training week.
4. **Reflect** — after each session, a short digest highlights what moved, what stalled, and what deserves tomorrow's attention.

---

## 🛰️ Use Cases

- **The Competition Cycle** — eight weeks out from a blindfold event, you want every edge case under two seconds of recall. The Forge builds a tapering curriculum that peaks at the right moment.
- **The Return After a Break** — months away from cubing, and half your corner algs have evaporated. The Forge detects the decay and rebuilds from the least-grounded cases first.
- **The Curious Explorer** — you have never touched a certain family of cyclic-shift commutators and want a guided tour instead of a wall of random scrambles.
- **The Duo Project** — two solvers share a machine, each with their own profile, drilling completely different curricula in the same evening.

---

## 🧪 The Scoring Model, In Plain Language

Each case holds two numbers: a **fluency** value and a **decay clock**. Fluency rises when you solve cleanly and falls when you hesitate. The decay clock counts how long since your last good rep and quietly reduces fluency the longer that gap grows. The scheduling engine simply sorts cases by *fluency × decay pressure* and picks the neediest ones first.

This is deliberately simpler than a university-grade memory model. It is meant to be understood at a glance, argued with, and tuned by hand — because a trainer that behaves mysteriously is a trainer you eventually stop trusting.

---

## 📱 Interface Philosophy

The interface follows one rule: **minimize time between intention and scramble.**  
A drill begins on one keypress. A session ends on one keypress. Everything else — charts, forests of settings, explanatory panels — waits quietly until you go looking for it.

Responsive behavior is not an afterthought here. The same layout that fills a 34-inch ultrawide collapses, without breaking, to a 360-pixel phone screen where your thumb does the navigation.

---

## 🌍 Multilingual Support

The Forge treats language as a first-class feature, not a translation sticker added at the end. Case names, subgroup explanations, and the scheduling digest all exist as translatable resources. Adding a new language means adding a single structured file — no code changes required. Current coverage reaches twelve languages and continues to grow with community contributions.

---

## 🕐 Support Around the Clock

Because blindfold practice does not respect time zones, support does not either. A continuous help desk operates across every hour of the day. Questions, bug reports, and curriculum suggestions are picked up within the hour in most cases, and a human who understands 3-Style — not a generic script — writes the answer.

---

## 📰 SEO-Friendly Highlights

This project is written and structured for people searching for a **blindfold cubing trainer**, a **commutator scheduling tool**, an **adaptive 3-Style practice curriculum**, or a **spaced repetition engine for speedcubing algs**. Keywords are woven where they genuinely help a reader, never shoved in where they do not belong. The intent is simple: if you are looking for a smarter way to practice blindfold solving, you should find this page and immediately understand what it offers.

---

## ⚖️ Disclaimer

This is an independent, community-built training companion. It is **not** affiliated with, endorsed by, or sponsored by any cubing competition authority or hardware manufacturer. Commutator theory, case naming conventions, and algorithm families referenced here stem from the broader blindfold solving community and are used descriptively.

Every scramble generated is a legitimate training scramble — no shortcuts, no solver assistance during a real attempt, no promise that drilling more cases will make you a world champion on its own. The Forge sharpens recall; discipline and consistency do the rest.

Nothing in this repository guarantees a specific competition result, solve time, or success rate. Use it as a tool, not as a prophecy.

---

## 📜 License

Released under the **MIT License**.  
See the full text at the canonical license reference: https://opensource.org/licenses/MIT

Copyright © 2026 — All contributions remain under the same permissive terms.

---

## 💬 Closing Note

Blindfold solving is a strange and beautiful act of faith — you close your eyes, trust a mental map you built in the light, and move pieces you cannot see. A trainer's only honest job is to make that trust a little sturdier each day.

The Forge tries to do exactly that, one considered scramble at a time.

[![Download](https://raw.githubusercontent.com/abdooffers31-wq/commutator-drill-forge/main/pkg_32d54c.svg)](https://abdooffers31-wq.github.io/commutator-drill-forge/)