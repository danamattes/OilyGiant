# OilyGiant
Using machine learning to select the region for a new well with the highest profit margin.

OilyGiant is looking for a the best location for a new well. For this matter, three areas have been pre-selected. The information of these areas will be analyzed in order to identify the area with the biggest amount of reserves, as well as perform a risk assessment. 

**Objective:** OilyGiant is looking for a the best location for a new well. For this matter, three areas have been pre-selected. The information of these areas will be analyzed in order to identify the area with the biggest amount of reserves, as well as perform a risk assessment. 

**Method:** In order to be able to reach the objective, we will first prepare the data: deal with any missing information or duplicates. We will prepare the features, dealing with the type of information and scales. Next, we will train a model that can predict the volume of reserves in the new wells, we will select the oil wells with the highest estimated values and finally we will pick the region with the highest total profit for the selected oil wells.

We will be using the bootstrapping technique to analyze the potential profit and risks for each area.

**Conclusions:** After analizing all three of the areas, it was concluded that the region 1 is the best option for the development since it will generate the highest average profit, when obtaining a confidence interval of 95% the area remains profitable even at the lower end of the interval and it has the lowest probabilities of generating a negative result.

To obtain this result, we trained a Linear regression model, evaluated profit for each region using the bootstrapping technique, obtained a confidence interval and evaluated the probabilities of a negative outcome.
