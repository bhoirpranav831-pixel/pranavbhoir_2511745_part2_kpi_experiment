## TASK 6 : FRAME HYPOTHESES

1. null hypothesis(H0) :
	there is no significant different in control paid conversion rate and treatment paid conversion rate

H0 : treatment paid conversion rate = control paid conversion rate 

2. alternative hypothesis(H1) : 
	treatment paid conversion rate is higher than control conversion rate 

H1 : treatment paid conversion rate > control paid conversion rate 

3. Whether the test is one-tailed or two-tailed
	one-tailed test

4. Significance level used
	α = 0.05

5. Metric being tested
	paid Conversion Rate is the rate of conversion from a trial user or free user into a paying customer. It is chosen because it is the North Star Metric and an indication of how effective the campaign has been in generating profits for the company.

6. Reason for choosing that metric
	reason for choosing Paid Conversion Rate is because it is the North Star Metric of the test. It is the percentage of users who have paid their dues after going through the onboarding experience. This is an indicator of success in terms of growing revenue and business improvement for the company. The goal of the test is to grow the number of subscribers and hence this metric will prove to be the most relevant measure of success.

7. Interpretation logic
	If p-value is less than 0.05 then the Treatment has an impact on Paid Conversion Rate which means that onboarding campaign can be rolled out If p-value is 0.05 or greater there is not enough proof to claim that the Treatment has any influence on paid Conversion Rate.

## TASK 7 : PERFORM HYPOTHESIS OR AB TEST ANALYSIS

1. summary of Test Inputs
metric Tested: Paid Conversion Rate
control Group Sample Size: 692 users
treatment Group Sample Size: 714 users
sest Type: Two-Sample t-Test Assuming Unequal Variances
significance Level (α): 0.05

2. Test output

control Group Mean Conversion Rate: 0.031791908 (3.17%)
treatment Group Mean Conversion Rate: 0.06993007 (6.99%)
t-Statistic: -3.2801
degrees of Freedom (df): 1269


3. P-value or equivalent evidence

One-tailed p-value: 0.000532847
Two-tailed p-value: 0.001065693

4. Decision rule

If p-value < 0.05, reject the null hypothesis.
If p-value ≥ 0.05, fail to reject the null hypothesis.

according to rule one tailed p-value (0.000532847) is less than 0.05 then null hypothesis is rejected

5. Business interpretation

treatment paid conversion rate (6.99%) higher than control paid conversion rate (3.17%) The very low p-value provides strong evidence that the new onboarding campaign improved conversions. Based on the primary metric, the treatment shows a positive impact and can be considered for launch, subject to guardrail metric review.