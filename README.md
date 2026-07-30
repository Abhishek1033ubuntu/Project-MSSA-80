# Project MSSA-80: Mid-Size Supersonic Commercial Airliner

[![Python: 3.8+](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21529549.svg)](https://doi.org/10.5281/zenodo.21529549) ![Status](https://img.shields.io/badge/Status-Research_POC-orange) ![Type](https://img.shields.io/badge/Type-Simulation_Model-blue)
---
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

# Important Notice

This repository contains code published for demonstration and testing purposes only. 
The underlying intellectual property (IP) — including inventions, processes, methods, 
algorithms, and research results — is proprietary and protected under Indian law and 
international treaties (Berne Convention, Paris Convention, TRIPS Agreement).

By accessing this repository, you agree:
- The code may be viewed and studied for non-commercial, educational, or research use only.
- Any reproduction, modification, distribution, or commercialization of the IP is strictly prohibited.
- Enforcement of rights will be pursued under Indian jurisdiction and applicable international treaties.

For licensing inquiries or commercial permissions, please contact:
Abhishek Singh  | UIDAI: 9414 9122 9013
Email: abhishek1033@gmail.com | abhishek.s@live.in
Location: Madhya Pradesh, India
