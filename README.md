# SMB-GA
A Genetic Algorithm approach to creating a DNN that succeeds at the original Super Mario Bros. game for the NES.

Deep_Neuroevolution_SMB_general.ipynb is the main code notebook, able to evolve the agent population across the entire game rather than just a single stage like Deep_Neuroevolution_SMB_general_first.ipynb. Additionally, the remaining notebook contains a modified system that attempts to distribute the mutation, evolution, and agent evaluation processes across multiple processor cores. I do not guarantee that this multiprocess version works properly.

Single-Stage Agent on 1-1
![Single-Stage Agent on 1-1](Examples/3161%201-1.gif)


General-Stage Agent on 7-2
![General-Stage Agent on 7-2](Examples/486%207-2.gif)


A special thanks to D0miH for the initial working structure of this project from https://github.com/D0miH/deep-learning-super-mario/tree/master/NeuroEvolution
