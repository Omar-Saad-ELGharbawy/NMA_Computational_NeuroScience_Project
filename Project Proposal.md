# The Project Proposal of Injera_Team1
## Research Question 
What is the difference in neuronal responses of the visual cortex to different stimuli?
## Ingredients
Different visual stimuli: here the 6 following stimuli will be used (refer to Benson's research paper for more info about the experiments)
"BAR1": Sweeping Bars repeat 1
"BAR2": Sweeping Bars repeat 2
"CCW": Counter Clockwise rotating wedge
"CW": Clockwise rotating wedge
"EXP": Expanding ring
"CON": Contracting ring
Neuronal responses of the brain to each run: preprocessed fMRI data which are the recorded activity of 91282 voxels over 300-time points
## Hypotheses 
There is no difference between the voxels' responses to the six different stimuli

We suppose that:  
mu_i is the mean of the distribution of voxels responses to the stimulus i  
i belong to {"CON", "EXP","CW","CCW","BAR1","BAR2"} which indicates the stimulus

We hypothesize that:  
mu_i = mu_j; where i and j belong to {"CON", "EXP","CW","CCW","BAR1","BAR2"} and i is not equal to j

In other words:
mu_CON = mu_EXP = mu_CW = mu_CCW = mu_BAR1 = mu_BAR2
## Tools
Python 
-t-statistics
