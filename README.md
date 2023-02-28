# Analysis-and-Visualization-of-Peanut-Allergy-Experiment-

# About this Project

In order to lower the risk of acquiring an allergy, it was thought that young children should avoid eating peanuts in their diets in the late 1990s. Researchers were no longer so certain in 2008. This study assesses the benefits and risks of exposing infants with additional allergic reactions, such as severe eczema, egg allergy, or both, to peanuts. Around 500 of these young children, who had previously been warned not to eat peanuts throughout the years 2–5, were given a peanut diet regimen (consume or avoid). The main result was that every child under the age of five had a peanut allergy test.

# Problem Statement

Does diet regimen have an association of developing a peanut allergy.

# Data Used

- The variables included in the dataset are:

    - had_early_risk: Indicates if the child was deemed to be at elevated risk of developing a peanut allergy at the start of the study based on a pin-prick test.
    - regimen: The peanut regimen assigned for the child, either "avoid" or "consume".
    - allergic: Indicates if the child had developed a peanut allergy by the end of the study.


# Loading and Working with the Data 

![image](https://user-images.githubusercontent.com/126027138/221912892-f2e3d22a-7569-47b3-8ad0-20ecdb515e65.png)


# Displaying results and proportions of Data 

![image](https://user-images.githubusercontent.com/126027138/221916891-b0b83251-659d-4ead-a5c2-933ce6339e27.png)


![image](https://user-images.githubusercontent.com/126027138/221917366-2df3fc29-20d0-4e67-993e-1cab2a7d447c.png)


- Data showcases the results from the data set from each treatment group regimen) that developed, and did not develop, a peanut allergy (allergic) by the end of the study. 

# Visualizing the proportions from the results of the study

![image](https://user-images.githubusercontent.com/126027138/221918638-e97de117-85e6-458c-859d-a1914f9cff74.png)

- Barplot visualies a comparison of subjects within each treatment group (regimen) that developed, and did not develop, a peanut allergy (allergic). 

There does seem to be a link between a child's diet and whether or not that child develops a peanut allergy. Just 3% of kids who ate peanuts went on to acquire a peanut allergy; in contrast, nearly 17% of kids who didn't eat peanuts did. This significant difference raises the possibility that a diet-related peanut allergy may exist.

# Conducting a Chi Squared Test 

![image](https://user-images.githubusercontent.com/126027138/221920688-7efd25ff-80f4-4d17-9a46-18f4be180dfe.png)

- The chi test is a test of independance to test the null hypothesis that there is no association betweenn diet regiman and developing a peanut allergy. From the test we can see test 

- We can see that the test statistic is 𝜒<sup>2</sup> = 33.683 and the p - value is almost 0. 


# Construction of 95% Confidence Interval 

![image](https://user-images.githubusercontent.com/126027138/221929002-c3455ba6-bed1-4131-a9dd-4ce3149eedc4.png)

- From this, we know that we are 95% confident that among all children with prior allergic conditions, the proportion who will develop a peanut allergy is between 9.4% to 18.6% higher among those who avoid peanuts than among among those who consume peanuts.

# Relative Risk Calculation

![image](https://user-images.githubusercontent.com/126027138/221933745-c68c721d-4db7-4688-83a6-06e8a053f9f6.png)


- This determined what proportion of children in the study were deemed to be at elevated risk of developing a peanut allergy (had_early_risk) at the start of the study which was based on pin-prick test. So, we can conclude that Of the children in the study, 0.156 or 15.6% were deemed to have an elevated risk of developing a peanut allergy

# Conclusions

The research shows convincing evidence linking dietary habits to the occurrence of peanut allergies in children with prior allergic conditions. As there is virtually zero support for the null hypothesis that there is no link, there is high evidence for an association, according to the p-value shown in the Chi squared test which was basically zero. Moreover, the confidence interval implies that children who avoid peanuts have at least a 0.4% higher likelihood of developing a peanut allergy compared to those who don't.






