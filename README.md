We want to see th erelationship between th enumber of selected features and MAE, in this relationship. we may expect th emore features results in better peformance , to a point, This relationship can be explored
by manually evaluating each configuration of k  for the SelectKBest from 81 to 100, gathering the sample of MAE scores and plotting the results using box and whisker plots side by side, The spread and mean of these
box plots would be expected to show any intresting relationship between the number of selected features and the MAE of the pipeline, Note that we started the spread of k values at 81 instead of 80 because the 
distribution of MAE scores for k=80 is dramatically larger than all other values of k considered and it washed out the plot of the results on graph.
