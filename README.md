# PMSM-drives-field-oriented-control-with-Machine-Learning
 A Twin Delayed Deep Deterministic Policy Gradient (TD3) algorithm is used to perform correction signals to inner-control loop (current) of the speed controller. The performance gains are supported by numerical simulations carried out in the MATLAB/Simulink environment by implementing both the suggested agent and a conventional PI controller

Reinforcement learning is employed for the successful completion of a desired task within an uncertain environment. After each sample time, the agent, which, in our model is a Twin-Delayed Deep Deterministic Policy Gradient (TD3) algorithm. Agents are trained on reward basis; a reward is a measure of how successful the preceding action was with respect to the desired goal. Every reinforcement learning agent has two primary components: a policy and an algorithm.


![image](https://github.com/hassanrizwank/PMSM-drives-field-oriented-control-with-Machine-Learning/assets/96073522/a87d2c80-deb6-483c-ab26-50a7b0ba0f8c)


We used a Twin-Delayed Deep Deterministic Policy Gradient (TD3) machine learning algorithm to correct the signals sent as input to the controller’s inner control (current). The inputs to the algorithm were quadrature current iq, direct current id, errors in their values with respect to the reference frame, reference speed, and feedback state of the monitor. The TD3 algorithm-based and a conventional controller were implemented on MATLAB/Simulink, and their results were compared. Mean relative error was the metric of comparison between the two controllers. The results of mean relative error declared the TD3-algorithm-based controller to be better by 0.94% in quadrature current following as well as 0.94% in motor speed following as well.
![image](https://github.com/hassanrizwank/PMSM-drives-field-oriented-control-with-Machine-Learning/assets/96073522/dcfebba9-3b0a-48ea-8dc9-61ffb9b630e9)

