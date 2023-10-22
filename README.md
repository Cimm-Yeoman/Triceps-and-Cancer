# Triceps-and-Cancer
## Part 1 
The first section of this report evaluated the tricep skinfold thickness of 892 Gambian women in three West African villages, over 50 years. The *triceps brachii* is a muscle situated on the back of the the arm, and includes a lateral, long, and medial head (see Figure 1). The data set includes the tricep skinfold thickness measurements of the Gambian women, the log of the tricep skinfold thickness measurements, and the age of the women. The tricep skinfold thickness was predicted as a function of age, using a smoothing model.
## Part 2
The second section of this report focuses on cancer, one of the leading causes of death in the United States and across the globe. The disease exists in various forms, and millions of people, both young and old, receive a cancer diagnosis each year. This report contains a United States focused data set, consisting of health and socioeconomic factors from 3047 counties. The response variable or variable of interest was **TARGET_deathRate**, 
the mean per capita (100,000) cancer mortalities. 

The goal of this analysis was to identify relevant predictor variables that could be candidates for a smooth relationship. A model with smoothing was compared to a basic
model. Both natural cubic splines and the smoothing.spline package were used. Variable selection was performed using the lasso regression method. 
