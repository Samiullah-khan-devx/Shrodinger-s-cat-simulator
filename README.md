# Schrödinger's Cat Simulator

**A quantum wavefunction collapse simulator built for [Hack Club Entropy](https://entropy.hackclub.com).**

> [Entropy](https://entropy.hackclub.com) is a Hack Club YSWS (You Ship, We Ship) — build something based in randomness, get custom dice and stickers.

---

## Quick Start

1. Download [`cat.html`](cat.html)
2. Double-click to open in any browser
3. Click the box — or press **Space** — to observe the cat

**No compiler. No server. No `npm install`. No build step. Just a file.**

---

## What is This?

Erwin Schrödinger's famous thought experiment (1935): a cat is placed in a sealed box with a quantum-triggered poison vial. Until the box is opened, the cat exists in a **superposition** of both alive **and** dead. The act of observation **collapses the wavefunction**, forcing reality into one definite state.

This simulator lets you run that experiment yourself. Adjust the probabilities. Collapse the wavefunction. Watch the statistics accumulate. Question the nature of reality.

---

## Features

- **Wavefunction collapse** — click the box or hit Observe
- **Adjustable quantum odds** — 50/50, 80/20, 99/1, and more
- **Auto-run mode** — repeatedly collapse cats (many worlds, after all)
- **Live statistics** — total observations, alive count, dead count
- **Probability bar** — visual ratio of survival vs. poison
- **Keyboard shortcuts** — Space/Enter to observe or reset
- **14 thematic status messages** — each collapse gets unique quantum commentary
- **Zero dependencies** — pure HTML, CSS, and JavaScript

---

## Probability Modes

| Mode   | Alive | Dead |
| ------ | ----- | ---- |
| 50/50  | 50%   | 50%  |
| 80/20  | 80%   | 20%  |
| 20/80  | 20%   | 80%  |
| 99/1   | 99%   | 1%   |
| 1/99   | 1%    | 99%  |

---

## How It Works

The cat exists in an unobserved quantum state (superposition). When the user triggers an observation, `Math.random()` generates a value compared against the selected probability threshold. The wavefunction collapses, the box opens, and the cat is revealed as alive or dead.

This models the **Copenhagen interpretation** of quantum mechanics: observation determines reality. The simulation uses a pseudo-random number generator — close enough for a thought experiment.

---

## Project Structure

```
├── cat.html        # Schrödinger's Cat Simulator
├── README.md       # This file
└── LICENSE         # MIT License
```

---

## Entropy Compliance

| Requirement | Status |
|------------|--------|
| Open source | ✅ MIT License |
| Has a README.md | ✅ You're reading it |
| Utilizes randomization | ✅ Core mechanic is quantum probability |
| Works out of the box (no compiling) | ✅ Open in browser |
| Tracked with Hackatime | ⏳ _(track your hours with [Hackatime](https://hackatime.hackclub.com) while coding)_ |

---

## Submission

To submit this project to Entropy:

1. Push this repo to **GitHub** (make it public)
2. Go to [entropy.hackclub.com](https://entropy.hackclub.com) and click **Submit your build!**
3. Fill out the submission form with your project details and GitHub link
4. Ensure you've tracked **5+ hours** with [Hackatime](https://hackatime.hackclub.com) for the custom dice set

---

## License

[MIT](LICENSE) — do whatever you want.
