# Programming for Psychologists - Home Assignment
Name: Kiki Beekman\
Date: 19-11-2024\
Vrije Universiteit Amsterdam

Data that fits this project can be found on [Neurosynth](https://neurosynth.org/) under Meta-analyses --> Terms. The specific data that was used in this project can be found [here](https://neurosynth.org/analyses/terms/mental%20imagery/).


PROJECT\
This project aims to visualize the fMRI data associated with a specific cognitive concept (e.g. episodic memory) or clinically relevant term (e.g. depression). It does so by plotting the functional data acquired from Neurosynth over the anatomical map of the brain. Additionally, a histogram is created that shows the distribution of the positive values within the functional data of the chosen concept (in this case mental imagery).


TABLE OF CONTENTS
- To be able the visualize the fMRI data of the chosen concept, two data files are required. The first datafile is a file containing the anatomical map of the brain (1), the second datafile is a file containing the functional data of the chosen concept (2). Important is that both files need to have the ".nii.gz" extension
	(1) anatomical.nii.gz
	(2) mental imagery_uniformity-test_z_FDR_0.01.nii.gz
- The code to create the visualization and plot of the functional data can be found in the attached Jupyter Notebook (3)
	(3) fMRI_home_assignment.ipynb

USED PACKAGES\
The packages that are used throughout the script are as follows:
- glob2
- matplotlib
- nilearn
- nibabel

