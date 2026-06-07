# Solar-cell-simulation-SCAPS-1D-
A simulation study if Chalcogenide-based perovskite solar cell using **SCAPS-1D**, exploring how bandgap variation affects solar cell performance.
---
## What is SCAPS-1D?
SCAPS-1D (Solar Cell Capacitance Simulator) is a free simulation software developed at the University of Gent, Belgium. It is widely used to model and analyze thin-film solar cells numerically.

With SCAPS-1D, you can:
- Plot **Quantum Efficiency (QE)** graphs to see how well the cell converts light at different wavelengths
- Generate **J-V curves** and extract key parameter like V<sub>oc</sub> , J, Fill Factor, and Efficiency
- Define **multiple thin-film layers** (absorber, ETL, HTL) with their material properties
- Set **metal contact** (front and back) with custom work functions
- Control **defect density** to study how traps affect recombination and performance
---
## Why Chalcogenide-Based Perovskite?
Chalcogenide-based perovskites are an emerging class of solar cell materials that offer several advantages over conventional halide perovskites:
- **More stable** & better thermal and environmental stability
- **Strong light absorption** hight absorption coefficient across the visible spectrum
- **Good defect tolerance** lead-free or low-lead alternatives
---
## What was done in this study
1. **Device structure was defined** in SCAPS-1D with a Chalcogenide-based perovskite absorber layer, electron and hole transport layers, and metal contacts (front and back).
2. **Defect density** was set in the absorber layer to simulate realistic device conditions.
3. **Bandgap of the absorber was varied** across a range of values to observe how it affects device performance.
4. For each bandgap value, the following were recorded:
   - Open-circuit voltage (V<sub>OC</sub>)
   - Short-circuit current density (J<sub>SC</sub>)
   - Fill Factor (FF)
   - Power Conversion Efficiency
5. **All data was analyzed and plotted** using **Origin software** to produce clean, comparative graphs.
   ---
## Results
### J-V Curve 
<img width="1695" height="1181" alt="image" src="https://github.com/user-attachments/assets/edb21c25-5a80-43c0-8732-b575e23fb861" />

### Temperature vs. Device Parameters (V<sub>OC</sub>,J<sub>SC</sub>, FF, Efficiency)
<img width="762" height="1138" alt="image" src="https://github.com/user-attachments/assets/286c23f5-7ce4-4d3c-84c9-417dc3c3bb42" />
<img width="762" height="1144" alt="image" src="https://github.com/user-attachments/assets/8411f8a0-e94a-41a2-9b8e-c8aeafb81ef7" />
<img width="763" height="1144" alt="image" src="https://github.com/user-attachments/assets/cc61a826-f0a2-4ddf-9088-2ae6f89a37be" />
<img width="819" height="1144" alt="image" src="https://github.com/user-attachments/assets/467a39fe-12be-4461-bacf-f86a01bf531a" />

This graph shows how each performance parameter changes as the temperature varied helping identify the optimal bandgap for maximum efficiency.

---
## Tools Used 
- **SCAPS-1D** Simulation
- **Origin Software** Data analysis and plotting

---
## Author 
**[Arshiya Parveen]**
[Department of Physics, Indira Gandhi National tribal University]
[arshiakhan025@gmail.com]










