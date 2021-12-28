# aversive_learning_simulation

Simulating SCR data based on aversive learning to test different MLE and Bayesian models of Reinforcement Learning models.

Currently I'm presenting to simple models of a task. 
Task simulate a simple aversive learning task in which participant watches one stimulus at a time. Two total stimuli can be presented, one (CS+) is paired with an electric shock 30% of the time and the other (CS-) is never paired with shock.

The actual task induces a skin-conductance response (SCR) for each of the trials. We expect an elevation in SCR for CS+ and demotion of SCR in CS-.

We use simle Rascorla-Wagner model here which states that:\
Expected value = EV[previous trial] + $\alpha$ * PredictionError

When\
PE = outcome - expected_value

