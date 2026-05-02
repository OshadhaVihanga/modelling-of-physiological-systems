# Analysis of Cardiac Physiology - CircAdapt Simulation

This project involves the computational modeling and analysis of cardiac hemodynamics using the **CircAdapt Simulation software (v1.1.0)**. The study covers normal sinus rhythm and the physiological impact of aortic valve stenosis.

---

## 🛠️ Project Overview
The simulation analyzes the relationship between pressure, volume, and flow within the left heart chambers. Key focuses include:
* [cite_start]**Wiggers Diagram Integration:** Comparing simulated pressure signals (Aorta, Left Atrium, Left Ventricle) with classical physiological models[cite: 4, 15].
* [cite_start]**Pressure-Volume (PV) Loops:** Mapping the four phases of the cardiac cycle[cite: 41, 42].
* [cite_start]**Valvular Hemodynamics:** Analyzing flow velocities through the Mitral and Aortic valves, specifically the E-wave and A-wave patterns[cite: 48, 52].
* [cite_start]**Pathology Modeling:** Simulating an 80% Aortic Valve Stenosis (AS) and calculating pressure drops using the simplified Bernoulli equation[cite: 66, 75].

---

## 📂 Exercise 1: Normal Sinus Rhythm
### 1. Pressure-Volume Relation
The PV loop is analyzed across four distinct phases:
* [cite_start]**Phase A:** Filling [cite: 42]
* [cite_start]**Phase B:** Isovolumic Contraction [cite: 42]
* [cite_start]**Phase C:** Ejection [cite: 42]
* [cite_start]**Phase D:** Isovolumic Relaxation [cite: 42]

### 2. Valvular Function
* **Mitral Valve:** Opens when $P_{atrium} > P_{ventricle}$. [cite_start]Characterized by an early passive filling phase (**E-wave**) and a late active phase (**A-wave**) from atrial contraction[cite: 17, 48].
* [cite_start]**Aortic Valve:** Opens when $P_{ventricle} > P_{aorta}$ during the ejection phase[cite: 18].

---

## 📂 Exercise 2: Aortic Valve Stenosis (AS)
[cite_start]This section evaluates the hemodynamic shifts when the aortic valve opening area is reduced from the normal 4 $cm^2$[cite: 61, 62].

### Key Calculations:
* [cite_start]**Simplified Bernoulli Equation:** Used to estimate maximal pressure drop across the stenotic valve[cite: 75, 77]:
  $$\Delta p \approx 4v^2$$
* [cite_start]**Work Assessment:** External pump work is estimated by calculating the area enclosed by the PV loop[cite: 80, 82].
* [cite_start]**Clinical Significance:** Evaluation of "critical" stenosis (>75% reduction) and its effect on myocardial adaptation (hypertrophy)[cite: 64, 83].

---

## 🚀 How to Run the Simulation
1. [cite_start]Download the **CircAdapt Simulator** from [circadapt.org](http://www.circadapt.org/downloads/files)[cite: 5].
2. Load the `REFERENCE` simulation state.
3. [cite_start]Right-click the Pressure-Time graph to select `aorta`, `left_atrium`, and `left_ventricle`[cite: 9].
4. [cite_start]Adjust the "Valves" tab to simulate different percentages of stenosis[cite: 66].
