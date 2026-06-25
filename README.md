# pranavbhoir_2511745_part2_kpi_experiment

## TASK 1 : UNDERSTAND THE BUSINESS PROBLEM

The firm introduced a new onboarding and activation campaign aimed at improving the rates of user conversions and engagement. The subjects have been allocated into two groups; Control Group consisting of the current onboarding experience and Treatment Group consisting of the new campaign experience. The core decision here is whether to launch the new campaign to all users.

The key objective here is to enhance the Paid Conversion Rate since it affects the growth in revenues. Before suggesting an optimal course of action, the company needs to assess the results of the experiment, test hypothesis and guardrails like refund rate, support ticket rate, and engagement score.


## TASK 4 : CLEAN AND PREAPARE EXPERIMENT DATA

Distribution of segments across groups was done for Region, Device Type, Traffic Source, and Plan Type. Comparison of distribution between the Control and Treatment groups revealed that the distribution is quite well-balanced, which implies that the groups were appropriate for experimentation.


## README Requirements : 

1. Business context

The objective of this assignment was for an SaaS company to conduct an experiment on their new onboarding campaign in order to test whether their new onboarding process should be launched to their users or not. The users were divided into two groups; Control group which experienced existing onboarding and the Treatment group which experienced the new onboarding process.

2. Dataset description

dataset contains user level experiment data, such as experiment group allocation, user segments, onboarding actions, conversions, revenue, engagement metrics, refunds, and support tick

3. North Star metric selected

Paid Conversion Rate

It refers to the proportion of people who end up becoming paying customers and represents business growth and income.

4. KPI tree summary

KPI tree built around paid conversion rate primary drivers include :

Landing Page Visit Rate
Trial Start Rate
Onboarding Completion Rate

Guardrail metrics included:

Refund Rate
Support Ticket Rate
Engagement Score
Average Days to Convert
Revenue Quality
Segment-Level Performance

5. Experiment analysis approach

dataset was cleaned and validated by checking:

Missing values
Group counts
Duplicate user IDs
Invalid binary values
Revenue outliers
Segment distribution across groups

Control and Treatment Groups were analyzed on the basis of major business KPIs, and segment level analysis was carried out for Region, Device, Traffic Sources, and Plan Type.

6. Hypothesis test summary

A one-tailed hypothesis test was performed using Paid Conversion Rate as the primary metric.

Control Conversion Rate: 3.17%
Treatment Conversion Rate: 6.99%
P-value: 0.000532847
Significance Level: 0.05

Since the p-value was below 0.05 null hypothesis was rejected indicating a statistically significant improvement in paid conversion rate

7. Guardrail metrics considere

Refund Rate
Support Ticket Rate
Average Days to Convert
Engagement Score
Revenue Quality
Segment-Level Performance

These metrics were evaluated to ensure that increased conversions did not negatively impact user experience or revenue quality.


8. Final recommendation
Launch

treatment group provided a statistically significant uplift in Paid Conversion Rate and demonstrated no alarming trends regarding the tested guardrails findings of the experiment suggest that the new onboarding campaign can be launched.

9. Assumptions and limitations

experiment sample is representative of target user population.
User behavior may change over time.
Results are based on observed experiment period.
Additional monitoring is recommended after launch.

10. Screenshots included

summary_metrics.png – Control vs Treatment summary table
hypothesis_test_output.png – Hypothesis test output and p-value evidence
kpi_tree_preview.png – KPI Tree visualization
