# 5-DoF_Feeder-Bot
IMU Kalman Filter

- Developed an accelerometer dynamic model based on initial statistics for estimation of independent system parameters
- Used the model and corrupted GPS measurements of position and velocity to develop a Kalman Filter to estimate conditional mean and variance of a stochastic system
- Analyzed a Monte Carlo simulation to validate the proximity of actual error variance to that computed by the Kalman Filter
- Generated an ensemble of state realizations and estimates, subsequently evaluating orthogonality properties
