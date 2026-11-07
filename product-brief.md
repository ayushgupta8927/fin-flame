# FinFlame Product Brief

A product-style write-up of the FinFlame report: who it is for, what it covers, how a user moves through it and what was still to come. It is based on screenshots of a local build captured on 23 December 2025, using sample data. It describes what the product shows and leaves out how scores are calculated, which is proprietary.

Back to the [README](../README.md).

## 1. Summary

FinFlame is a report for food-service MSMEs that sell through delivery platforms such as Swiggy and Zomato. It turns a restaurant's sales and operations data into a credit view (score and indicative loan ranges) and a business health view (metrics, strengths, challenges and an action plan).

## 2. Problem and opportunity

- A delivery-platform restaurant generates detailed data about its own business, but the data sits in dashboards that are built for operations, not for judging financial health.
- Owners find it hard to see which numbers matter and what to do about them.
- Lenders have little structured, comparable information about small restaurants.

The opportunity is one report that reads the data for the owner and speaks to both needs: "How healthy is my business?" and "How much could I borrow?"

## 3. Users and what they need

| User | Need | Where the report answers it |
|---|---|---|
| Restaurant owner or operator | Understand how the business is doing | Headline numbers, sales trends, business performance insights |
| Restaurant owner or operator | Know what to fix first | Strengths and challenges, action plan with reversal probability |
| Restaurant owner or operator | See borrowing capacity | Scorecard and loan eligibility by tenor |
| Lending partner (indirect) | A structured view of a small restaurant | Scorecard parameters, financial discipline metrics |

## 4. Scope: what the report covers

| Area | What it shows | Status in the screenshots |
|---|---|---|
| Filters | Date range, channel, days, time slots, cuisine, order type, reset | Shown |
| Headline numbers | Orders, gross sales, net sales, average order value, cancellation, rating, repeat share | Shown |
| Open-hour ROI | Return on operating hours | Coming soon |
| Credit scorecard | Overall score and five parameter scores | Shown (one parameter coming soon) |
| Loan eligibility | Indicative ranges for 3, 6, 12 and 24 months | Shown |
| Sales trends | Net sales, orders, average order value by month and by quarter | Shown |
| Customer rating trend | Rating over time | Coming soon |
| Business performance insights | Six metric groups (see section 5) | Shown, some metrics N/A |
| Demand pattern | Orders by day and meal slot, slot or hourly view | Shown |
| Operating Hours Optimizer | Suggested operating hours | Coming soon |
| Pricing and discount discipline | Discount against net sales, discount tiles | Shown |
| Product mix and concentration | Top ten items by revenue, concentration warning | Shown |
| Complaints deep dive | Complaint share by reason, main drivers flagged | Shown |
| Order fulfilment | Fulfilment rate against cancellations | Shown |
| Customer retention | New against repeat, 30, 60 and 90 day cohorts | Shown |
| Kitchen operations | Preparation time, uptime, stockouts | Coming soon |
| Strengths and challenges | Core competencies and main challenges | Shown |
| Action plan | Actions per problem with reversal probability | Shown |
| Action Playbook | Real-time metrics and actions | Coming soon |

## 5. Metric catalogue

Metrics are grouped by theme. In the sample report, a metric with no data shows N/A.

| Group | Metrics | In the sample |
|---|---|---|
| Growth Momentum | MoM revenue growth %, QoQ revenue growth %, monthly revenue stability, business vintage | All four have values |
| Business Efficiency | Cash to sales ratio %, cancellation rate, order fulfilment rate, buyer concentration | Buyer concentration is N/A |
| Customer Engagement | Repeat order rate %, unique customer growth %, 30-day repeat rate, 90-day repeat rate | 30-day and 90-day repeat rates are N/A |
| Channel Performance | Platform rating, funnel conversion, ad efficiency (GMV), ad efficiency (orders) | All four have values |
| Financial Discipline | Average days past due (DPD), maximum DPD, unsecured enquiries, entity 30+ DPD | All N/A |
| Digital Footprint | Digital engagement score (active days per week) | N/A |

### Scorecard parameters

1. Business Stability and Growth
2. Operational Efficiency
3. Customer Stickiness and Retention
4. Digital and Platform
5. Creditworthiness and Compliance (coming soon)

## 6. User flow

1. **Set the view.** Choose a date range and, if needed, channel, days, slots, cuisine and order type.
2. **Read the headline numbers.** Orders, sales, order value, cancellations, rating and repeat share give a first impression.
3. **Check the credit view.** See the overall score, which parameters pull it up or down, and the indicative loan ranges.
4. **Understand the trend.** Review sales, orders and order value by month and quarter.
5. **Find the cause.** Use the metric groups, demand heatmap, pricing, product mix, complaints and retention panels.
6. **See strengths and challenges.** The report names what the restaurant does well and where it struggles.
7. **Act.** Follow the action plan, starting with the actions tagged High.

## 7. Action plan (as shown in the sample)

Each challenge breaks into problems. Each problem has a short list of actions and a reversal probability.

| Challenge | Problem | Example actions | Reversal probability |
|---|---|---|---|
| Inconsistent sales | Inconsistent sales growth | Loyalty programme, higher order value through upselling and bundling, subscription model | High |
| Inconsistent sales | High discount dependency | Tiered discounts by order value, margin-based discounting | Medium |
| Breaking funnel | Impression to menu drop | Better menu visibility, layout and photo tests, item names based on search trends, clearer descriptions | High |
| Breaking funnel | Menu to cart drop | Cart-exclusive offers, cart-level upsell nudges, one-click reordering | Medium |
| Declining ads ROI | Declining ROI on ad spend | Rebalance ad budgets, focus on high-conversion placements, keyword analysis | High |
| Declining ads ROI | Target segment misalignment | Test creative formats, optimise ad delivery by time slot | Medium |
| Skewed demand pattern | Low weekend sales | Weekend menus and family bundles, weekend offers, happy-hour campaigns | Medium |
| Skewed demand pattern | Low breakfast and late-night sales | Breakfast and late-night products, adjusted operating hours | High |

The recommendations that appear depend on the restaurant's own data, so a restaurant sees only the challenges that apply to it.

## 8. Product principles

- **Honest about gaps.** "N/A" and "Coming soon" appear instead of invented numbers.
- **Honest about confidence.** Loan ranges are indicative and subject to underwriting. The report carries a beta disclaimer saying insights are based only on the data provided.
- **Every problem has a next step.** Actions are ranked so the owner starts where effort is most likely to pay off.
- **Status is visible at a glance.** Colour separates strengths, challenges and complaints.
- **The owner controls the view.** Filters apply across the report.

## 9. Edge cases the report handles

- Metrics with no data show N/A and an empty bar.
- Sections that depend on data not yet connected show a Coming soon state with a short explanation.
- Missing parameters in the scorecard are labelled instead of being left out.

## 10. Questions to answer next

These are the questions I would take up as the next step for a product like this:

1. Which data sources would fill the Financial Discipline and Digital Footprint metrics, and what would it take to connect them?
2. How would we know whether a recommended action worked? A follow-up view of the metric after the owner acts would close the loop.
3. Do owners understand why the score is what it is? Plain-language reasons next to each parameter would help.
4. How should loan ranges be explained so that owners do not read them as an offer?

## Glossary

| Term | Meaning |
|---|---|
| MSME | Micro, small and medium enterprise |
| AOV | Average order value |
| GMV | Gross merchandise value |
| MoM, QoQ | Month on month, quarter on quarter |
| DPD | Days past due |
| KPT | Kitchen preparation time |
| SKU | A single sellable item |
| Tenor | The length of a loan |
| Underwriting | A lender's review before approving a loan |
