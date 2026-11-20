# Telecom Customer Churn Analysis

A Tableau dashboard exploring customer churn, reported reasons for leaving, customer age groups, and revenue by customer status. Completed as a Data in Motion milestone project.

**Author:** Nana Ekow Bryan Sackey

**Tool:** Tableau

[View the interactive dashboard on Tableau Public](https://public.tableau.com:9443/views/TelecomCustomerChurnAnalysisDashboard_17908460236670/CustomerChurnOverview?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Project objective

Explore which customer groups have higher churn and what reasons customers report for leaving, to identify opportunities for customer retention.

The analysis focuses on:

- How many customers churned, and how is the churn rate calculated?
- Which categories and reasons account for the most departures?
- How does customer status vary by age group?
- How does recorded revenue differ between churned and retained customers?
- How can location and contract filters help explore customer segments?

## Dataset

The supplied telecom dataset contains **7,043 customer records** and **38 columns**, including demographics, location, tenure, contracts, services, charges, revenue, customer status, and churn reasons.

| Customer status | Customers |
|---|---:|
| Stayed | 4,720 |
| Churned | 1,869 |
| Joined | 454 |
| Total | 7,043 |

## Dashboard features

- KPI cards for churn rate, churned customers, total customers, and average tenure at churn.
- Bar chart showing the distribution of churn categories.
- Revenue comparison for churned and retained customers.
- Stacked bars comparing customer status across age groups.
- Treemap of reported churn reasons.
- ZIP-code map for geographic exploration.
- Filters for age group, contract, and city.

## Key findings

The following figures describe the supplied dataset at the unfiltered overview level.

| Finding | Result |
|---|---|
| Customers who churned | 1,869 |
| Dashboard churn rate, excluding joined customers | 28.4% |
| Churned customers as a share of all records | 26.5% |
| Average tenure among churned customers | Approximately 18 months |
| Largest reported churn category | Competitor: 841 customers, or 45.0% of churned customers |
| Most common individual churn reason | Competitor had better devices: 313 customers, or 16.7% |
| Second most common individual churn reason | Competitor made better offer: 311 customers, or 16.6% |
| Recorded total revenue from churned customers | $3,684,459.82 |
| Recorded total revenue from customers who stayed | $17,632,392.12 |

Competitor-related departures account for nearly half of churn. Dissatisfaction accounts for **17.2%**, attitude for **16.8%**, price for **11.3%**, and other reasons for **9.7%**.

## Metric definitions

**Dashboard churn rate:**

`Churned / (Churned + Stayed) = 1,869 / 6,589 = 28.4%`

This excludes the 454 customers whose status is Joined. The total-customer KPI includes them.

**Churned share of all customers:**

`Churned / Total customers = 1,869 / 7,043 = 26.5%`

**Churn category and reason percentages:**

`Customers in a churn category or reason / 1,869 churned customers`

**Average tenure at churn:** Average Tenure in Months for customers whose status is Churned.

**Revenue by status:** Sum of Total Revenue for each customer status. These are recorded revenue totals, not estimates of future revenue lost or recoverable revenue.

## Recommendations

1. **Review competitive offers and devices.** Investigate the offers and device options associated with competitor-related departures, then test targeted retention offers.
2. **Improve service and support experiences.** Use the dissatisfaction and attitude categories to prioritize follow-up research, service recovery, and support training.
3. **Explore retention needs by segment.** Use age, contract, and city filters to identify groups for further investigation. Review customer counts alongside rates before prioritizing small segments.
4. **Test and measure interventions.** Track whether retention initiatives improve outcomes before expanding them. This analysis identifies opportunities; it does not prove which intervention will work.

## Skills demonstrated

Tableau dashboard design, KPI presentation, customer segmentation, geographic visualization, interactive filtering, and communicating analytical findings.

## Interpretation notes

- This is a descriptive project based on the supplied dataset; associations do not establish causes.
- The dataset's original source and observation period are not documented here. Results should not be treated as current industry benchmarks.
- The Joined group is excluded from the headline churn calculation and the displayed churned-versus-stayed comparisons.

## Explore the dashboard

Open the Tableau Public link above to explore the views and available filters.
