# AeroSim ✈️
### A beginner-friendly aircraft aerodynamics simulator

AeroSim is an interactive web project that helps students explore the basic forces behind flight. Change airspeed, wing area, air density and angle of attack, then watch estimated lift, drag and aerodynamic values update instantly.

**No Python, Node.js or external libraries are required.** AeroSim runs in a modern web browser.

## Open the simulator

- **PC / laptop:** download this repository, extract it, and open `index.html` in Chrome, Edge or Firefox.
- **Android:** download and extract the repository, then open `index.html` using a code editor with HTML preview, such as Acode.
- **Step-by-step setup:** read [PHONE_AND_PC_TUTORIAL.md](PHONE_AND_PC_TUTORIAL.md).

## What can you experiment with?

| Input | Available range |
|---|---:|
| Airspeed | 20–250 m/s |
| Wing reference area | 5–80 m² |
| Air density | 0.5–1.225 kg/m³ |
| Angle of attack | -5° to 22° |

The simulator displays lift force, drag force, lift coefficient, drag coefficient, lift-to-drag ratio, dynamic pressure and a graph of lift coefficient against angle of attack.

## Project files

```text
Aerosim-for-students-/
├── index.html
├── style.css
├── app.js
├── README.md
└── PHONE_AND_PC_TUTORIAL.md
```

| File | Purpose |
|---|---|
| `index.html` | Webpage structure, controls and result panels |
| `style.css` | Colours, layout and responsive design |
| `app.js` | Aerodynamic calculations and graph |
| `README.md` | Project introduction |
| `PHONE_AND_PC_TUTORIAL.md` | Phone and computer setup guide |

Keep `index.html`, `style.css` and `app.js` together in the same folder.

## The physics behind AeroSim

Dynamic pressure: `q = ½ρv²`

Lift: `L = ½ρv²SCₗ = qSCₗ`

Drag: `D = ½ρv²SCᵈ = qSCᵈ`

Where ρ is air density, v is airspeed, S is wing reference area, Cₗ is lift coefficient and Cᵈ is drag coefficient.

The current illustrative model uses a simple lift-coefficient curve that peaks around a chosen stall angle, then decreases. Drag is estimated using:

`Cᵈ = 0.025 + 0.045Cₗ²`

## Important limitations

This is a **simplified educational model**, not a CFD solver or a validated model of a real aircraft or airfoil. It does not fully model Reynolds-number effects, compressibility, real airfoil geometry, aircraft stability or control. Its output must not be used for aircraft design, flight planning, operation or safety decisions.

## Roadmap

- [x] Live lift and drag calculations
- [x] Adjustable flight conditions
- [x] Lift coefficient vs angle-of-attack graph
- [x] Responsive phone and computer layout
- [x] Setup documentation
- [ ] Compare multiple airfoil models
- [ ] Add a drag polar chart
- [ ] Add more carefully validated aerodynamic models

## Built to learn

This project is a starting point for learning web development, physics and aerodynamics. Explore the code, change one thing at a time, and compare what the model predicts.

**Project:** AeroSim · **Version:** 1.0 · **Type:** Educational web simulator
