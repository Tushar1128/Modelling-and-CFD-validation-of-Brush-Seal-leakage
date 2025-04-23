Brush Seal Leakage: Mathematical Modelling & CFD Validation


This repository presents a comprehensive analysis of brush seal leakage in turbomachinery using both analytical modeling (MATLAB) and CFD validation (ANSYS Workbench). The goal is to evaluate leakage rates, visualize flow behavior, and model the impact of clearance and blow-down effects on performance.

 📂 Repository Contents
| `brush_seal_leak.m` | MATLAB script for mathematical modeling of leakage with and without clearance, including blow-down effect estimation. |
| `honey__dp1.wbpz` | Archived ANSYS Workbench project file containing the CFD setup, mesh, boundary conditions, and results for brush seal leakage simulation. |
| `contour_and_mesh_images/` | Folder containing CFD velocity and pressure contour plots and mesh images for both with and without clearance conditions. |

📈 Project Highlights

- ✅ Analytical mode using Chew’s porosity and Pröstler’s resistance formulas.
- ✅ Mass flow rate calculated using Darcy–Forchheimer equation.
- ✅ Clearance impact and blow-down effect modeled using parametric expressions.
- ✅ CFD validation*with visual comparison of flow behavior.
- ✅ Ready for future extension into optimization studies.

🔬 Technical Overview

1. MATLAB Modelling
- Calculates corrected porosity and flow resistance.
- Solves velocity using Darcy-Forchheimer equation.
- Estimates leakage mass flow rate under:
  - Zero clearance
  - 0.25 mm clearance
  - Clearance with blow-down effect

 2. ANSYS Workbench CFD
- Geometry and mesh created for bristle pack flow domain.
- Pressure-inlet and pressure-outlet BCs applied.
- Simulations run for both contact and non-contact (clearance) cases.
- Mesh independence ensured with refinement near bristles.

3. Visualizations
- CFD contour plots of pressure and velocity.
- Side-by-side comparison of leakage behavior with and without clearance.
- Mesh structure visualized to demonstrate grid quality.

 🛠 Tools Used
- MATLAB – Parametric leakage modeling
- ANSYS Workbench – 2D CFD simulation

🚀 Future Work
- Parametric sweep for various bristle densities and lay angles
- Thermal analysis under high-temperature operation
- Experimental correlation with literature data

📜 License
This project is open-sourced under the MIT License.

 🙌 Acknowledgements
Inspired by foundational work from Chew, Pröstler, and brush seal leakage studies in academic literature.
