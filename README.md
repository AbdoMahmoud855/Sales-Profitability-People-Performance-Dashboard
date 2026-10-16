# 📊 Sales, Profitability & People Performance Dashboard (Power BI)

An interactive Power BI dashboard that tells the story of **402 customers, 19 employees and 8K orders** between **2013 and Q2 2016**, generating **$19.88M in sales** at a **49.92% profit margin**. Instead of staring at tables, the dashboard answers real questions: Where does the money come from? What actually drives profit up or down? Who are our best customers and employees? And is the business still growing?

> ⏱️ **Data range:** 2013 → **end of Q2 2016** (January–June). 2016 is a **partial year**, so every "2016 drop" in this report is read with that in mind. See [Reading 2016 Correctly](#-reading-2016-correctly).

<img width="1370" height="749" alt="image" src="https://github.com/user-attachments/assets/ce3e8c7a-6d28-46d7-b8a5-472ed774f8d6" />



---

## 🗂️ Project Contents

| File | Description |
|---|---|
| `[FileName].pbix` | The complete Power BI report |
| ↳ **Sales & Business Performance** | Page 1: overview (KPIs, yearly trend, cities, products, orders) |
| ↳ **What Drives Sales Profitability** | Page 2: AI-driven analysis of what moves profit (Key Influencers + Top Segments) |
| ↳ **Customer & Employee Performance** | Page 3: customers, employees and their profit contribution |
| `images/` | Dashboard screenshots |
| `data/` | The dataset |

---

## ❓ Questions This Dashboard Answers

### Page 1: Sales & Business Performance

**KPI cards:** *"Where do we stand right now?"*
- **$19.88M** total sales across **8K orders** and **1M units**.
- A **49.92%** profit margin, which is strong and stable across the years.
- **13.93%** sales growth.

| Chart | Question | Short Answer |
|---|---|---|
| TotalSales and totalprofit per year (line) | Is the business growing? | Yes from 2013 to 2015 (sales $5.3M → $6.3M, profit $2.6M → $3.2M). 2016 covers only half a year (H1). |
| Top 5 City per Profit (column) | Which cities make the most profit? | Akhiok leads with $259.55K, then San Jacinto $185.16K and Meadowdale $176.75K. |
| Performance Sales & Cost by Year (matrix) | Is growth healthy, and is cost under control? | Sales grew +11.1% in 2014 and +8.6% in 2015; cost stays at about 50% of sales every year. |
| Top 10 Product per Sales (bar) | Which products sell the most? | Air cushion machine (Blue) at $1.198M, followed by bubble-wrap and packaging products. |
| Total Orders per Sales by Year (combo) | Do orders and sales move together? | Yes. Orders 2,210 → 2,400 → 2,571, then 1,007 in H1 2016. |
| Number of Sales Employee (pie) | How many sales records are profitable? | 97.86% Profit vs 2.14% Loss. |

### Page 2: What Drives Sales Profitability

| View | Question | Short Answer |
|---|---|---|
| Key Influencers: Decrease | What makes profit go down? | A fall in Total Excluding Tax of 1,473.82 (avg profit −751), and low unit prices (12–16: −413.4, ≤12: −240.9). |
| Scatter plot | How does order value relate to profit? | Strong positive relationship: bigger Total Excluding Tax means higher average profit. |
| Top Segments: Low | Which groups earn the least? | 7 segments found; average profit from 19.42 up to 181.9. |
| Top Segments: High | Which groups earn the most? | 4 segments; average profit from 489.3 up to 2.93K. |

### Page 3: Customer & Employee Performance

| Chart | Question | Short Answer |
|---|---|---|
| KPI cards | How big are the customer base and the team? | 402 customers, 19 employees, 12.19% Customer Purchase, 46.92% Employee Active. |
| Count of Customer per Year (area) | How does customer activity evolve? | 7.1K → 7.7K → 8.3K, then 3.3K in H1 2016 (partial year). |
| Top 5 Less Customer by Sales | Which customers are at the lower end of sales? | Between $170K and $223K, a tight range. |
| Top 10 Customer by Number of Orders | Who orders the most? | "Unknown" with 2,842 orders, then Wingtip Toys (Kapa'a, HI) with 132. |
| Sales Employee by Profit Status (bar) | Are employees profitable? | Every employee shows overwhelmingly profit, with minimal loss. |
| Top 5 Less Employee per Sales | Is the lower end of the team far behind? | No: $1.79M–$1.98M, a narrow gap. |
| Top 10 Employee by Profit (table) | Who contributes the most profit? | Sophia Hinton ($1.088M), Lily Code ($1.049M), Kayla Woodcock ($1.027M). |

### Questions That Emerge From Combining Charts
- **Is cost under control?** Yes. Cost stays at roughly 50% of sales every year, so profit simply follows sales.
- **Is 2016 really a collapse?** Not by itself: it is a half year. The monthly run-rate is still lower than 2015, which needs validation (see below).
- **Are we dependent on a few products?** The top 10 products make about **$6.5M (≈ 33% of sales)**, and almost all are packaging materials.
- **Does profit depend on a few cities?** No. The top 5 cities together hold only about **10% of total profit**, so profit is spread widely.
- **Do we depend on a star employee or customer?** No. The top 5 employees are within about 8% of each other, and the top customers sit between 126 and 132 orders.

> 💡 The slicers let you ask any of these questions for a specific slice, for example: *"What does the picture look like for a single brand in a specific month, loss-making records only?"*

---

## 📅 Reading 2016 Correctly

The data ends in **Q2 2016**, so 2016 holds only **6 months**. Comparing it directly to a full year is misleading. A fairer first look uses a monthly average:

| Year | Months | Sales | Avg Sales / Month | Orders | Avg Orders / Month |
|---|---|---|---|---|---|
| 2013 | 12 | $5.26M | ≈ $0.44M | 2,210 | ≈ 184 |
| 2014 | 12 | $5.84M | ≈ $0.49M | 2,400 | ≈ 200 |
| 2015 | 12 | $6.35M | ≈ $0.53M | 2,571 | ≈ 214 |
| **2016 (H1)** | **6** | **$2.43M** | **≈ $0.41M** | **1,007** | **≈ 168** |

**What it means:** even after correcting for the shorter period, the 2016 monthly average is **about 23% below 2015** for sales and about 21% below for orders. This is a *rough* comparison and ignores seasonality. The proper check is **H1 2016 vs H1 2015** using the Month slicer. Until then, treat it as a *possible slowdown to investigate*, not a confirmed decline.

---

## 🎨 Dashboard Design

A dark navy and orange theme keeps the numbers in focus and gives all three pages one identity.

| Role | Color | Where it's used |
|---|---|---|
| Header banner, filter panel, KPI cards, table headers | Navy `#111827` | Title bar, left filters, KPI blocks |
| Primary data color | Orange `#FF9900` | Bars, lines, KPI labels, buttons |
| Area fill | Light orange `#FFD699` | Area chart |
| Loss / negative | Dark blue `#1F3A5F` | Loss legend and pie slice |
| Page background | Light grey `#F3F4F6` | Canvas behind the cards |
| Cards | White `#FFFFFF` | All chart containers |
| Secondary text | Gray `#4B5563` | Axis labels |

### Navigation
- **Page 1 → Page 2:** orange arrow at the bottom-right.
- **Page 2 → Page 1:** back arrow at the top-left.
- **Page 1 ↔ Page 3:** the orange header button switches between *Sales & Business* and *Customer & Employee*.

### 🎛️ Filters (Slicers), Left Side
| Slicer | Purpose |
|---|---|
| Month | Zoom in on a specific month (useful for H1 vs H1 comparisons) |
| Brand | Compare brands |
| Profitstatus | Profit vs Loss records |

---

## 📄 Page 1: Sales & Business Performance

<img width="1370" height="749" alt="image" src="https://github.com/user-attachments/assets/95374d7c-54e9-4917-807e-543a2ac5bc19" />


### 🔢 Part 1: KPI Cards
**The story:** In five seconds the cards say "where we stand".

| Card | Value | The Story |
|---|---|---|
| 💰 TotalSales | $19.88M | The scale of the business over 2013 – Q2 2016. |
| 🛒 Total Orders | 8K | About **$2.5K per order**, which looks like business-to-business buying. |
| 📦 Total Quantity | 1M | Roughly 125 units per order, so orders are large. |
| 📈 TotalSales Growth | 13.93% | Healthy growth. Document how it is calculated. |
| 💵 Profit Margin | 49.92% | Strong margin, consistent with cost at ~50% of sales. |

### 📈 Chart 1: TotalSales and totalprofit per Year
**Type:** Line chart · **Question:** Is the business growing?

| Year | Sales | Profit |
|---|---|---|
| 2013 | $5.3M | $2.6M |
| 2014 | $5.8M | $2.9M |
| 2015 | $6.3M | $3.2M |
| 2016 (H1) | $2.4M | $1.2M |

**The story:** Sales and profit rose together every full year. The two lines are almost parallel because margin is stable at ~50%.

**Takeaway:** 2016 is only half a year, so the visible "fall" is mostly the missing months. Use the monthly-average view in [Reading 2016 Correctly](#-reading-2016-correctly) to judge the real trend.

### 🏙️ Chart 2: Top 5 City per Profit
**Type:** Column chart · **Question:** Which cities make the most profit?

| City | Profit |
|---|---|
| Akhiok | $259.55K |
| San Jacinto | $185.16K |
| Meadowdale | $176.75K |
| Haycock | $168.00K |
| Fieldbrook | $163.72K |

**The story:** Akhiok clearly leads, about 40% above the second city. Yet the five cities together hold only **≈ 10% of total profit (~$0.95M of ~$9.9M)**.

**Takeaway:** Profit is spread across many cities. There is no single-city dependency, and also no obvious "hub" beyond Akhiok worth studying and copying.

### 📋 Chart 3: Performance Sales & Cost by Year
**Type:** Matrix · **Question:** Is growth healthy and cost under control?

| Year | Total Sales | Previous Year | Cost | Cost % of Sales |
|---|---|---|---|---|
| 2013 | $5,257,949 | none | $2,620,208 | 49.8% |
| 2014 | $5,843,430 | $5,257,949 | $2,935,372 | 50.2% |
| 2015 | $6,347,853 | $5,843,430 | $3,185,771 | 50.2% |
| 2016 (H1) | $2,430,357 | $6,347,853 | $1,214,346 | 50.0% |

**The story:** Sales grew **+11.1%** (2014) and **+8.6%** (2015). Cost stays locked at about half of sales, so margin does not move.

**Takeaway:** Growth slowed from 11.1% to 8.6% even before 2016. The 2016 red arrow compares a *half year* with a *full year*, so it should be read with that in mind.

### 🛍️ Chart 4: Top 10 Product per Sales
**Type:** Bar chart · **Question:** Which products sell the most?

| Rank | Product | Sales |
|---|---|---|
| 1 | Air cushion machine (Blue) | $1,198.27K |
| 2 | 10 mm Anti static bubble wrap (Blue) 50m | $866.25K |
| 3 | 20 mm Double sided bubble wrap 50m | $790.56K |
| 4 | 32 mm Anti static bubble wrap (Blue) 50m | $769.44K |
| 5 | 32 mm Anti static bubble wrap (Blue) 50m | $631.05K |
| 6 | 10 mm Double sided bubble wrap 50m | $605.85K |
| 7 | 20 mm Anti static bubble wrap (Blue) 50m | $587.52K |
| 8 | Void fill 400 L bag (White) 400L | $405.50K |
| 9 | 32 mm Anti static bubble wrap (Blue) 20m | $360.00K |
| 10 | 20 mm Anti static bubble wrap (Blue) 20m | $309.60K |

**The story:** The top 10 add up to about **$6.5M (≈ 33% of sales)**. Nine of ten are packaging materials, and the air cushion machine leads.

**Takeaway:** The business is anchored on packaging supplies. The machine on top also points to a cross-sell chain: *machine → consumables*.

### 🔁 Chart 5: Total Orders per Sales by Year
**Type:** Column + line combo · **Question:** Do orders and sales move together?

**The story:** Orders (2,210 → 2,400 → 2,571) and sales ($5.3M → $5.8M → $6.3M) rise together, so growth came from **more orders**, not bigger orders. In H1 2016 there are 1,007 orders and $2.4M.

**Takeaway:** If the average order value stayed flat, the lever for growth is order count. The Key Influencers page shows order value is also a profit driver, so both levers matter.

### 🥧 Chart 6: Number of Sales Employee (Profit vs Loss)
**Type:** Pie chart · **Question:** How much of the activity is profitable?

**The story:** **97.86%** profit vs **2.14%** loss.

**Takeaway:** Loss is small. The question is *which* 2.14% (see the Profitstatus slicer), since it may be a small, fixable pocket.

---

## 📄 Page 2: What Drives Sales Profitability
##  Increas
<img width="1345" height="753" alt="image" src="https://github.com/user-attachments/assets/c83cc4ea-4d5e-4d18-8165-82a901b6ced3" />
<img width="1348" height="752" alt="image" src="https://github.com/user-attachments/assets/af2928dd-f56d-4867-a9b4-05653342d363" />

##  Decrease
<img width="1339" height="754" alt="image" src="https://github.com/user-attachments/assets/4462d207-9299-4316-b17e-2a25f693a61f" />
<img width="1342" height="741" alt="image" src="https://github.com/user-attachments/assets/2c9e9446-0978-4eb4-8d17-2e9e00e18109" />

### ⬇️ Key Influencers: What Decreases Profit?

| Condition | Average Profit Decrease |
|---|---|
| Sum of Total Excluding Tax goes down by 1,473.82 | **−751** ⚠️ |
| Sum of Unit Price is 12 – 16 | −413.4 |
| Sum of Unit Price is 12 or less | −240.9 |

**The story:** Profit is tied to order value more than anything else. Low unit prices also pull profit down.

### 🔵 Scatter Plot: Total Excluding Tax vs Average Profit
**The story:** The trend is clearly linear: as order value rises, average profit rises almost proportionally. A few points sit far above the line (up to 9K profit at ~11K order value), and those are the best deals.

**Takeaway:** Bigger deals are not just more revenue; they are more profitable *per deal*. The sales effort should push customers toward bigger baskets.

### 🎯 Top Segments

**Low-profit view (7 segments found, 6 shown)**

| Segment | Average Profit | Population |
|---|---|---|
| Segment 1 | 19.42 | 3,702 |
| Segment 2 | 42.91 | 2,131 |
| Segment 3 | 61.78 | 2,774 |
| Segment 4 | 91.51 | 4,005 |
| Segment 5 | 131.8 | 2,137 |
| Segment 6 | 181.9 | 1,652 |

**High-profit view (4 segments)**

| Segment | Average Profit | Population |
|---|---|---|
| Segment 1 | 2.93K | 1,283 |
| Segment 2 | 926.8 | 2,394 |
| Segment 3 | 641.4 | 1,571 |
| Segment 4 | 489.3 | 1,303 |

**The story:** The gap is huge. The best segment earns about **150× more per record** than the weakest (2,930 ÷ 19.42), with a **smaller** population (1,283 vs 3,702).

**Takeaway:** A small group of records produces most of the profit. Finding what defines Segment 1 (high view) and repeating it is the biggest profit lever in the dashboard.

---

## 📄 Page 3: Customer & Employee Performance

<img width="1372" height="740" alt="image" src="https://github.com/user-attachments/assets/2b9da6d9-b950-4654-a09a-09293aa8e3bc" />


### 🔢 KPI Cards
| Card | Value | The Story |
|---|---|---|
| 👥 Number of Customers | 402 | A small, concentrated customer base. |
| 🧑‍💼 Count of Employees | 19 | Team size. |
| 🛒 Customer Purchase | 12.19% | Define clearly (e.g., share of customers who purchase in a period). |
| ✅ Employee Active | 46.92% | Fewer than half the team is "active", so check how it is defined. |

### 👥 Customers

| Chart | Finding |
|---|---|
| Count of Customer per Year | 7.1K → 7.7K → 8.3K → 3.3K (H1 2016). Follows the same shape as sales. |
| Top 5 Less Customer by Sales | $223K, $218K, $213K, $183K, $170K (Tailspin/Wingtip Toys branches in AK, OR, CA). |
| Top 10 Customer by Number of Orders | Unknown 2,842 · Wingtip Toys (Kapa'a, HI) 132 · Tailspin Toys (Fieldbrook, CA) 130 · Wingtip Toys (Salt Wells, NV) 129 · Tailspin Toys (Kwethluk, AK) 126 · Tailspin Toys (Sekiu, WA) 126 |

**The story:** Named customers are very even (126–132 orders), so no single account dominates. The exception is **"Unknown" with 2,842 orders**, roughly **a third of all orders** with no customer identity.

**Takeaway:** The customer base is well balanced, but one-third of the orders cannot be tied to a customer, so retention and targeting analysis is blind for that part.

### 🧑‍💼 Employees

| Employee | Total Orders | Total Profit | Total Sales | Sales / Order | Profit / Order |
|---|---|---|---|---|---|
| Sophia Hinton | 832 | $1,087,989.90 | $2,219,626 | **$2,668** | **$1,308** |
| Lily Code | 850 | $1,048,804.05 | $2,112,720 | $2,486 | $1,234 |
| Kayla Woodcock | 831 | $1,027,053.50 | $2,081,322 | $2,505 | $1,236 |
| Archer Lamble | 817 | $1,010,010.10 | $2,005,041 | $2,454 | $1,236 |
| Taj Shand | 795 | $1,005,794.15 | $2,008,876 | $2,527 | $1,265 |

**The story:** The team is very balanced (top 5 within about 8% on profit). **Sophia Hinton** leads even though **Lily Code** handles more orders, because Sophia's average order is larger ($2,668 vs $2,486). This matches the Key Influencers finding: **order value matters more than order count**.

**Takeaway:** The winning habit is *bigger orders*, not *more orders*. Sophia's approach is worth studying and sharing. The lower end of the team ($1.79M–$1.98M in sales, e.g., Jack Potter) is not far behind, so coaching can lift the whole team.

---

## 🧩 The Whole Story in 6 Sentences

1. The company sells **$19.88M** across 8K orders with a strong **49.92%** margin that stays stable because cost is always about 50% of sales.
2. Sales grew every full year (+11.1% in 2014, +8.6% in 2015), though the growth rate is slowing.
3. The data stops at **Q2 2016**, so the 2016 "drop" is mostly missing months, but the monthly run-rate is still about 23% below 2015 and needs validation.
4. **Order value drives profit:** falling order value cuts profit most, low unit prices hurt, and the best segment earns ~150× more per record than the weakest.
5. The business is anchored on packaging products (top 10 ≈ 33% of sales), while profit is widely spread across cities, customers and employees.
6. About **one-third of orders have an "Unknown" customer**, and the best employee wins through **bigger orders**, not more orders.

---

## 🧭 Solution Strategy & Tactics

> **Purpose of this section:** when the dashboard reveals a problem, the data owner needs a solution they can **accept without conflicting with company strategy**. Each proposal below follows one pattern: **Problem (with evidence) → Proposed solution → Safe tactic (small pilot) → Why it fits the strategy → How we prove it worked.**

### 🏢 Company Strategy Assumed From the Data
These are inferred from the numbers, **not confirmed**. Check them with the data owner before presenting.

1. **Protect the strong margin** (≈ 50%, stable every year).
2. **Keep growing order volume** (sales grew +11.1% and +8.6% in the full years).
3. **Stay anchored on the packaging product line** (top 10 products ≈ 33% of sales).
4. **Keep a balanced base** of many customers and a team of similar performance.

Every solution below is designed to **stay inside these four lines**: no across-the-board price increase, no change to the core products, no restriction on customers, no team restructuring.

### 🧩 Problem → Solution → Tactic

#### 1. Possible slowdown in 2016 📉
| | |
|---|---|
| **Problem & evidence** | The data stops at Q2 2016, but the monthly average (~$0.41M) is still below 2015 (~$0.53M), and orders per month are ~168 vs ~214. |
| **Proposed solution** | **Validate before acting.** Do not change anything until we know whether this is real. |
| **Tactic** | Compare Jan–Jun 2016 against Jan–Jun of each earlier year with the Month slicer. Drill by Brand and City to see where the drop concentrates. Add a "Data through June 2016" label on every page. |
| **Why it fits the strategy** | It changes nothing operationally. It is analysis only. |
| **Proof it worked** | H1-vs-H1 growth % is known and the cause (seasonality, brand, or city) is identified. |

#### 2. Order value drives profit, and small orders lose it 💰
| | |
|---|---|
| **Problem & evidence** | A fall in order value of 1,473.82 cuts average profit by **751**. The scatter shows profit rising almost in line with order value. |
| **Proposed solution** | **Encourage bigger baskets with incentives, not rules.** |
| **Tactic** | Pilot bundles (air cushion machine + matching wrap and void-fill) and a small benefit when an order crosses a value tier. Run it for 4 to 8 weeks on a subset of customers and compare with the rest. |
| **Why it fits the strategy** | It grows sales, uses existing products, and forces nothing on the customer. No minimum-order rule. |
| **Proof it worked** | Average order value (today ≈ $2.5K) and profit per order rise in the pilot group. |

#### 3. Low unit prices drag profit down 🏷️
| | |
|---|---|
| **Problem & evidence** | Unit price of 12–16 lowers average profit by **413.4**, and 12 or less by **240.9**. |
| **Proposed solution** | **Sell low-priced items as add-ons to higher-value orders** instead of alone. |
| **Tactic** | Select a small group of low-price products and attach them to the bundles from Problem 2. Review the price of only a few of these products, with a margin check before any change. |
| **Why it fits the strategy** | No general price increase, so volume and customer relationships are protected. |
| **Proof it worked** | Profit per unit on these products, and the share of orders that contain only low-price items. |

#### 4. Profit is concentrated in a small high-profit segment 🎯
| | |
|---|---|
| **Problem & evidence** | Top segment averages **2.93K** profit per record with 1,283 records. The weakest segment averages **19.42** with 3,702 records (~150× gap). |
| **Proposed solution** | **Find what defines the best segment and offer the same to similar customers.** |
| **Tactic** | Open the segment in the Top Segments visual and list its customers, products, and order sizes. Offer the same product mix to customers who resemble them. |
| **Why it fits the strategy** | It uses existing customers and products. No new market and no new risk. |
| **Proof it worked** | Share of records that fall in the high-profit segments increases. |

#### 5. About one-third of orders have no known customer 🔍
| | |
|---|---|
| **Problem & evidence** | "Unknown" has **2,842 orders**, roughly 35% of the total. Retention and targeting are blind for this part. |
| **Proposed solution** | **Find the cause first, then fix data capture going forward.** |
| **Tactic** | Check whether "Unknown" is a walk-in channel, a missing key, or a null replaced by a label. Then make the customer ID a required field for new orders. Analyze Unknown separately in the meantime. |
| **Why it fits the strategy** | It is an internal data-quality fix. The customer notices nothing. |
| **Proof it worked** | The "Unknown" share of orders falls month after month. |

#### 6. Dependence on one product family 🧱
| | |
|---|---|
| **Problem & evidence** | The top 10 products ≈ **$6.5M (33% of sales)**, and nine of them are packaging materials. |
| **Proposed solution** | **Strengthen the core and grow around it** rather than replace it. |
| **Tactic** | Keep the top 10 always in stock, push consumables to every machine buyer, and promote products ranked 11 to 30 inside bundles. |
| **Why it fits the strategy** | It supports the packaging focus instead of moving away from it. |
| **Proof it worked** | Revenue from outside the top 10 increases while top-10 sales stay stable. |

#### 7. Employees win through order value, not order count 🧑‍💼
| | |
|---|---|
| **Problem & evidence** | Sophia Hinton earns more profit with fewer orders than Lily Code because her average order is larger ($2,668 vs $2,486). |
| **Proposed solution** | **Share the best practice across the team.** |
| **Tactic** | A short session where Sophia explains how she builds orders. Pilot profit-based recognition for one team before any wider change. |
| **Why it fits the strategy** | The team is already balanced (top 5 within ~8%), so no restructuring is needed. |
| **Proof it worked** | Average order value per employee moves closer to the top performer. |

#### 8. Metrics that are unclear or mislabeled 📋
| | |
|---|---|
| **Problem & evidence** | Growth 13.93%, Customer Purchase 12.19%, and Employee Active 46.92% have no documented definition. "Count of Customer per Year" shows 7K+ while customers total 402. |
| **Proposed solution** | **Document every measure and rename visuals to match what they count.** |
| **Tactic** | A one-page definitions sheet and corrected visual titles. |
| **Why it fits the strategy** | Zero cost and zero risk. |
| **Proof it worked** | Anyone reading the dashboard can say what each number means. |

### 🗣️ How to Present a Solution to the Data Owner

Use this sentence pattern:

> "We noticed **[problem]** (**[number from the dashboard]**). We suggest testing **[solution]** on **[small group]** for **[time period]**, **without changing [what the owner cares about]**. If **[metric]** improves, we expand. If not, we go back to how things were."

**Four rules that reduce pushback:**
1. **Lead with the number, not the opinion.** "Profit drops by 751" is stronger than "I feel orders are small."
2. **Offer a pilot, not a final decision.** Limited time and limited scope.
3. **Say what you will not change.** Core prices, core products, key customers.
4. **Ask for approval on one step,** not the whole plan.

### 🗓️ Implementation Roadmap

| Phase | Timeframe | Focus | Problems addressed |
|---|---|---|---|
| **Phase 1: Clarify** | 0 – 30 days | Validate numbers, no operational change | 1, 5 (audit only), 8 |
| **Phase 2: Pilot** | 30 – 90 days | Small, reversible tests | 2, 3, 4, 7 |
| **Phase 3: Scale** | 90 – 180 days | Expand only what the pilots proved | 5 (data entry), 6, and the winning pilots |

### ⚖️ Priority Matrix

| Problem | Impact | Effort | Risk to strategy | Priority |
|---|---|---|---|---|
| 1. Validate the 2016 slowdown | High | Low | None | 🥇 Start now |
| 8. Clarify metrics | Enabler | Low | None | 🥇 Start now |
| 5. Unknown customers | High | Medium | None | 🥈 Next |
| 2. Order value incentives | High | Medium | Low | 🥈 Next |
| 4. High-profit segments | High | Medium | Low | 🥈 Next |
| 3. Low unit prices | Medium | Low | Low | 🥈 Next |
| 7. Share best sales practice | Medium | Medium | Low | 🥉 Later |
| 6. Product concentration | Medium | High | Low | 🥉 Later |

### 📊 Success KPIs to Track on the Dashboard

| KPI | Today | Direction |
|---|---|---|
| Monthly sales run-rate (H1 2016) | ≈ $0.41M | ⬆️ Increase (vs ≈ $0.53M in 2015) |
| Average order value | ≈ $2.5K | ⬆️ Increase |
| Profit margin | 49.92% | ➡️ Hold or improve |
| Orders with "Unknown" customer | ≈ 2,842 | ⬇️ Decrease |
| Top-10 product share of sales | ≈ 33% | ⬇️ Gradually decrease |
| Employee Active | 46.92% | ⬆️ Increase |
| Loss share of records | 2.14% | ⬇️ Decrease |

> 📝 Targets should be set by the business after the Phase 1 baseline. Figures above are current values from the dashboard, and the directions are the recommended goals.

### ❓ Questions to Confirm With the Data Owner Before Presenting
1. Is protecting the ~50% margin the top priority, or is growth?
2. Are price changes allowed at all, or only incentives?
3. What does "Unknown" customer mean in your business?
4. How are Growth, Customer Purchase and Employee Active defined?
5. Is there any seasonality in the first half of the year?

### ⚠️ Risks to Watch

| Risk | Mitigation |
|---|---|
| Reading 2016 as a full year | Always show data coverage and compare H1 vs H1 |
| A pilot hurts customer relationships | Keep it small, time-limited, and reversible |
| Bundles lower the margin | Check margin per bundle before launch |
| Metric labels that don't match what is counted | Rename visuals and document each measure |
| Small samples in some segments | Check the population count before acting on a segment |

---

## 🧰 Tools Used
- **Power BI Desktop**
- **Power Query:** data cleaning and preparation `[add your steps]`
- **DAX measures:** Total Sales · Total Profit · Profit Margin · Sales Growth · Orders · Quantity `[add your measures]`
- **Data Modeling:** relationships between Sales, Customer, Employee, Product, City and Date `[add your model]`
- **AI Visuals:** Key Influencers · Top Segments
- **Dashboard design:** custom navy and orange theme, icons, slicers, navigation buttons

## 🚀 How to Use the Dashboard
1. Open `[FileName].pbix` in Power BI Desktop.
2. Use the slicers on the left (**Month**, **Brand**, **Profitstatus**) to filter the data.
3. Use the arrow at the bottom-right of Page 1 to open **What Drives Sales Profitability**, and the back arrow to return.
4. Use the orange header button to switch between **Sales & Business** and **Customer & Employee** pages.
5. On the profitability page, switch between **Key influencers** and **Top segments**, and change the dropdown (Decrease/Increase, Low/High) to see other angles.
6. To compare 2016 fairly, select **Month = Jan–Jun** and compare across years.
7. If you change the data: **Home → Refresh**.

---

⭐ If you like this dashboard, leave a star on the project!

