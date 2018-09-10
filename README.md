## Under Construction
![](https://openclipart.org/download/295167/just-bulldozer.svg){:height="30%" width="30%"}  
While I consolidate my stuff onto this page, check out my github repositories [here](https://github.com/qizhantam) and a slightly outdated list of projects [here](https://tamqizhan.wixsite.com/portfolio/).

## 2018
### Signal Temporal Logic meets Hamilton-Jacobi Reachability: Connections and Applications (WAFR 2018, co-first author)
The goal of this project is to merge STL with HJ-Reachability such that time-varying objectives of a robot can be achieved while guaranteeing safety. I worked on this project during my Master's degree in the [Stanford Autonomous Systems Laboratory](http://asl.stanford.edu/). You can find the details in the [paper](http://asl.stanford.edu/wp-content/papercite-data/pdf/Chen.Tam.Livingston.Pavone.WAFR18.pdf) which was recently accepted to the 2018 Workshop on the Algorithmic Foundations of Robotics. You can also watch the [experiments](https://www.youtube.com/watch?v=SI4bbBVkcgs&t=2s) or dive into the deep end with the [code](https://github.com/StanfordASL/stlhj).

### Drift Initiation via Nonlinear Trajectory Optimization
For the AA203: Intro to Optimal Controls course, [John](https://github.com/JohnHaTrick) and I applied non-linear optimization techniques for state and control trajectories to initiate the Scandanavian Flick maneuver. We used the bicycle model for the car dynamics and a logit approximation of the piecewise Fiala brush tire model. Skip to the [results](https://youtu.be/JB334BDw6gY), study the [paper](https://github.com/qizhantam/portfolio/raw/master/docs/papers/Alsterda_Tam.pdf) for all the details, or read the [code](https://github.com/JohnHaTrick/AA203).

### Autonomous Search and Rescue
Using a Velodyne LiDAR puck and other onboard sensors, developed and implemented a software stack of integrated perception and navigation algorithms such as SLAM, TensorFlow and A* on Turtlebot3 Burgers to locate animal pictures in a model city and rescue them.

### Mechatronics: Autonomous Line-Following Robot
Designed and built a robot from the ground-up to accomplish tasks such as navigation by following lines and depositing balls in designated bins. Hardware components include IR-LEDs, phototransistors, DC brush motors, stepper motors, all controlled by a Teensy 3.2 microcontroller with a state-space algorithm and feedback controller.

### Herding Animals through Social Integration of Robots and Leader-Follower Formation Control
The flocking instinct of herd animals was leveraged in a study to develop control methods for robots to herd animals using path-following and potential field navigation techniques.

## 2017
### Grid Stability Management and Price Arbitrage for Distributed Energy Storage and Generation via Reinforcement Learning
Developed and implemented a Reinforcement Learning control policy for distributed batteries in a simulated residential environment using the IEEE 123 feeder model supplied with real user load and modeled solar generation.

### Density Functional Theory Computations for Li-ion Battery Materials
This project involves the quantum mechanical calculation of Lithium Cobalt Oxide crystals to predict the voltage and volume change of the crystals during charge cycling. All computations were done using [QuantumEspresso](https://www.quantum-espresso.org/) on Stanford's High Performance Computing Cluster. I developed this project for the course ME420: Applied Electrochemistry at Micro- and Nanoscale. Course material can be found [here](). The closing project discussion slides and the solutions to the assignments are made available upon request.  
2018 Update: Modified for Slurm job scheduler (previously PBS).
