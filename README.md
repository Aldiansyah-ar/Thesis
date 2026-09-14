# Development of The Finite Difference Method for Vorticity Flow Simulation 

<p style="text-align: justify;">
  The finite difference method is a numerical method to solve partial differential equations. The Forward Time Centered Space (FTCS) is an explicit finite difference method employed to solve parabolic partial differential equations. However, the FTCS scheme has a strict stability condition, requiring a very small time step. To address this limitation, this study integrates the centered difference scheme with fourth-order Runge-Kutta method (RK4), resulting in the RK4-CS scheme. The RK4-CS scheme is applied to simulate vorticity flow in a lid-driven cavity system. Validation is conducted by comparing the flow structures and computing error values using the Mean Absolute Percentage Error (MAPE) with the results from prior studies. The simulation results show that the vorticity flow structures obtained from the RK4-CS scheme are consistent with the results of prior studies. The MAPE values obtained from the RK4-CS scheme with time steps exceeding the stability limit of the FTCS scheme under the laminar and turbulent regimes are 2.3013% and 14.4795%, respectively.
</p>

## Stack

* Python (Numpy)