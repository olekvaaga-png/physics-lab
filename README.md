# Physics lab

An interactive laboratory for quantum mechanics, quantum fields and the ideas behind string theory. Every view is a live simulation or a calculated graph that you can change with sliders and buttons, with a plain-language explanation of what you see and what each change means.

**Open the lab:** https://olekvaaga-png.github.io/physics-lab/

The whole lab is one self-contained file, [`index.html`](index.html). It needs no installation, no server and no internet connection: download the file and open it in any modern browser (Chrome, Edge, Firefox or Safari), on a computer or a phone.

*På norsk:* Labben er én HTML-fil. Åpne lenken over, eller last ned `index.html` og åpne den i en nettleser. Forklaringspanelet til venstre er på norsk som standard og kan byttes til engelsk.

## How to use it

1. Pick a view in the list on the left.
2. Change the model with the parameters on the right. Presets under the list set up instructive starting points.
3. Read the **explanation panel** next to the list. It says what is happening right now, what the setting you just changed does, what the view shows, how it compares with something familiar from engineering, and what it means in the real world. It is in Norwegian by default, with a button for English, and can be hidden. On narrow screens it opens from the **Explanation** tab on the left edge.
4. Under the picture, **What happens here** gives a fuller explanation and says whether the view is calculated or only illustrated.
5. The clock under the picture shows simulation time. Use pause, reset and the speed slider to control it. In 3D views, drag to rotate and scroll or pinch to zoom.

## What is in it

### String theory and extra dimensions

| View | What it shows |
| --- | --- |
| Dimension Explorer | A cube in 0 to 9 dimensions, rotated in any plane (including a true double rotation in 4D) and projected into 3D. |
| Calabi–Yau Geometry | A 2D slice of the Fermat quintic, a six-dimensional Calabi–Yau space, plus a point sample of the whole space. The viewing angle and the slice can move over time; the shape itself does not. |
| String Vibration Lab | A classical string with fixed ends or a closed loop, built from up to eight harmonics. |
| Classical Closed Ring | Small waves on a supported ring, and the exact collapse of a free relativistic circular string, with its worldsheet. |
| Compactification Explorer | Momentum and winding on a curled-up circle, and T-duality (R ↔ 1/R, n ↔ w). |

### Quantum mechanics

| View | What it shows |
| --- | --- |
| Quantum superposition | Two states of a harmonic trap mixed together, so the probability density sloshes. |
| Wave packets | A free Gaussian packet that moves and spreads (the uncertainty principle). |
| Measurement and collapse | Single photons through polarizing filters, a double slit built up photon by photon (with and without a which-path detector), and a position measurement that collapses a wavefunction in a box. Includes a fun fact on Roger Penrose's idea that collapse is linked to gravity and consciousness. |
| Two-path interference | Fringes from two paths and how a phase shift moves them. |
| Quantum tunneling | Transmission through a barrier for every energy. |
| Two-level dynamics | Rabi oscillations of a driven two-level system, on and off resonance. |

### Atoms and matter

| View | What it shows |
| --- | --- |
| Hydrogen orbitals and spectrum | Exact hydrogen-like orbitals for any n, l, m and Z as a 3D cloud or a 2D slice, energy levels, and the emitted spectral lines. |
| Crystal energy bands | A two-band model showing metals, semiconductors and insulators. |

### Oscillators and fields

| View | What it shows |
| --- | --- |
| Nonlinear oscillations | A mass in a potential with a quartic term; the period changes with amplitude. |
| Coupled modes | Two coupled oscillators exchanging energy through their eigenmodes. |
| Quantum field modes | The amplitude distribution of one field mode holding N quanta. |
| Mass and dispersion | ω² = k² + m²: mass as the lowest frequency of a field. |
| Statistics and vacuum | Bosons, fermions, zero-point energy and the Casimir pressure. |
| Thermal occupation | How many quanta a mode holds at a given temperature (Bose–Einstein). |
| Energy and frequency | Converts energy to frequency, mass and wavelength with exact SI constants. |
| Origins of mass | Mass from the coupling to the Higgs field. |

### The big picture

| View | What it shows |
| --- | --- |
| Planck to universe | Lengths on a logarithmic scale, from the Planck length to the observable universe. |
| Evidence and theory | Which claims are tested by experiment, which are derived mathematically, and which are not yet tested. |

## Calculated or illustrated?

Most views compute their pictures from the equations they show (for example the hydrogen orbitals, tunneling, Rabi oscillations, the free circular string and the polarizer and double-slit statistics). Some are illustrations of an idea and say so in **What happens here**, for example the band model, which is a dimensionless toy model. The string-theory views show the mathematics of strings and extra dimensions; none of it has been confirmed by experiment, and the lab says this where it matters.

## Sources

The views link their sources in the right panel. Among them: David Tong's lecture notes on quantum mechanics, quantum field theory and string theory; CERN on the Higgs boson and extra dimensions; NIST for physical constants; OpenStax University Physics; and A. J. Hanson's construction of Calabi–Yau sections.

## Licence

MIT, see [LICENSE](LICENSE).
