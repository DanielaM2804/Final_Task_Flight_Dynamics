# Final Task — Aircraft Model (RCAM)
**Flight Dynamics | Universidad Pontificia Bolivariana**

## Authors
- Daniela Miranda Paniagua — 000307885
- Alejandro Pimienta — 000393723
- David Alejandro Díaz — 000448052

## Description
Nonlinear simulation of the Research Civil Aircraft Model (RCAM)
including baseline flight, aileron pulse, engine failure, and
PSO trim optimization for single-engine flight at 78 m/s.

## Files
| File | Description |
|------|-------------|
| `rcam_model.py` | RCAM nonlinear model — xdot function (10 steps) |
| `simulate_p2_3_4A.py` | Simulations 2, 3, and 4 with RK4 integration |
| `simulate_p4B_pso.py` | PSO trim optimization (single engine, 78 m/s NE) |

## How to run

### Install dependencies
pip install numpy matplotlib

### Run simulations
# Change SIMULATION_TO_RUN to 2, 3, or 4
python simulate_p2_3_4A.py

### Run PSO optimization
python simulate_p4B_pso.py

## Requirements
- Python 3.8+
- numpy
- matplotlib
