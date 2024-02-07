# schedule_it 
## Objective
To perform task scheduling based on CPU and Memory allocation to maximise resource utilisation using Reinforcement Learning methods, such as Q-Learning, Double Q-Learning and Deep Q-Network.
## Environment Creation
States: No.of tasks to be scheduled (m)

Actions: Selecting a task, Not selecting a task (0/1)

Reward/Penalty based on the "Resources" ([CPU, Memory])

Reward Calculation:
1. Reward = sum(CPU, Memory)
2. Penalty = -sum(CPU, Memory)/10

Penalty if:
1. sum(CPU, Memory) > limit 
2. Selecting an already scheduled task.

To analyse the output with ease the no.of job samples is 1, but the inputs can be altered to handle input dynamically.

## Approaches compared
1. Q-Learning
2. Double Q-Learning
3. Deep Q-Network

## Observations
Deep Q-Network achieves a good tradeoff in the exploration-exploitation conundrum, compared to Q-Learning and Deep Q-Learning. Thus, helping to achieve maximum resource utilisation.

Results from all the above models can be sampled for n no.of times and the average result can be viewed for better understanding.

Done the project with @monisha-0311.
