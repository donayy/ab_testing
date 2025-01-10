# A/B testing

A/B testing is a statistical method used to compare two different groups (Control and Test) in order to evaluate the effectiveness of changes or new features. 
By conducting this test, businesses can make data-driven decisions to improve their offerings.

Key Steps in A/B Testing:
Hypothesis Formation: The first step involves defining the null hypothesis (H0) and alternative hypothesis (H1). 
In this case, we assume that there is no significant difference in conversion rates or metrics (H0: p1 = p2), and the alternative hypothesis suggests a difference exists (H1: p1 ≠ p2).

Data Collection: The test involves collecting data from two groups – one exposed to the current feature or method (Control group) and the other exposed to the new feature or method (Test group). 
Metrics, such as conversions, purchases, or other relevant data points, are then analyzed.

Assumption Testing: Before running the statistical test, assumptions like normality (whether the data follows a normal distribution) and homogeneity of variances (whether both groups have similar variability) are checked. 
This ensures the validity of the chosen statistical test.

Statistical Testing: Depending on the results of the assumption tests, an appropriate test is chosen. 
If assumptions hold, a parametric test like the T-test is applied to compare the means of both groups. 
If not, non-parametric tests like the Mann-Whitney U test may be used.

Result Analysis and Decision Making: The test results are then analyzed. 
A p-value greater than 0.05 typically indicates that there is no significant difference between the groups, meaning the current method (e.g., max bidding) should continue. 
A p-value less than 0.05 would suggest a significant difference, and the new feature (e.g., avg bidding) may be adopted.

This methodology allows businesses to test changes and improvements in a controlled, measurable way to ensure that any adjustments will lead to positive outcomes.
