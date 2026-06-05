# Task-4-Waliyullahi-Akorede-Husain
Repository for Task 4

# Internship Diary: Project 4 – Business Intelligence Dashboarding

## Project Overview
Following the exploratory query phase in Excel and SQL, I advanced to Power BI for Project 4 to build an interactive, three-page executive reporting dashboard. By creating clear relational data paths, I was able to isolate exactly which operational and marketing channels are driving our $1.26M gross sales and, more importantly, track down the exact mechanisms causing financial loss.

---

## Tools Used & Methodology
* **Power BI Desktop:** Used for data modeling and interactive report design.
* **DAX (Data Analysis Expressions):** Formulated custom measures and dynamic categorical binning for behavioral mapping.

---

## Key Business Insights

### 1. Gross Revenue & Net Revenue Leakage 
High-level summary cards initially showed an spectacular Gross Revenue of $1.26M. However, breaking down metrics across interactive data paths revealed a severe operational bottleneck:
* Actual cash kept in the bank (**Net Revenue** from Delivered & Shipped orders) sat at just $488.8K.
* A staggering **$775K** was lost to cash leakage driven by a 20.8% Cancellation Rate, a 20.6% Return Rate, and a 19.8% Pending Fulfillment Rate.
* The WINTER15 coupon campaign drives the highest absolute cancellations, while full-price (NO COUPON) orders trigger the most returns possibly due to post-purchase buyer's remorse.

### 2. High-Value Carts vs. Low Customer Retention
* Large carts (7+ items) appeared highly profitable, bringing in 44.64% of total sales volume.
* Large carts drive the highest absolute sales volume, but they also represent the highest financial loss when an order goes sideways.
* The dashboard shows a completely flat customer purchase frequency of **1.0**, meaning practically everyone buys a high-value cart once and walks away.

### 3. False Revenue Collapse in the Third Year
An evaluation of the annual trend card displays a terrifying 50% drop-off in total revenue for the year 2025. 
* By cross-referencing this drop-off with the Monthly Sales Trend line chart, I once again confirmed the root cause behind the trend.
* Sales volume climbs to a massive peak in June 2025 and then plummets straight to zero for July through December. 
* The business isn't failing, the data collection for the year just didn't cover the full 12 months. It stopped abruptly at June, which mathematically explains the artificial drop-off and the unusual cancellation metrics for 2025.

---

## 🤖 The Nearly Uniform Distribution
A basic dashboard report would rush to aggressively fund Chairs, Instagram, or FREESHIP coupons since they appeared to be the top revenue drivers. However, interactive cross-filtering exposed a highly uniform, near-perfect split across multiple variables:
* Sales volume and revenue across seven totally different product categories look visually flat and uniform, leaving little difference between a bulky Chair and a Phone.
* Marketing coupons and referral sources segment into nearly identical percentage parts across the board.

---

## Recommendations

*  **I.** Since Chairs, Printers, and Phones all bring in roughly the same gross revenue due to the uniform split, stocking and selling the items that are the cheapest to warehouse and easiest to ship (like Phones over bulky Desk`) should be prioritized to maximize net profit margins.
*  **II.** Since discount codes split evenly and do not drastically shift sales volume, the ones causing operational problems should be eliminated. WINTER15 should be discontinued and the highly successful FREESHIP code should be standardized to reduce checkout complexity and buyer's remorse.
*  **III.** Because the company suffers from a flat customer purchase frequency of 1.0, marketing focus should move toward structured customer loyalty programs to actively turn one-time buyers into repeat customers.
*  **IV.** Large carts drive the bulk of sales volume but carry a massive **$121.6K cancellation leak**. Implementing an automated verification hold for any cart containing 4+ items before it leaves the warehouse floor will proactively safeguard that at-risk capital.
*  **V.** The Monthly Sales Trend chart proves that demand spikes heavily in June. Knowing that mid-year is peak sales season, the business should optimize its supply chain and stock up aggressively in Q1 and Q2 to handle big sales volume.

---

## Conclusion

This project highlighted that high gross revenue can often mask severe operational inefficiencies. By moving beyond superficial metrics in Power BI, this analysis successfully separated surface-level noise from actionable business realities.
