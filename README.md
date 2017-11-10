# FramingData
Neuroimaging Data Repository 
Created by Colleen Mills-Finnerty, Ph.D.
11/2017
cmillsfinn@gmail.com
cmfinn@stanford.edu


The data in this repository was collected in 2013-2015 at the Rutgers University Brain Imaging Center by Colleen Mills-Finnerty, PhD, Catherine Hanson, PhD, and Stephen Jose Hanson, PhD. For description of the appetitive and aversive framing stimuli and task, consult the following papers:

Mills-Finnerty, C., Hanson, C., & Hanson, S. J. (2014). Brain network response underlying decisions about abstract reinforcers. NeuroImage. http://doi.org/10.1016/j.neuroimage.2014.09.019
Mills-Finnerty, C., Hanson, C., & Hanson, S. J. (2017). Brain network connectivity underlying decisions between the “lesser of two evils.” http://doi.org/10.7287/peerj.preprints.3340v1


Aversive Framing Subject Data Key:

Subject Data:

Behavioral - reaction time files from PsychoPy
TS- time series in regions of interest extracted from FSL meanTS from BOLD data
preprocess - files with preprocessing (e.g. registration)
files - reconstructed, unprocessed anatomical and functional brain images in .nii format
1stLev - 1st level models run in FSL, named by condition:
	Aversive - HighHigh = high severity stimuli, rated as most aversive by subject

Group Analysis -
	 2nd level models in FSL (group means and contrasts)
	Graph analysis in Tetrad
	Behavioral data summary spreadsheet



Appetitive Framing Subject Data Key:

Subject Data:

betreg - files produced by FSL brain extraction tool (bet) and registration files
converted - registered/preprocessed data
1stLev - 1st level models run in FSL, named by condition:
	6ALL = positive and negative framing split by early/late and size baseline split early/late (6 regressors total)

Group Analysis:

	Framing_FSL- 2nd level models in FSL and graph analysis in Tetrad
	GraphAnalysis - connectivity analysis in Tetrad 

