# Summer workshop on the dynamic brain 2016
Code for trial to trial variability analysis of brain observatory data from the Allen Institute

Most useful code is stimulusResponse_AL: pulls data from Allensdk (altho assumes that you have hdf files containing sweep by sweep data locally, since using AllenSdk to grab those files takes a long tme), performs COV, std, and reliability on all trials of all stimuli for every cell, runs K-S test and Anderson-Darling stats on those, and creates histograms.
