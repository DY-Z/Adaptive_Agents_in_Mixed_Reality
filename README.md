# Adaptive Agents in Mixed Reality

This is the final year project for my bachelor's degree in Data Science at The Hong Kong University of Science and Technology. In this project, we trained an agent who can not only play tennis but also adjust its behaviors according to its opponents' skills. We embedded this agent in an VR tennis game.

We trained the agent using Proximal Policy Optimization (PPO) algorithm. We replaced human players with cuboids while training, whose heights, widths, and velocities were carefully designed. 

![Main Menu](https://github.com/DY-Z/Adaptive_Agents_in_Mixed_Reality/blob/main/MainMenu_Full.png)

## Environment

To run the demo, you need a Windows 10 machine and a Oculus Rift/Rift S headset. The game's performance on Windows 11 hasn't been tested.

To open the project in Unity and Visual Studio, you will need

Unity: version 2020.3 or above\
Visual Studio: 2021 or above\
Input System: version 1.1.0-preview3 or above\
ML Agents: release 18 ( version 2.1.0-exp.1 if downloaded through Unity Package Manager)\
ML Agents Extensions: version 0.5.0-preview\
Animation Rigging: version 1.1 or above\
Unity XR Plug-in

## Agents
The baseline agent is hardcoded, while the adaptive agent is trained through reinforcement learning.

The details of our algorithm can be found in the presentation.

## Presentation
You can find our presentation slides here.\
https://docs.google.com/presentation/d/1eYQ3FjF0uSOf_IHLG9LD626fTM6PZsnmjM8Tf9Dch1g/edit?usp=sharing


