# Blood Flow Simulation in a Coronary Artery Bifurcation using ANSYS Fluent

A Computational Fluid Dynamics (CFD) study investigating the hemodynamic behavior of blood flow through a coronary artery bifurcation using **ANSYS Fluent**. The project analyzes velocity, pressure, wall shear stress (WSS), and flow patterns to understand how arterial geometry influences cardiovascular health.

---

## Project Overview

Coronary artery disease is one of the leading causes of cardiovascular mortality worldwide. Areas where coronary arteries branch (bifurcations) are particularly susceptible to plaque formation because blood flow becomes disturbed, creating regions of low wall shear stress and flow recirculation.

This project uses Computational Fluid Dynamics (CFD) to simulate blood flow through an idealized coronary artery bifurcation and visualize important hemodynamic parameters associated with cardiovascular disease.

---

## Objectives

- Simulate blood flow through a coronary artery bifurcation.
- Analyze velocity and pressure distributions.
- Evaluate wall shear stress (WSS).
- Visualize streamlines and flow separation.
- Understand the relationship between blood flow and plaque formation.
- Develop a complete CFD workflow using ANSYS Fluent.

---
### Modeling Assumptions

- Incompressible flow
- Newtonian blood model
- Laminar flow
- Rigid vessel walls
- Constant blood properties
- No-slip wall condition

## Key observations include:

- Flow divides asymmetrically at the bifurcation.
- Pressure decreases continuously from inlet to outlets.
- High wall shear stress occurs near the bifurcation apex.
- Low wall shear stress develops along the outer walls of the daughter branches.
- Small recirculation regions form downstream of the bifurcation.

These observations are consistent with established coronary hemodynamics and explain why arterial bifurcations are common locations for plaque formation.

---

## Software Used

- ANSYS Discovery
- ANSYS Meshing
- ANSYS Fluent
- ANSYS CFD-Post

---

## Future Work

This project can be extended to investigate more advanced cardiovascular scenarios, including:

- Blood flow through stenosed (blocked) arteries
- Blood flow before and after coronary stent implantation
- Drug-eluting stent performance
---

## Repository Structure

```
├── Geometry/
├── Mesh/
├── Simulation_Setup/
├── Results/
│   ├── Streamlines
│   ├── Velocity
│   ├── Pressure
│   └── Wall_Shear_Stress
├── Report/
└── README.md
```

---

## Key Learning Outcomes

- Coronary artery hemodynamics
- Computational Fluid Dynamics (CFD)
- ANSYS Fluent workflow
- Biomedical flow simulation
- Mesh generation for complex geometries
- Interpretation of velocity, pressure, and wall shear stress distributions
- Understanding the relationship between blood flow and cardiovascular disease
