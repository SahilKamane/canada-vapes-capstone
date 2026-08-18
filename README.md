# Canada Vapes — Data Analytics Capstone

## Executive Summary

This capstone transformed Canada Vapes sales and customer data into business-focused insights about sales growth, customer value, regional opportunity, and Average Order Value (AOV).

The team used Python/pandas for data preparation and validation and Power BI for dashboarding and business storytelling. The final analysis validated 177,142 completed positive-value orders, $18.17M in completed net sales, 22,569 identifiable customers, and a weighted order-level AOV of $102.59. The supplied forecast reaches approximately $8.0M in net sales by 2028.

> **Portfolio note:** Original client datasets and proprietary source files are not included in this public repository.

## Business Problem

The project examined:
- sales, orders, and AOV trends
- future growth
- new versus returning customer value
- regional opportunity
- progress toward the $120 AOV target
- privacy, governance, and responsible-marketing considerations

## My Role — Visualization & QA Lead

My documented team role was **Visualization & QA Lead**.

Responsibilities included:
- assessing data quality
- developing the Power BI dashboard prototype
- creating charts and visualizations
- supporting dashboard development
- coordinating quality-assurance reviews
- assisting with report formatting
- developing presentation materials

## Tools

- Python
- pandas
- Microsoft Power BI
- Microsoft Word
- PowerPoint

## Analytical Workflow

1. Loaded and standardized 181,641 transaction rows.
2. Retained completed positive-value purchases, producing 177,142 valid orders.
3. Calculated sales, AOV, items/order, coupon rate, customer type, and purchase frequency.
4. Built descriptive customer planning segments.
5. Aggregated the monthly forecast into annual results.
6. Analyzed the regional customer dataset separately because no validated shared customer/region key was available.
7. Used Power BI to communicate KPIs, trends, forecasts, and regional opportunities.

## Key Results

| KPI | Result |
|---|---:|
| Completed net sales | **$18,173,726** |
| Completed orders | **177,142** |
| Weighted order AOV | **$102.59** |
| Identifiable customers | **22,569** |
| Repeat customer rate | **57.2%** |
| Returning-customer order AOV | **$112.96** |
| New-customer order AOV | **$75.50** |
| 2021–2025 sales CAGR | **27.9%** |
| 2028 forecast net sales | **$7,998,665** |

## Key Insights

### Customer value
Repeat customers represented 57.2% of identifiable customers and 95.9% of completed net sales in the reported analysis period. Returning-customer order AOV was $112.96 versus $75.50 for new customers.

### AOV opportunity
The validated weighted order-level AOV was $102.59 against the $120 target. The project also identified several AOV measures calculated at different analytical grains, leading to a recommendation for a governed metric dictionary.

### Regional opportunity
Ontario and Quebec received the highest priority scores in the regional dashboard, while Nova Scotia and British Columbia were classified as pilot/expand opportunities.

## Power BI Dashboard

The dashboard covers:
- regional AOV versus the $120 target
- historical and three-year AOV forecast
- addressable next-order gap
- regional priority scores
- regional reach versus AOV-growth difficulty
- active customer mix

## Data Quality & QA

A major QA finding was that AOV values differed across dashboards because they were calculated at different grains:

- Weighted completed-order AOV: $102.59
- Executive dashboard AOV: $101.84
- Regional dashboard AOV: $101.62
- Mean customer AOV: $100.50
- Median customer AOV: $84.73

The project recommended clearly defining each metric's analytical grain and reconciling Power BI and Python outputs before management uses the measures.

## Ethics, Privacy & Governance

The project addressed confidentiality, purpose limitation, data minimization, secure storage, aggregated reporting, data lineage, regional bias, age-eligibility checks, responsible marketing, and avoiding unsupported ROI/profit claims.

## Limitations

- The transaction dataset did not contain a region field.
- Product descriptions were not fully standardized.
- Product cost, campaign cost, shipping, payment fees, and profit-margin data were unavailable.
- Forecast methodology and accuracy metadata were unavailable.
- Historical customer segments were descriptive rather than predictive.
- Age-eligibility information was not present in the analytical dataset.

## Recommendations

The final project recommended:
1. establishing one governed AOV and growth scorecard
2. protecting the existing high-value customer base
3. improving first-to-second purchase conversion
4. using basket-building approaches rather than broad discounting
5. piloting regional tactics before scaling
6. adding cost/margin information before profit or ROI claims
7. maintaining privacy, age-eligibility, responsible-marketing, and audit controls

## Repository Structure

```text
canada-vapes-capstone/
├── README.md
├── analysis/
├── dashboard/
├── data/
├── documentation/
├── presentation/
└── report/
```

The raw client dataset and original proprietary files should not be uploaded publicly without explicit authorization.

