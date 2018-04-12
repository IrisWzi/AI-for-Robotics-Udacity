# AI-for-Robotics-Udacity
Some of the codes from the Udacity course Artificial Intelligence for Robotics

## Notes:

### Filter
#### Comparing the three filters
|	                  |State         |Space	        |Belief	       |Efficiency	In Robotics|
|:------------------|:-------------|:-------------|:-------------|:------------------------|
|Histogram Filter	  |Discrete	     |Multi-model	  |Exponential	 |Approximate|
|Kalman Filter	    |Continuous	   |Uni-model	    |Quadratic	   |Approximate|
|Particle Filter	  |Continuous	   |Multi-model	  |              |Approximate|

#### Particle filter: 
  easy to implement, complexity scales exponentially with number of dimensions
#### Kalman filter: 
  the only filter that scales exponentially

### Search
|                    |Continuous  |Optimal     |Universal   |Local       |
|:-------------------|:----------:|:----------:|:----------:|:----------:|
|BFS                 |            |X           |            |            |
|A*                  |            |X           |            |            |
|Dynamic Programming |            |X           |X           |            |
|Smoothing           |X           |            |            |X           |

### PID
Proportional - minimize error
Integral     - compensate drift
Derivative   - avoid overshoot
