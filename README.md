# ⚛️ Gamma Knife Challenge

An interactive neurosurgery simulation where you use converging gamma beams to destroy a brain tumor while protecting healthy brain tissue.

## Live Demo & Mobile Play
- **GitHub Pages:** `https://2ndreturn.github.io/GammaKnifeSIM/`

1. **Select Beam Count (1–201):** Adjust the slider to choose how many Cobalt-60 beams converge on the tumor. More beams speed up treatment and reduce damage to surrounding healthy brain tissue.
2. **Hold to Fire:** Press and hold **FIRE** (or hold **Spacebar** on desktop) to deliver radiation and shrink the tumor.
3. **Protect Brain Health:** Fewer beams require longer exposure times, and dropping below **192 beams** causes brain health to decline much faster.
4. **Win Condition:** Bring **Tumor Health** down to **0%** while keeping **Brain Health** above **0%**.

## Real-World Physics Concept
Stereotactic radiosurgery systems like the Gamma Knife focus many low-intensity beams onto a single target point. Each individual beam passes through healthy tissue with relatively low dose, while their convergence at the tumor delivers a high, concentrated therapeutic dose.

## Built With
- HTML5, CSS3, and SVG
- Vanilla JavaScript
