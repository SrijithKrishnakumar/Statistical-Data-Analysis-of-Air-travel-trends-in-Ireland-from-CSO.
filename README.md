Air Travel Trends in Ireland: Statistical Business Analysis
This project delivers an advanced business and statistical analysis of air travel trends in Ireland, using passenger movement data between 2013 and 2023. The work was completed as part of the MSc in Business Analytics at University College Dublin and is positioned at a corporate decision‑support level, focusing on demand dynamics, seasonality, and post‑pandemic recovery patterns.
​

Business Context:
Air travel is a critical enabler of Ireland’s tourism, trade, and FDI‑driven economy, with Dublin Airport acting as a primary gateway for international passengers. Understanding the evolution of passenger volumes, route structures, and seasonal peaks is essential for:
​

Airlines optimising network planning, fleet utilisation, and yield management.
​
Airport operators planning capacity, resource allocation, and capital investments.
​
Policy makers evaluating connectivity, sustainability, and regional development priorities.
​

This project translates raw passenger statistics into actionable insight for commercial and operational stakeholders in aviation and adjacent sectors such as tourism and hospitality.
​
Objectives and Key Questions
The analysis is structured around four core business questions.
​

Growth and demand dynamics

How have total passenger numbers evolved over time (pre‑, during, and post‑Covid)?
​
Are observed changes statistically significant across years and seasons?
​

Seasonality and peak‑period management

What seasonal patterns exist in air travel demand (e.g. summer vs winter, holiday peaks)?
​
How stable are these patterns across years, and did Covid‑19 structurally alter them?
​
Route and airport performance

Are there statistically significant differences in passenger volumes between key airports and/or routes?
​
Which segments are driving overall growth or contraction?
​

Post‑pandemic recovery and resilience

To what extent has Irish air travel recovered to pre‑2019 levels?
​
Which segments show the fastest recovery and where do risks remain?
​

Data Description
The dataset used in this analysis is based on structured passenger movement statistics for Irish air travel. It includes:
​
Time period: Annual and intra‑year observations across multiple years around the Covid‑19 period (e.g. 2013–2023).
​Geography: Major Irish airports (e.g. Dublin, Cork, Shannon) plus aggregated national totals.
​Metrics: Passenger counts, directional flows (arrivals/departures), and segmentation by time period.
​

Data cleaning steps included:
​
Validation of totals and removal of obvious inconsistencies.

Handling of missing values via listwise deletion or imputation as appropriate to the test design.

Creation of derived fields (e.g. year, period, airport category) for statistical modelling.
​

Methodology
The project applies a full statistical workflow aligned with corporate analytics standards, combining exploratory data analysis and inferential statistics.
​

Exploratory Data Analysis (EDA)
EDA was performed to understand distributions, outliers, and structural patterns.
​

Time‑series plots of total passengers by year and by airport.

Seasonal profiles of monthly/quarterly passengers highlighting peak periods.

Comparison of pre‑Covid (baseline), Covid‑impact, and recovery years.
​

EDA allowed the identification of non‑linear effects, structural breaks around 2020, and inter‑airport heterogeneity in trends.
​

Hypothesis Testing
A set of business‑oriented hypotheses was formalised and tested with standard statistical techniques.
​

Two‑sample and paired t‑tests

Comparing mean passenger volumes between two periods (e.g. pre‑Covid vs Covid years, or pre‑Covid vs post‑Covid).
​

Assessing whether recovery years are statistically different from the pre‑pandemic baseline.
​

One‑way and two‑way ANOVA

Testing for significant differences in average passenger counts across multiple years.
​

Evaluating interaction effects between year and airport or season on passenger volumes.
​

Post‑hoc analysis (Tukey HSD)

Identifying specifically which years or airports differ materially when ANOVA indicates overall significance.
​

All tests were executed under clearly defined null and alternative hypotheses, with significance levels typically set at 
α
=
0.05
α=0.05.
​

Assumption Checking
Before interpreting test results, key model assumptions were evaluated.
​

Normality of residuals using Q–Q plots and tests such as Shapiro–Wilk where relevant.

Homogeneity of variances via Levene’s test.
​

Independence considerations based on the time‑series nature of the data and grouping structure.
​

Where assumptions were violated, results were interpreted cautiously and, where necessary, non‑parametric alternatives or data transformations were considered.
​

Key Insights and Business Interpretation
Demand Trajectory and Covid‑19 Impact
Total passenger volumes show a strong upward trajectory in the pre‑Covid period, reflecting growing connectivity and tourism demand.
​

2020–2021 exhibit a structurally significant collapse in passenger numbers, with statistical tests confirming that Covid‑era means are markedly lower than all other years.
​

Recovery years show a sharp rebound, with recent values approaching or surpassing pre‑2019 levels, although confidence intervals indicate residual volatility.
​

Seasonality and Capacity Planning
Clear seasonality is visible, with pronounced peaks in summer and holiday periods, and troughs in off‑peak months.
​

ANOVA across seasons confirms statistically significant differences in average passenger volumes, supporting differentiated pricing, staffing, and capacity planning strategies.
​

Despite Covid‑related disruption, underlying seasonal structure re‑emerges in recovery years, suggesting that long‑term demand patterns remain stable.
​

Airport and Route Performance
Larger hubs such as Dublin consistently handle significantly higher passenger volumes than regional airports, as confirmed by multi‑factor ANOVA.
​

The interaction of year × airport indicates that the pace of recovery is not uniform across locations, with some airports lagging in returning to pre‑Covid traffic.
​

These results can inform targeted marketing, route development, and infrastructure decisions at both national and airport‑operator level.
​

Post‑Pandemic Recovery and Strategic Implications
Statistical evidence suggests that Irish air travel has largely transitioned from crisis management into recovery and growth, though with heightened exposure to macro‑shocks.
​

Airports and airlines can leverage this analysis to:

Re‑optimise capacity and staffing for seasonal peaks.

Prioritise investment in high‑growth routes and airports.

Support data‑driven negotiations with regulators, tourism boards, and commercial partners.
​

Technical Implementation
Although the original work was developed in a spreadsheet environment, the design is fully compatible with Python/R workflows and enterprise BI tools. A typical reproducible pipeline would include:
​

Data ingestion and cleaning (e.g. pandas or Power Query).

EDA and visualisation (e.g. matplotlib, seaborn, Power BI, or Tableau).

Statistical modelling and hypothesis testing (e.g. scipy.stats, statsmodels, or R’s aov).
​

This project demonstrates the ability to move from raw operational data to statistically robust, management‑ready insight using replicable analytical methods.
