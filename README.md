# Play 'N Learn 🎮✨

> **Turn screen time into learning time.**  
> Browser-based educational games that use your camera, hands, and body — no app install needed.

---

## The Problem

Kids and teens spend hours passively scrolling. Play 'N Learn flips that: instead of consuming content, they move, solve, and discover — all inside a web browser.

---

## What Is This?

**Play 'N Learn** is an open-source collection of browser-based educational games built with vanilla HTML, CSS, and JavaScript. Each game uses real-time computer vision (camera + MediaPipe) to make learning a physical, interactive experience.

Designed by **Abbas Madwani**, 4th Year Design Student.

Aligned with **UN Sustainable Development Goal 4 — Quality Education**.

---

## Games

### 🧪 Plasma Elements
**Subject:** Chemistry · **Grade Level:** 6th – 9th Grade

An interactive periodic table where students physically drag atoms together using hand gestures to trigger real chemical reactions.

- Pinch and grab atoms with your hand via camera tracking
- Combine elements to form real molecules (H₂O, NaCl, CO₂, NH₃, and more)
- Full 118-element periodic table rendered as a live canvas grid
- Generative ambient audio and explosion effects for engagement
- Teaches: element symbols, groups, periods, and basic reaction chemistry

**Tech:** MediaPipe Hands · Web Audio API · HTML5 Canvas

---

### ➕ Math Simon Says
**Subject:** Mathematics · **Grade Level:** Kindergarten (Ages 4–6)

A full-body math game where kids answer arithmetic questions by jumping or squatting — the right answer is tied to the right movement.

- Camera detects your pose in real time
- A math problem appears with two possible answers — one per action
- Jump = one answer · Squat = the other
- Timer, score tracking, and animated feedback keep kids engaged
- Turns passive sitting into active physical + cognitive play

**Tech:** MediaPipe Pose · HTML5 Canvas · CSS Animations

---

## Why It Matters

| Goal | How Play 'N Learn Addresses It |
|------|-------------------------------|
| SDG 4 – Quality Education | Free, accessible, curriculum-aligned games for K–9 |
| Reduce Passive Scrolling | Replaces passive screen time with active, embodied learning |
| No Install Barrier | Runs entirely in the browser — no app, no download |
| Inclusive Access | Works on any device with a camera and a browser |

---

## How to Run

No server needed. Just open the HTML files in any modern browser (Chrome recommended for best camera support).

```
plasma-grid.html       → Plasma Elements (Chemistry)
math-simon-says.html   → Math Simon Says (Kindergarten Math)
```

Allow camera access when prompted. That's it.

---

## Tech Stack

- **Vanilla HTML / CSS / JavaScript** — no frameworks
- **MediaPipe Hands & Pose** — real-time hand and body tracking via CDN
- **Web Audio API** — generative sound design
- **HTML5 Canvas** — all game rendering

---

## Roadmap

- [ ] More games across more subjects (geography, biology, language)
- [ ] Difficulty levels per game
- [ ] Multiplayer / classroom mode
- [ ] Progressive Web App (PWA) support for offline play
- [ ] Teacher dashboard for progress tracking

---

## License

© 2025 Abbas Madwani. All rights reserved.
This project and its source code are publicly visible for review and educational purposes only. No part of this project may be copied, modified, distributed, or used in any form without explicit written permission from the author.

---

*Built with ❤️ and Claude · Prototype v1.0*
