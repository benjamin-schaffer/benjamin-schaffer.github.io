# Lightweight Biking Wrench Design  
*MIE 313 – Mechanical Design | University of Massachusetts Amherst Fa25*

---

## Project Overview
This project involved the **design, analysis, and validation of a lightweight biking wrench** capable of supporting **250 in-lb of torque** on a ¼-20 bolt and withstanding a **50 N three-point bending test** **without plastic deformation**.

The design was completed under strict **material, size, and weight constraints**, emphasizing **structural efficiency, manufacturability, and real-world performance** rather than cost optimization.

---

## Problem Statement
Design a **lightweight aluminum biking wrench** that:
- Supports **250 in-lb torque** on a ¼-20 bolt  
- Passes a **50 N three-point bending test**  
- Exhibits **no plastic deformation**  
- Fits within **1.25” × 0.25” × 8” aluminum bar stock**  
- Achieves a **target mass of 1.15 oz (32.6 g)**  

---

## Design Constraints

### Material
- Aluminum 6061  
- Yield strength: ~270 MPa  
- Young’s modulus: ~69 GPa  
- Poisson’s ratio: 0.33  

### Size
- Maximum bar stock: **1.25” × 0.25” × 8”**

### Weight
- Target: **1.15 oz (32.6 g)**  
- Final mass: **31.9 g**

---

## Final Design
The final design features:
- **Closed wrench head** for improved torque resistance  
- **I-beam handle geometry** to maximize stiffness-to-weight ratio  
- **Integrated bike tire removal feature**  
- Fully **machinable external geometry**

### Key Dimensions
- Max length: **6.55”**  
- Max width: **1.00”**  
- Max thickness: **0.21”**

---

## Design Evolution
An initial open-head wrench concept was evaluated but rejected due to:
- Excessive mass  
- Reduced strength from open geometry  
- Poor manufacturability due to rounded external profiles  

Iterative refinement led to the **closed-head I-beam design**, balancing **strength, weight, and manufacturability**.

---

## Engineering Analysis

### By-Hand Analysis
Euler–Bernoulli beam theory was used to evaluate:
- Torque loading  
- Combined torque + bending  
- Pure bending  

**Results**
- Max bending stress (torque): **165 MPa**  
- Combined loading stress: **166 MPa**  
- Bending test stress: **18.6 MPa**  

All calculated stresses remained below yield limits.

---

### Finite Element Analysis (FEA)
FEA validated analytical results and informed geometry refinement.

| Load Case | Max Von Mises Stress |
|---------|---------------------|
| Bending | 26 MPa |
| Torque | 45 MPa |
| Combined | 73 MPa |

**Result:**  
Safety factor **> 3.5** across all load cases.

---

## Physical Testing & Results
- **Bending test:** Passed with non-permanent deformation  
- **Torque test:** Failure occurred via **jaw stripping**, caused by aluminum-steel contact and clearance effects  

This revealed real-world interface behavior not captured in idealized models and highlighted the importance of **contact mechanics and tolerancing**.

---

## Key Learnings
- Structural efficiency through **geometry optimization** significantly reduces mass  
- Closed-loop geometries outperform open designs under torque  
- **Manufacturability must be considered early** in the design process  
- Physical testing reveals failure modes beyond analytical assumptions  

---

## Tools & Skills Used
- SolidWorks (CAD & Simulation)  
- Finite Element Analysis (FEA)  
- By-hand stress calculations  
- Manufacturing feasibility analysis  
- Engineering documentation & reporting  

---

## Supporting Documentation
- 📄 **Final Project Report (PDF)**  
- 📊 **Poster Presentation (PDF)**  

*(Linked as downloadable PDFs)*

---

## Reflections
This project closely mirrored a real-world mechanical design workflow — from concept generation and trade studies to simulation, fabrication considerations, and physical testing. It reinforced the importance of **designing for both analysis and reality**, particularly when working with constrained materials and real interfaces.
