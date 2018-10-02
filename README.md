## 2018
### [WAFR 2018, co-first author] Signal Temporal Logic meets Hamilton-Jacobi Reachability: Connections and Applications
The goal of this project is to merge STL with HJ-Reachability such that time-varying objectives of a robot can be achieved while guaranteeing safety. I worked on this project during my Master's degree in the [Stanford Autonomous Systems Laboratory](http://asl.stanford.edu/){:target="_blank"}. You can find the details in the [paper](http://asl.stanford.edu/wp-content/papercite-data/pdf/Chen.Tam.Livingston.Pavone.WAFR18.pdf){:target="_blank"} which was recently accepted to the 2018 Workshop on the Algorithmic Foundations of Robotics. You can also watch the [experiments](https://www.youtube.com/watch?v=SI4bbBVkcgs&t=2s){:target="_blank"} or dive into the deep end with the [code](https://github.com/StanfordASL/stlhj){:target="_blank"}.   
UPDATE: I recently developed an MPC controller that is smoother and more stable than the conventional switching (bang-bang) controller used previously. Check out the performance comparison between the old and new controllers [here](https://www.youtube.com/playlist?list=PLYB3nnEvwz0xpMx2unjJuJz_hrfBOShyh){:target="_blank"}!

### Drift Initiation via Nonlinear Trajectory Optimization
For the AA203: Intro to Optimal Controls course, [John](https://github.com/JohnHaTrick){:target="_blank"} and I applied non-linear optimization techniques for state and control trajectories to initiate the Scandanavian Flick maneuver. We used the bicycle model for the car dynamics and a logit approximation of the piecewise Fiala brush tire model. Skip to the [results](https://youtu.be/JB334BDw6gY){:target="_blank"}, study the [paper](https://github.com/qizhantam/portfolio/blob/master/docs/papers/Alsterda_Tam.pdf){:target="_blank"} for all the details, or read the [code](https://github.com/JohnHaTrick/AA203){:target="_blank"}.

### Autonomous Search and Rescue 
Building upon the [asl_turtlebot](https://github.com/StanfordASL/asl_turtlebot){:target="_blank"} ROS package, my team developed and implemented a [software stack](https://github.com/qizhantam/asl_turtlebot/tree/project){:target="_blank"} of integrated perception and navigation algorithms such as SLAM, TensorFlow and A* on a Turtlebot3 Burger that came with a VLP-16 Velodyne LiDAR puck and a camera to [locate animals in a model city and rescue them](https://youtu.be/3CHbzuHkM34){:target="_blank"}.

### Mechatronics: Autonomous Line-Following Robot 
Designed and built a robot from the ground-up to accomplish tasks such as navigation by [following lines and depositing balls in designated bins](https://youtu.be/KClaUtPyq60){:target="_blank"}. Hardware components include IR-LEDs, phototransistors, DC brush motors, stepper motors, all controlled by a Teensy 3.2 microcontroller with a [state-space algorithm and feedback controller](https://github.com/srharris91/ME210_CowShots){:target="_blank"}.

### Herding Animals through Social Integration of Robots and Leader-Follower Formation Control
I leveraged upon the flocking instinct of herd animals in a [study](https://github.com/qizhantam/portfolio/blob/master/docs/papers/AA277_FinalPaper_QizhanTam.pdf){:target="_blank"} to develop control methods for robots to herd animals using path-following and potential field navigation techniques.

## 2017
### Grid Stability Management and Price Arbitrage for Distributed Energy Storage and Generation via Reinforcement Learning
I developed and implemented a reinforcement learning control policy for distributed batteries in a simulated residential environment using the IEEE 123 feeder model supplied with real user load and modeled solar generation. This was a course project for CS238: Decision Making under Uncertainty. The [paper](https://github.com/qizhantam/CS238_GridStability_ReinforcementLearning/blob/master/CS238_Course_Paper.pdf){:target="_blank"} goes through the details and the code can be found [here](https://github.com/qizhantam/CS238_GridStability_ReinforcementLearning){:target="_blank"}.

### Density Functional Theory Computations for Li-ion Battery Materials (Teaching Material)
I developed this project for the students of ME420. It involved the quantum mechanical calculations of Lithium Cobalt Oxide crystal structures to predict the voltage and volume changes of the crystals during charge cycling. All computations were done using [QuantumEspresso](https://www.quantum-espresso.org/){:target="_blank"} on Stanford's High Performance Computing Cluster. Course material can be found [here](https://github.com/qizhantam/ME420_DensityFunctionalTheory_LiBattery){:target="_blank"}. The closing project discussion slides and the solutions to the assignments are made available upon request.  
2018 Update: Modified for Slurm job scheduler (previously PBS).

### [ASME InterPACK, SystemX Alliance Conference] CFD Modeling and Optimization of Fin Array Packaging Solutions for MicroThermoelectric Generator Devices 
I worked on this project while I was in a research rotation with the Stanford [Nanoheat Lab](https://nanoheat.stanford.edu/){:target="_blank"}. This project was funded and done in collaboration with Analog Devices to study effective fin designs for heat sinks of novel micro-thermoelectric generator devices through analytical and CFD analysis. I presented a [poster](https://github.com/qizhantam/portfolio/blob/master/docs/papers/Interpack2017%20v4.pdf){:target="_blank"} on this project in the 2017 ASME InterPACK conference held in San Francisco and the 2017 SystemX Alliance Conference held in Stanford.

## 2016
### [Nano Letters] Heterogeneity in the Small-Scale Deformation Behavior of Disordered Nanoparticle Packings  
I participated in this project during my time in [Carpick Nanotribology Group](https://carpick.seas.upenn.edu){:target="_blank"}. I studied the mechanical properties of amorphous materials by using an Atomic Force Microscope (AFM) [to perform nanoindentations on nanoparticle packings](https://i.imgur.com/xXeFftD.gif){:target="_blank"}. I found trends using image recognition on MATLAB and gave a group presentation on the new findings. You can find the details in the [paper](https://pubs.acs.org/doi/abs/10.1021/acs.nanolett.5b05319){:target="_blank"}.

### Evaporasun, raising solar panel efficiency through passive cooling.
Evaporasun is the product of my senior design project with 3 other team members. We performed small scale solar panel tests in a controlled environment to evaluate the effects of different cooling methods. After gathering data and developing models, we designed and built a fully passive cooling system through capillary action, finally validating our design and predictive models on a full scale commercial solar panel. We predict a 20<sup>o</sup>C decrease in temperature under simulated peak sun conditions using our passive cooling system and 10% average increase in power output. Visit the [project website](https://tamqizhan.wixsite.com/portfolio/project-evaporasun){:target="_blank"}, or download the [poster](https://github.com/qizhantam/portfolio/blob/master/docs/papers/TransluSun_poster-6-page-001.jpg){:target="_blank"} and [full report](https://github.com/qizhantam/portfolio/blob/master/docs/papers/TransluSun_finalReport.pdf){:target="_blank"}.

## 2015
### String Stability of Independent Autonomous Vehicles
In this project I studied the propagation of instability that arises from autonomous vehicles independent of one another. I simulated and implemented a feedback controller for independent miniature electric vehicles following a lead train at varying velocities and directions based on sensory data from on-board ultrasonic sensors. For more information and a video of the experiment, visit the [project website](https://tamqizhan.wixsite.com/portfolio/project-train-chain){:target="_blank"}.

### Automatic Ball-Balancing
The objective of this project is to balance a ball at different points along an inherently unsteady rail by using computer vision to track the ball’s position and a PID controller to maintain the ball’s position. I modelled the kinetics of the ball based on the rail geometry and used the model to design the PID controller. Visit the [project website](https://tamqizhan.wixsite.com/portfolio/project-ball-balancing-act){:target="_blank"} for videos of the various design configurations.

## 2014
### Machine Design and Manufacturing: Gamma-type Stirling Heat Engine
Using 2.5D CNC mills and lathes, I designed and machined a Gamma-type Stirling Heat Engine from aluminum and steel which ran at over 1000 RPM. Visit the [project website](https://tamqizhan.wixsite.com/portfolio/project-beta-type-stirling-heat-eng){:target="_blank"} for a detailed look at the designs, or skip to the [video](https://www.youtube.com/watch?v=--OT9Ku7soA){:target="_blank"} (I apologize for the low quality video ahead of time.)

### Designing and Testing a New Microcantilever Calibration Device for an Advanced Atomic Force Microscope 
I performed research on the application of the Diamagnetic Lateral Force Calibration on the Ultra High Vacuum 750 AFM by RHK. A central component of the calibration device is a [graphite-mica composite levitating through diamagnetism](https://youtu.be/k_1TMDkXIWw){:target="_blank"}. I designed and machined custom parts using CNC mills and lathes to house the composite sheet securely. The parts were particularly challenging to machine as they have small tolerances and dimensions (~1" in diameter, ~1/4" thick). Unorthodox methods were used in making them. You can see a summary of the project by going over the
[poster](https://github.com/qizhantam/portfolio/blob/master/docs/papers/Qizhan_Poster_7.30-1.jpg){:target="_blank"} or read the full story in the [report](https://github.com/qizhantam/portfolio/blob/master/docs/papers/Littlejohn_report.pdf){:target="_blank"}.

### [Applied Physics Letters] Direct torsional actuation of microcantilevers using magnetic excitation
My first foray into research in [Carpick Nanotribology Group](https://carpick.seas.upenn.edu){:target="_blank"}, I investigated the improvement in data collection from attaching magnetic beads to AFM tips. Details can be found in the [paper](https://aip.scitation.org/doi/citedby/10.1063/1.4894737){:target="_blank"}.


