This Tsay_Kim_2022_Data_README.txt file was generated on 2022-04-08 by Jonathan Tsay. 


GENERAL INFORMATION

1. Title of Dataset: Data from: Dissociable use-dependent learning processes for volitional goal-directed reaching.

2. Author Information
	Corresponding Investigator 1
		Name: Dr Jonathan Tsay
		Institution: UC Berkeley
		Email: xiaotsay2015@berkeley.edu

	Corresponding Investigator 2
		Name: Prof Hyosub Kim
		Institution: University of Delaware

	Co-investigator 1
		Name: Arohi Saxena
		Institution: UC Berkeley
	
	Co-investigator 2
		Name: Dr Darius Parvin
		Institution: UC Berkeley 

	Co-investigator 3
		Name: Prof Timothy Verstynen
		Institution: Carnegie Mellon University

	Co-investigator 4
		Name: Prof Rich Ivry
		Institution: UC Berkeley


3. Date of data collection: 2016-2018

4. Geographic location of data collection: Berkeley, California

5. Funding sources that supported the collection of the data: 
	Foundation for Physical Therapy Research
	NIH NINDS

6. Recommended citation for this dataset: Tsay*, Kim* et al. (2022), Data from: Dissociable use-dependent learning in volitional reaching, Dryad, Dataset


DATA & FILE OVERVIEW

1. Description of dataset

These data were generated to investigate dissociable components in use-dependent learning in volitional reaching. Recent experiments that impose strict constraints on planning time have revealed two sources of use-dependent biases, one arising from dynamic changes occurring during motor planning and another reflecting a stable shift in motor execution. Here, we used a distributional analysis to examine the contribution of these biases in reaching. To create the conditions for UDL, the target appeared at a designated "frequent" location on most trials, and at one of six "rare" locations on other trials (Exp 1, N = 10). Strikingly, the heading angles were bimodally distributed, with peaks at both frequent and rare target locations. Despite having no constraints on planning time, participants exhibited a robust bias towards the frequent target when movements were self-initiated quickly, the signature of a planning bias; notably, the peak near the rare target was shifted in the frequently practiced direction, the signature of an execution bias. These dissociable components were replicated in a classic dataset in use-dependent learning by Verstynen and Sabes (N = 8). Furthermore, these execution biases were not only replicated in a delayed response task but were also insensitive to reward (Exp 2, N = 32). Taken together, these results extend our understanding of how volitional movements are influenced by recent experience.

2. File List: 
	File 1 Name: UD_E1.csv
	File 1 Description: Experiment 1 data. 

	File 2 Name: UD_E2.csv
	File 2 Description: Experiment 2 data. 

	File 3 Name: VerstynenSabes2011.csv
	File 3 Description: Verstynen and Sabes (2011) data

	File 4 Name: UD_WithTraj.csv
	File 4 Description: Experiment 1 trajectory data. 

	
METHODOLOGICAL INFORMATION

See Tsay, Kim et al for details. 

DATA-SPECIFIC INFORMATION FOR: UD_E1.csv

1. Number of variables: 21

2. Number of cases/rows: 8601

3. Variable List: 
	SN: subject number.
	TN: trial number
	block: different blocks in the experiment (1 = veridical feedback; 2 - 10 = use-dependent learning blocks). 
	trainTgt: training target location (top right quadrant: 60; top left quadrant: 150). 
	hand_theta: hand angle at target radius
	hand_theta_maxv: hand angle at maximum velocity
	hand_theta_maxradv: hand angle at max radial velocity
	hand_theta_100: hand angle 100 ms after movement initiation
	hand_theta_40/Hand: hand angle 40 ms after movement initiation
	ti: target angle. 
	fbi: cursor feedback (1 = cursor feedback provided; 0 = cursor feedback not provided).
	MT: movement time
	RT: reaction time
	ST: search time (i.e., time between end of trial to finding the start location) 
	radvelmax: maximum radial velocity
	Distance_raw: angular distance from training target (between 0-360)
	Distance: angular distance from training target (between 0-180). 
	Handb: baseline subtracted hand angle at 40 ms after movement.
	RTb: baseline subtracted RTs.
	Hand_IB: inward bias.
	CN: cycle number. 

DATA-SPECIFIC INFORMATION FOR: UD_E2.csv

1. Number of variables: 16

2. Number of cases/rows: 30209

3. Variable List: 
	SN: subject number.
	TN: trial number
	group: group assignment (R = reward group; N = no reward group)
	block: different blocks in the experiment (1 = veridical feedback; 2 - 8 = use-dependent learning blocks). 
	trainTgt: training target location (top right quadrant: 60; top left quadrant: 150). 
	hand_theta: hand angle at target radius
	hand_theta_maxv: hand angle at maximum velocity
	hand_theta_maxradv: hand angle at max radial velocity
	hand_theta_100: hand angle 100 ms after movement initiation
	hand_theta_40: hand angle 40 ms after movement initiation
	ti: target angle. 
	fbi: cursor feedback (1 = cursor feedback provided; 0 = cursor feedback not provided).
	MT: movement time
	RT: reaction time
	ST: search time (i.e., time between end of trial to finding the start location) 
	radvelmax: maximum radial velocity
	

DATA-SPECIFIC INFORMATION FOR: VerstynenSabes2011.csv

1. Number of variables: 4

2. Number of cases/rows: 673

3. Variable List: 
	SN = subject number
	Distance = distance from training target
	RT = reaction time
	Hand_IB = inward bias

DATA-SPECIFIC INFORMATION FOR: UD_WithTraj.csv

1. Number of variables: 11

2. Number of cases/rows: 6791

3. Variable List: 
	SN = subject number
	TN = trial number
	trainTgt: training target location (top right quadrant: 60; top left quadrant: 150). 
	ti = target location.
	fbi = veridical feedback provided (0 = no; 1 = yes). 
	hx? = hand position on x axis (# = sampling timepoints).
	hy? = hand position on y axis (# = sampling timepoints).
	absvel? = absolute velocity (# = sampling timepoints).
	absacc? = absolute acceleration (# = sampling timepoints).
	hdist? = hand distance (# = sampling timepoints).
	radvel? = radial velocity (# = sampling timepoints).

	
	









