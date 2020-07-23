# A-B-Testing

## Introduction

For this project, I worked to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users. My goal was to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

## Part I - Probability
Statistics were computed to find out the probabilities of converting regardless of page. These were used to analyze if one page or the other led to more conversions.

## Part II - A/B Test
Next, hypothesis testing was conducted assuming the old page is better unless the new page proves to be definitely better at a Type I error rate of 5%.
The data was bootstrapped and sampling distributions were determined for both pages. Conclusions were drawn on conversions for both pages by calculating p-values.

## Part III - Regression
Logistic regression was then performed to confirm results of the previous steps. Null and alternative hypotheses associated with this regression model were stated and verified using statsmodel.
Next, along with testing if the conversion rate changes for different pages, I added an effect based on which country a user lives. Statistical output using logistic regression was provided to check if country had an impact on conversion.

## Conclusions
There was no evidence suggesting that those who explore either page will neccessary lead to more conversions
The country of the user did not impact the rate of conversion between the two pages

You can also check out my article [A/B Testing: the Basics](https://towardsdatascience.com/a-b-testing-the-basics-86d6d98525c9?source=friends_link&sk=86434b44e90841eb1a30e7e7cc2760eb)
