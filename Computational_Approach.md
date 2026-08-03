## Computational Fluid Dynamics (CFD)

Computational Fluid Dynamics (CFD) is a numerical technique used to analyze fluid flow by solving the governing equations of fluid motion over a discretized computational domain. In cardiovascular engineering, CFD provides a non-invasive method for investigating blood flow within arteries, enabling detailed visualization of hemodynamic parameters such as velocity, pressure, wall shear stress (WSS), and flow streamlines.

In this project, ANSYS Fluent is used to simulate blood flow through a coronary artery bifurcation. The artery geometry is divided into a finite number of small control volumes (mesh elements), and the governing equations are solved iteratively at each element until a converged solution is obtained. The resulting flow field provides valuable insight into regions of disturbed flow, recirculation, and abnormal shear stress, which are closely associated with the development of atherosclerosis.

## Governing Equations

The motion of blood within the coronary artery is governed by the principles of conservation of mass and conservation of momentum.

Continuity Equation (Conservation of Mass)

For an incompressible fluid,

$$ ∇⋅V=0 $$

where:

V = velocity vector (m/s)

This equation ensures that mass is conserved throughout the computational domain.

Navier–Stokes Equation (Conservation of Momentum)

For incompressible Newtonian flow,

$$ \rho \left( \frac{\partial \mathbf{V}}{\partial t} + (\mathbf{V} \cdot \nabla)\mathbf{V} \right) = -\nabla p + \mu \nabla^2 \mathbf{V} + \mathbf{F} $$

where:
- ρ = fluid density (kg/m³)
- V = velocity vector (m/s)
- p = pressure (Pa)
- μ = dynamic viscosity (Pa·s)
- F = body force per unit volume

The continuity and Navier–Stokes equations are solved simultaneously to determine the pressure and velocity fields throughout the artery.

## Assumptions
To simplify the computational model while maintaining acceptable accuracy, the following assumptions are made:

- Blood is treated as an incompressible fluid.
- Blood is assumed to behave as a Newtonian fluid, which is a valid approximation for large coronary arteries where shear rates are relatively high.
- The flow is assumed to be laminar under normal physiological conditions.
- The arterial walls are considered rigid and stationary, neglecting vessel wall deformation.
- Body forces such as gravity are neglected because their effect is insignificant compared with pressure-driven blood flow.
- Blood properties, including density and viscosity, are assumed to remain constant throughout the simulation.
- The simulation is performed under prescribed inlet and outlet boundary conditions representative of physiological blood flow.
