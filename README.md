A/B testing, also known as split testing, refers to a randomized experimentation process
wherein two versions of a variable (web page, page element, etc.)
are shown to different segments of website visitors at the same time 
to determine which version leaves the maximum impact and drives business metrics.

At Cookie Cats, As players progress through the game they will encounter gates that force them to wait some time before they can progress or make an in-app purchase. 
In this project, we will analyze the result of an A/B test where the first gate in Cookie Cats was moved from level 30 to level 40.

Steps in A\B Testing 
i . Define Control Group & Test Group 
ii . Check for normality, Apply Shapiro Test to check if Distribution is normal, 
iii. Check for homogeneity, Apply Levene Test for homogeneity of variances 
        Then, if Parametric and there is homogeneity of variances, apply T-Test 
        However, if Parametric - homogeneity of variances, apply Welch Test 
iv .If Non-parametric, apply Mann Whitney U Test directly

Conclusion: For our dataset, Mann Whitney U Testing failed to reject H0 hypothesis and we learned A/B groups are similar! 
Thus putting the gate at either level 40 or level 30 will give different results
