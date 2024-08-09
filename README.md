# Statistics-and-Startups
## Description
The dataset encompasses startups from around the world. In this analysis, we focused on Indian startups, examining both the average funds raised and the number of funding rounds they underwent. We were looking at startups that are either operating and those that are closed.
## Objective
To perform statistical tests to understand:
- if there is a statistically significant difference in the **mean funds** raised between startups that are **operating** and those that are **closed** by using an independent sample t-test.
- If there is a statistically significant difference in the **funding rounds** between **operating** and **closed** startups by using the chi-square test of independence.
## Data Cleaning and Preparation
- Filtered Data based on Country because had to analyze Indian Startups data.
- For simplicity restricted the status category for closing and operating startups.
- Removed data where the amount of funding was missing.
- Created Funding round categories of **1,2 and 3+** as the majority of data was between 1,2 and 3 rounds.
## Analysis and Insights
1. Total Data for startups after performing the cleaning operation was around 1134 Startups, of which 1085 were currently operating and 49 had ceased operations.
2. Startups that went through just 1 round of funding were 795, 2 rounds were 205 and 3+ were 134.
3. the P-value in both tests was above the significance level of 0.05.
4. There was no statistically significant difference in the mean funds raised between startups that are operating and those that are closed.
5. There was no statistically significant difference in the funding rounds between operating and closed startups.
## Conclusion
This project aimed to explore the financial characteristics of Indian startups by examining their operational status in relation to the funds they raised and the number of funding rounds they underwent. Through detailed statistical analysis and visualization, the following key findings emerged:
- **Mean Funds Raised:**
The independent sample t-test indicated no statistically significant difference in the mean funds raised between startups that are currently operating and those that have closed.
This suggests that the total amount of funding may not be a decisive factor in determining whether a startup succeeds or fails.
- **Funding Rounds:** 
Similarly, the chi-square test of independence did not show a statistically significant difference in the number of funding rounds between operating and closed startups. This implies that the number of funding rounds alone may not significantly influence a startup's chances of survival.

#### These findings challenge common assumptions that higher funding amounts and more funding rounds are directly linked to startup success. The results suggest that other factors, possibly beyond just financial metrics, could play a more crucial role in determining the long-term viability of startups.
#### Future research could benefit from investigating additional factors, such as the startup’s business model, market conditions, or the experience of the founding team, to better understand what drives success in the startup ecosystem.

