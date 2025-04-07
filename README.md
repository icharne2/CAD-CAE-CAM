# CAD-CAE-CAM
This repository contains basic model files and simulation results created using CAD, CAE, and CAM software.
Files in Solidworks:
- `heat_cooling_simulation_solidworks` -> This file contains a 3D model used for simulating heat exchange during the cooling process of hot-rolled coils in SolidWorks. The geometry consists of multiple layered coils created with linear patterning and includes reference axes for thermal analysis. The model is prepared for transient thermal simulation with appropriate material properties, boundary conditions, and mesh settings
- `Thermal Cooling Simulation of Stainless Steel Cuboids` -> This project includes a thermal simulation study of two stainless steel cuboids (dimensions 20x50x50 mm) conducted in a transient thermal environment.  
The simulation analyzes the cooling behavior of both blocks under defined boundary conditions, with heat exchange occurring on all surfaces.  
Two model variants were prepared to examine the influence of spacing (10 mm and 100 mm) between the cuboids on final temperature distributions.  
The results include maximum and minimum temperatures at 6000 s and differences between both setups.

Simulation Details:
- Material: AISI 304 (isotropic)
- Initial temperature: 900 °C
- Environment temperature: 50 °C
- Convection coefficient: α = 7 W/(m²K)
- Emissivity: 0.95
- Configuration factor: 1
- Mesh size: 5 mm
- Time step: 500 s
- Total simulation time: 3000 s
- Solver: Intel Direct Sparse

The final files include:
- `thermal examination_part2.SLDPRT` -> 100mm
- `thermal examination_part1.SLDPRT` -> 10m
