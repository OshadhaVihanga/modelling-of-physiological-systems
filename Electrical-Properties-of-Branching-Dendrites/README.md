# Electrical Properties of Branching Dendrites

This project analyzes the steady-state electrical behavior of a branched dendritic structure using cable theory. The study models how voltage propagates through a neuron’s dendritic tree and examines the effects of boundary conditions and branch properties.

---

## 📘 Course Information

**BM2102 – Modelling and Analysis of Physiological Systems**
University of Moratuwa

---

## 📌 Objective

* Model a first-order branched dendrite (one parent branch splitting into two daughter branches)
* Derive the governing equations using cable theory
* Solve the system using matrix methods
* Analyze voltage distribution under different boundary conditions

---

## 🧠 Background

Dendrites are tree-like structures of neurons that receive electrical signals. By modelling each branch as an electrical cable, we can describe how membrane voltage varies spatially.

The steady-state cable equation leads to solutions of the form:

[
V(x) = A e^{-x} + B e^{x}
]

These equations are applied to each branch with appropriate continuity and boundary conditions.

---

## ⚙️ Methodology

1. **Mathematical Modelling**

   * Derived equations for each branch
   * Applied nodal and boundary conditions

2. **Matrix Formulation**

   * Converted system into:
     [
     Ax = b
     ]

3. **Numerical Solution**

   * Solved using MATLAB

4. **Visualization**

   * Plotted voltage profiles for each branch

---

## 📊 Results Summary

* Voltage decays exponentially along dendrites
* Coefficients of growing exponential terms are nearly zero → stable decay
* Daughter branches show identical voltage profiles when:

  * Same electrotonic length
  * Same boundary conditions

---

## 🔬 Boundary Conditions Studied

* **Case (a):** One sealed end, one killed end
* **Case (b):** Both daughter branches sealed
* **Case (c):** Current injected at one daughter branch
* **Case (d):** Current injected at both daughter branches

Each condition significantly changes voltage distribution.

---

## 📈 Key Observations

* Sealed ends prevent current flow → voltage does not drop to zero
* Killed ends act as sinks → voltage drops sharply
* Current injection causes positive voltage gradients
* Identical branch conditions → identical voltage behavior

---

## 🔁 Rall’s Branching Rule

When daughter branch diameters are equal and satisfy Rall’s condition:

* The branch point becomes electrically “invisible”
* The system behaves like a single continuous cable

---

## 📁 Files

* `report.pdf` – Full derivation, MATLAB code, and results
* `code.m` *(optional)* – MATLAB implementation
* `plots/` *(optional)* – Generated graphs

---

## ▶️ How to Run (MATLAB)

1. Open MATLAB
2. Run the provided script
3. View voltage profile plots

---

## 👤 Author

K.W.A.O.V Perera
Department of Electronic & Telecommunication Engineering
University of Moratuwa

