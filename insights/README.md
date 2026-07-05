🛠️ Tools Used
Pandas & NumPy: For cleaning data, handling missing values, and manipulating columns.
Seaborn & Matplotlib: For plotting the distributions, trends, and categorical breakdowns.
📊 Quick Insights
The Gender Gap: The historical "women and children first" rule completely shows up in the data. Women had a massive survival rate of around 74%, while only about 19% of men made it out.
Class Divide: Wealth played a huge role. Over 60% of first-class passengers survived, whereas less than a quarter of third-class passengers survived.
Family Size: Traveling alone or with a massive family actually lowered your survival odds. The "sweet spot" was traveling in a small group of 2 to 4 family members.
Fares & Embarkation: Higher fares strongly correlated with survival. We also see higher survival rates for people who boarded at Cherbourg (C), but that's mostly because a huge chunk of them bought first-class tickets.
🧠 What I Did
Data Cleaning: Imputed missing ages based on passenger class medians and fixed a couple of missing embarkation points.
Feature Engineering: Combined the SibSp (siblings/spouses) and Parch (parents/children) columns into a single family size metric to see how traveling with others affected survival.
Visualization: Used Seaborn heatmaps for correlations and bar/box plots to easily compare survival rates across different demographics.
