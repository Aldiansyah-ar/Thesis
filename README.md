# Development of The Finite Difference Method for Vorticity Flow Simulation

## Abstract 
<p style="text-align: justify;">
  The finite difference method is a numerical method to solve partial differential equations. The Forward Time Centered Space (FTCS) is an explicit finite difference method employed to solve parabolic partial differential equations. However, the FTCS scheme has a strict stability condition, requiring a very small time step. To address this limitation, this study integrates the centered difference scheme with fourth-order Runge-Kutta method (RK4), resulting in the RK4-CS scheme. The RK4-CS scheme is applied to simulate vorticity flow in a lid-driven cavity system. Validation is conducted by comparing the flow structures and computing error values using the Mean Absolute Percentage Error (MAPE) with the results from prior studies. The simulation results show that the vorticity flow structures obtained from the RK4-CS scheme are consistent with the results of prior studies. The MAPE values obtained from the RK4-CS scheme with time steps exceeding the stability limit of the FTCS scheme under the laminar and turbulent regimes are 2.3013% and 14.4795%, respectively.
</p>

## Stack
* Python (Numpy)

## Setup
Clone the repository
```bash
git clone https://github.com/Aldiansyah-ar/Thesis
```
Direct to the project directory
```bash
cd Thesis
```
Create the `Python Environment`

```bash
python -m venv venv_name
```
Activate the environment
```bash
venv_name\scripts\activate.bat
```
Install the library in `requirements.txt`
```bash
pip install -r requirements.txt
```

## Acknowledgements
This research was conducted as part of the requirements for the Master of Computational
Science program at Bandung Institute of Technology (ITB), within the Faculty of Mathematics
and Natural Sciences. I would like to express my gratitude to my supervisors, Acep Purqon
and Ikha Magdalena for their supervision, funding, and valuable insights during this research.