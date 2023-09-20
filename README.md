# Reinforcement-Learning-for-Active-Structural-Control
This repository contains the python codes of the paper 
  > + Panda, J., Chopra, M., Matsagar, V., & Chakraborty, S. (2023). An iterative gradient descent-based reinforcement learning policy for active control of structural vibrations. Computers & Structures, Accepted, in press. [Article]

# Signal flow diagram of closed loop structure-controller system in PI framework.  
![Proportional-Integral state-output feedback](Figure1.png)

# Detailed flow diagram showing the iterative sequence for policy parameter update.
![Agent–Environment interaction](Figure3.png)

# Files
A short description of the files is provided below for ease of reading.
Folder: QCModel (Continuous time)
  + `RLAlgorithm_QCmodel_P.ipynb`: This code is for RL-based control algorithm in proportional (P) to state feedback case (Case study I: Quarter car model).
  + `RLAlgorithm_QCmodel_PI.ipynb`: This code is for RL-based control algorithm in proportional-integral (PI) to state-output feedback (Case study I: Quarter car model).
Folder: 8Story (Discrete time)
  + `RLAlgorithm_8Story_P.ipynb`: This code is for RL-based control algorithm in proportional (P) to state feedback case (Case study II: 8-story benchmark building).
  + `RLAlgorithm_8Story_PI.ipynb`: This code is for RL-based control algorithm in proportional-integral (PI) to state-output feedback (Case study II: 8-story benchmark building).
  + `Validation_8Story_P&PI.ipynb`: This code is for the robust performance of trained RL controllers in P and PI feedback (Section 5.2.2, Figure 11).
Considered SAC ground motions to validate the robust performance of the trained controllers are placed in the folder '8Story' along with the state-space matrices and updated P and PI controller gains. In case, the location of the mentioned data is changed, the correct path should be given.

