Code from Portfolio 2 where I had to: 
- Simulate the trajectory of a ball with the parameters launch position (especially the height
above an imaginary ground), launch speed and launch angle of the ball.
- Simulate the observation of the ball position (x, y as shown in the slides). The estimated
ball position shall be subject to uncertainty and it shall be possible to parameterize this
uncertainty. In addition, the time span between two observations shall be variable and the
observations shall be able to drop out completely over a certain period of time.
- The initial parameters of the Kalman Filter shall be adaptable.
- The normally distributed noise on transition and observation should be adjustable. This means
that the covariance matrices R and Q shall be set as a parameter in the Kalman Filter.

- The task of your Particle Filter is to estimate the positions and velocity vectors of two balls flying simultaneously only from the observed erroneous positions over time. 
- Your implementation shall be flexible in the sense that it can handle variations similar to the ones from Task P2.1
