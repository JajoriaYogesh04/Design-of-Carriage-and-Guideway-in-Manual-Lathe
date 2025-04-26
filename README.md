# 🛠️ Lathe Carriage, Guideways & Lead Screw Structural Design and Simulation

**Mentor:** Dr. Hirshikesh, IIT Jodhpur  
**Contributors:** Yogesh (B22ME073), Sonal (B22ME062)

---

## 📌 Project Overview

This project focuses on the **design, structural analysis, and simulation of a manual lathe machine’s carriage, guideways, and lead screw system** — core components responsible for precise tool positioning during machining.  

Our goal was to understand how these elements behave under actual machining forces (cutting forces, weight, reaction moments) and ensure that they meet safety and functional standards through both analytical and simulation-based validations.

This included:
- Deriving load equilibrium conditions  
- Calculating contact and axial forces  
- Assessing stress concentration at guideway junctions  
- Designing a lead screw resistant to both torsional and buckling failure  
- Validating the entire system using SolidWorks static and buckling simulations  
- Cross-verifying calculations with custom MATLAB scripts  

---

## 📐 Why This Matters

In any lathe machine, ensuring the **carriage and lead screw assembly can withstand cutting loads without excessive deformation or buckling is essential** for precision and operator safety. 

This project replicates real-world design decision-making — combining material selection, dimensioning, stress analysis, and simulation — reflecting practical mechanical engineering challenges.

---

## 📊 Project Breakdown

### 🔧 Components Designed & Analyzed
- **Carriage**: Supports tool post, compound rest, and cross-slide; designed for optimal stiffness.
- **Guideways**: Ensures smooth, accurate carriage motion while withstanding reaction and cutting forces.
- **Lead Screw**: Transmits motion to the carriage; designed for torsional and buckling resistance.
- **Lathe Bed, Tool Holder, Cutting Tool**: Modeled for completeness and load distribution accuracy.

---

## 📏 Key Design Parameters

| Parameter         | Value / Range |
|:-----------------|:---------------|
| Carriage weight    | 2000 N         |
| Cutting forces (Fx, Fy, Fz) | (500 N, 800 N, 4000 N) |
| Bed length         | 0.76 m         |
| Lead screw lead    | 3.175 mm       |
| Contact angle      | 45°            |
| Friction coefficient | 0.1          |

---

## 📝 What We Did

✔️ Developed 3D models for the carriage, guideways, lead screw, and associated parts in **SolidWorks**  
✔️ Derived force equilibrium relations to compute contact forces at guideways (F1, F2, F3)  
✔️ Analyzed notch stresses and stress concentration factors at the V-guide junction  
✔️ Designed lead screw dimensions based on:
- Torsional strength (from cutting forces and torque requirement)
- Buckling resistance (using Euler’s theory with fixed–fixed end conditions)
✔️ Wrote custom **MATLAB scripts** to compute analytical values for:
- Normal forces  
- Lead screw safe diameters under torsion and buckling  
- Factor of safety for each component  
✔️ Ran **SolidWorks simulations** for:
- Static stress analysis  
- Buckling analysis of the lead screw under axial loads  

---

## 📐 Materials Used and Why

| Component       | Material            | Why We Chose It |
|:----------------|:-------------------|:----------------------------------------------------------|
| Lathe Bed        | FG200 (Grey Cast Iron) | Great vibration damping and compressive strength |
| Carriage & Guideways | FG260 (High-Grade Cast Iron) | Higher hardness, wear resistance, and sliding properties |
| Lead Screw       | ANSI 1045 (Medium Carbon Steel) | Good tensile strength and machinability |
| Tool Holder      | Cast Alloy Steel     | High toughness and wear resistance under cutting loads |
| Cutting Tool     | HSS (High-Speed Steel) | Retains hardness at elevated temperatures |

---

## 📊 Simulation Highlights  

- **Static analysis** verified that stresses remain within allowable limits under operational loads.
- **Buckling analysis** confirmed the selected lead screw diameter is safe against axial compression.
- Maximum observed deflection and stress values from simulation matched analytical predictions closely.

---

## 📊 Final Design Outcome  

- **Lead screw safe diameter**:
  - Torsion: 7.7 mm  
  - Buckling: 15 mm  
  - Final chosen: 20 mm (with safety factor)  
- **Guideway-contact normal forces** computed for cutting and reaction conditions  
- **Carriage structure verified for both static and dynamic stability**

---

## 📚 Tools & Technologies

- 📐 SolidWorks (3D Modeling, Static & Buckling Simulation)
- 📊 MATLAB (Analytical Calculations, Design Verification)
- 📝 Structural Mechanics, Machine Design Principles

---

## 📸 Project Gallery  

> 📌 Add images/screenshots of your models and simulation results here  

- `/images/lathe_assembly.png`
- `/images/carriage_design.png`
- `/images/leadscrew_analysis.png`
- `/images/static_simulation.png`
- `/images/buckling_simulation.png`
- `/images/matlab_force_calc.png`

---

## 🚀 Future Work  

- Extend design for CNC automation integration  
- Perform full dynamic FEA under real cutting cycles  
- Optimize material selection based on cost-performance trade-offs  
- Develop a digital twin prototype of the entire lathe assembly  

---

## 📞 Contact  

For queries, ideas, or collaboration:
- Yogesh (B22ME073)  
- Sonal (B22ME062)  
- Or open an issue on this repository.

---

