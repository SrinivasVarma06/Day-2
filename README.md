# Day-2

Continuing from yesterday, 

Step-1: Generated the statistics of the data using df.describe() method.

Step-2: Generated Histograms, Boxplots, Pairplots and Correlation matrix for the data.

Step-3: Noting down the analysis obtained through these visualizations.

The results I obtained were as follows:-
  1. PClass and Sex have relatively high correlation with Survival rate. Higher fare often correlated with higher survival. 1st class paid more, and had higher survival.
  2. Females had survived more than males. 
  3. A large number of people on board belonged to age group 20-40 years with maximum being at around 28-30 years old. People with lesser age had higher survival.
  4. Boxplots helped visualize the outliers which were later removed. There were a lot of outliers in age and fare features.
  5. The distribution of each numerical feature were right-skewed except the age feature which was close to normal distribution. This can also be observed from the statistics printed using describe method.
