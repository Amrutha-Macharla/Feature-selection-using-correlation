# Feature-selection-using-correlation
The accuracy of a dataset can be improved by feature selection. Here, I have used correlation technique to pickout the unnecessary features and calculate the best accuracy of a dataset.

The objective of feature selection is a crucial machine learning activity to pick out a small subset of relevant features
from a huge pool of candidate features. The hybridization of the algorithm involves using correlation to evolve a
subset of the features, represented by the chromosomes, and using the competitive swarm optimizer to optimize the
selected features.

In this project, we have taken 'titanic' dataset and loaded. 
In this particular dataset we are calculating the accuracy of the number of passengers alive or dead according to the dataset.
There are few irrelevant features in the dataset to calculate the accuracy so we will first look after them and delete the unnecesary columns.
Then by using correlation we can pick up a weak feature and eliminate it so that we can now have an efficient dataset to calculate the accuracy.
When we closely observe the accuracies before and after correlation there is a huge change in the values.
Before correlation the accuracy is 56% and after correlation it reaches upto 96%.
