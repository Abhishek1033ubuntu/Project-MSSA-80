# Project MSSA-80: Mid-Size Supersonic Commercial Airliner

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python: 3.8+](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Project MSSA-80 is an open-source analytical conceptual design framework for an **80-seat commercial supersonic transport jet** optimized for trans-Atlantic ranges (4,200 nm) cruising at **Mach 1.7**. 

By leveraging **Advanced Composite Materials (ACMs)**, aeroelastic tailoring, and modern non-afterburning Variable-Cycle Engine architecture, this model demonstrates physical and financial feasibility capable of breaking even at **1.2x current international Business Class ticket pricing**.



---

## 🚀 Core Architectural Parameters
* **Capacity:** 80 Seats (1-1 Single-Aisle layout using deep-cradle premium ergonomic recliners).
* **Speed/Range:** Mach 1.7 Cruise Velocity at 55,000–60,000 ft / 4,200 Nautical Miles.
* **Structural Composites:** Carbon Fiber Reinforced Polymers (CFRP) bound with high-temperature Bismaleimide (BMI) matrix resins.
* **Propulsion:** Twin Non-Afterburning Variable-Cycle Engines (Dual high-bypass subsonic / low-bypass turbojet cruise cycles).
* **Mishap-Resilient Fuel System:** Polymer-blended anti-misting Sustainable Aviation Fuel (SAF) paired with inline high-shear mechanical degraders.

---

## 📊 Analytical Simulation Core
The repository contains an analytical simulation script (`mssa_80_simulation.py`) mapping out compressible wave drag, thermal stagnation boundary layer heating, and pressure vessel skin stress cycles across a multi-regime velocity index.

### Running the Verification Model
To set up dependencies and run the core calculation simulation, deploy the following local execution context:

```bash
# Clone the Core Architecture Repository
git clone [https://github.com/Abhishek1033ubuntu/project-mssa-80.git](https://github.com/Abhishek1033ubuntu/project-mssa-80.git)
cd project-mssa-80

# Install Open-Source Computation Stack
pip install -r requirements.txt

# Run Analytical Aero-Thermal Validation Engine
python mssa_80_simulation.py
