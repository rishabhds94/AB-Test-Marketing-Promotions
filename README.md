# AB-Test-Marketing-Promotions
Which promotion was the most effective?
### Introduction
A fast food chain plans to add a new item to its menu. However, they are still undecided between three possible marketing campaigns for promoting the new product. In order to determine which promotion has the greatest effect on sales, the new item is introduced at locations in several randomly selected markets. A different promotion is used at each location, and the weekly sales of the new item are recorded for the first four weeks.
Dataset - Marketing-Campaign
Description - Dataset contains data of a campign.

The varaible used in the dataset are described below:
1. MarketId: an inhouse tag used to describe market types, we won't be using it
2. AgeOfStores: Age of store in years (1–28). The mean age of a store is 8.5 years.
3. LocationID: Unique identifier for store location. Each location is identified by a number. The total number of stores is 137.
4. Promotion: One of three promotions that were tested (1, 2, 3). We don’t really know the specifics of each promotion.
5. Sales in Thousands: Sales amount for a specific LocationID, Promotion and week. The mean amount of sales are 53.5 thousand dollars.
6. Market size: there are three types of market size: small, medium and large.
7 Week: One of four weeks when the promotions were run (1–4).

### T-Value
The t-value measures the degree of difference relative to the variation in our data groups. Large t-values indicate a higher degree of difference between the grups.

### P-Value
P-value measures the probability that the results would occur by random chance. Therefore the smaller the p-value is, the more statistically significant difference there will be between the two groups

## Comparing Promotion 1 vs Promotion 2 in an A/B Test
t-value = 6.42752867090748
p-value = 4.2903687179871785e-10
## Analysis of P and t-values
Our P-Value is close to 0 which suggests that there is good evidence to REJECT the Null Hypothesis. Meaning the there is a statistical difference between the two groups. Our threshold rejectings the Null is usually less than 0.05.

Our t-test shows that the marketing performances for these two groups are significantly different and that promotion group 1 outperforms promotion group 2

## Comparing Promotion 1 vs Promotion 3 in an A/B Test
t-value = 1.5560224307758634
p-value = 0.12059147742229478
## Analysis of P and t-values
We note that the average sales from promotion group 1 (58.1) is higher than those from promotion group 2 (55.36).

But, running a t-test between these two groups, gives us a t-value of 1.556 and a p-value of 0.121.

The computed p-value is a lot higher than 0.05, past the threshold for statistical significance.
