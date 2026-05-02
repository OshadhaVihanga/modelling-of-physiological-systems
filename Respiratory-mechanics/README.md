# Simulation of Respiratory Mechanics

This project presents a computational simulation of respiratory system mechanics using a MATLAB Simulink model. It analyzes how lung compliance and airway resistance affect breathing patterns under normal and diseased conditions.

---

## 📘 Course Information

**BM2102 – Modelling and Analysis of Physiological Systems**
University of Moratuwa

---

## 📌 Objective

* Model the respiratory system using a two-compartment approach
* Simulate breathing under different physiological conditions
* Analyze the effects of compliance and resistance on ventilation
* Compare minute ventilation across conditions

---

## 🧠 Background

Breathing is a mechanical process governed by two key properties:

* **Compliance (C):** Ability of lungs and chest wall to expand
* **Resistance (R):** Opposition to airflow in airways

Diseases alter these properties:

* **Restrictive diseases (e.g., fibrosis):** ↓ Compliance → stiff lungs
* **Obstructive diseases (e.g., asthma):** ↑ Resistance → airflow limitation

A pressure-controlled ventilator is used in the model to simulate breathing cycles. 

---

## ⚙️ Model Description

The system includes:

### 🔹 Physiological Parameters

* Lung compliance (CL)
* Thoracic compliance (Cth)
* Central airway resistance (Rc)
* Peripheral airway resistance (Rp)
* Airway tissue compliance (Caw)

### 🔹 Ventilator Parameters

* Breathing frequency
* Peak inspiratory pressure (PIP)
* Positive end-expiratory pressure (PEEP)
* Inspiratory-to-expiratory ratio (I:E)

---

## 🧪 Simulation Cases

Three physiological conditions were simulated:

### 🟢 Normal Condition

* Balanced compliance and resistance
* Smooth breathing waveform
* Minute ventilation ≈ **7.80 L/min** 

---

### 🔴 Restrictive Condition (Fibrosis)

* Reduced lung compliance
* Lower lung expansion (low tidal volume)
* Increased breathing rate (compensation)
* Minute ventilation ≈ **11.45 L/min** 

---

### 🔵 Obstructive Condition (Asthma)

* Increased airway resistance
* Slower exhalation and air trapping
* Near-normal ventilation with altered airflow
* Minute ventilation ≈ **7.94 L/min** 

---

## 📊 Key Equation

Minute ventilation is defined as:

$$
\dot{V}_E = \text{Respiratory Rate} \times \text{Tidal Volume}
$$

---

## 📈 Key Observations

* Normal lungs show efficient and stable breathing patterns
* Restrictive conditions:

  * Reduced tidal volume
  * Rapid shallow breathing
  * Higher total ventilation but lower efficiency
* Obstructive conditions:

  * Prolonged exhalation
  * Air trapping
  * Near-normal ventilation but reduced effectiveness

---

## 📁 Files

* `report.pdf` – Full report with model details and simulation results
* `simulink_model.slx` *(optional)* – Simulink model
* `plots/` *(optional)* – Simulation graphs

---

## ▶️ How to Run

1. Open MATLAB
2. Load the Simulink model
3. Adjust parameters if needed
4. Run simulation and observe waveforms

---

## 🎯 Conclusion

The simulation highlights how different respiratory disorders affect lung mechanics:

* **Restrictive diseases** limit lung expansion
* **Obstructive diseases** limit airflow

These two conditions produce distinctly different breathing patterns, even under identical ventilator settings.

---

## 👤 Author

K.W.A.O.V Perera
Department of Electronic & Telecommunication Engineering
University of Moratuwa
