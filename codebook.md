## Description
- The original data set includes 561 features(not including subject and activity), after running "run_analysis.R", you will get a data set including only 66 features(not including subject and activity). The original data has 10299 records, and the final data set has only 180 records.

- The final data only selects the "mean and standard deviation" related features from the original data set.
> 1 "LAYING" 0.22159824394 

- "0.22159824394" means when the subject 1 conduct the "LAYING" gesture for many times, the mean value of data from body accelerator is 0.22159824394 on X dimension, so was all the other features.

## Features 
- subject: the subject label, each label represents a volunteer, range from 1 to 30, so there are 30 volunteers in total.
- activity: six activities
	- WALKING
	- WALKING_UPSTAIRS
	- WALKING_DOWNSTAIRS
	- SITTING
	- STANDING
	- LAYING
- tBodyAcc.mean.X: mean value for body accelerator on X dimension
- tBodyAcc.mean.Y: mean value for body accelerator on Y dimension
- tBodyAcc.mean.Z: mean value for body accelerator on Z dimension
- tBodyAcc.std.X: std value for body accelerator on X dimension
- tBodyAcc.std.Y: std value for body accelerator on Y dimension
- tBodyAcc.std.Z: std value for body accelerator on Z dimension

**All the remaining features have the very similar meanings.**


