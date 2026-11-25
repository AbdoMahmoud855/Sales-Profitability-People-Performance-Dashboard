# 📊 Sales, Profitability & People Performance Dashboard (Power BI)

An interactive **three-page Power BI dashboard** that tells the story of **402 customers, 19 employees and 8K orders**, generating **$19.88M in sales at a 49.92% profit margin**. Instead of staring at tables, the dashboard answers real questions: *Where does the money come from? What drives profit up or down? Who are the top customers and employees? Is the business still growing?*

**Data range:** January 2013 → May 2016. 2016 covers **five months only** (the Sales & Cost matrix shows Qtr 1 and Qtr 2, with Qtr 2 holding April and May), so every "2016 drop" in this report should be read with that in mind. See [Reading 2016 Correctly](#-reading-2016-correctly).

<img width="1194" height="660" alt="image" src="https://github.com/user-attachments/assets/9d52ed35-181e-4f20-b25f-c86a7823b068" />


---

## 🗂️ Project Contents

| Item | Description |
|---|---|
| `[FileName].pbix` | The complete Power BI report |
| ↳ **Sales & Business Performance** | Page 1: KPIs, yearly trend, cities, products, orders |
| ↳ **What Drives Sales Profitability** | Page 2: Key Influencers and Top Segments |
| ↳ **Customer & Employee Performance** | Page 3: customers, employees and profit contribution |
| `images/` | Dashboard screenshots |
| `data/` | The dataset |

---

## ⚡ Key Findings at a Glance

- 📈 Sales grew **+11.1% in 2014** and **+8.6% in 2015**, and cost stayed at **about 50% of sales** every year.
- 📅 2016 (Jan–May) runs at **≈ $0.486M per month vs ≈ $0.529M in 2015 (≈ −8.1%)**, and Qtr 1 2016 is **≈ 8.5% below Qtr 1 2015**.
- 📦 The **top 10 products generate ≈ $6.52M (≈ 32.8% of total sales)**, and nine of them are packaging materials.
- 💎 **Unit price above 36** is the strongest profit influencer (**average profit +1.21K**).
- 📉 A **fall in Total Excluding Tax of 1,473.82** is the strongest profit decrease (**−751**).
- 🎯 The best high-profit segment averages **2.93K per record, ≈ 7.8× the overall average (375.9)**.
- ❓ **"Unknown"** customers account for **2,842 orders (≈ 34.7% of 8,188 orders)**.
- 🏆 **Sophia Hinton** earns the most profit **with fewer orders than Lily Code**, because her average order is larger.

---

## ❓ Questions This Dashboard Answers

<img width="1236" height="683" alt="image" src="https://github.com/user-attachments/assets/718e1fba-fb80-4a4a-b78a-1a131c4093fa" />

### Page 1 — Sales & Business Performance

| Chart | Question | Short Answer |
|---|---|---|
| TotalSales and totalprofit per year | Is the business growing? | Yes from 2013 to 2015 (sales $5.3M → $6.3M, profit $2.6M → $3.2M). 2016 is a partial year |
| Top 5 City per Profit | Which cities make the most profit? | Akhiok leads with $259.55K, then San Jacinto $185.16K and Meadowdale $176.75K |
| Performance Sales & Cost by Year | Is growth healthy and cost under control? | Sales +11.1% (2014) and +8.6% (2015); cost stays near 50% of sales |
| Top10 Product per Sales | Which products sell the most? | Air cushion machine (Blue) at $1,198.27K, followed by bubble-wrap and packaging products |
| Total Orders per Sales by Year | Do orders and sales move together? | Yes. Orders 2,210 → 2,400 → 2,571 and sales $5.3M → $5.8M → $6.3M |
| Profit vs Loss | How much of the activity is profitable? | 97.86% Profit vs 2.14% Loss |

### Page 2 — What Drives Sales Profitability
<img width="1361" height="708" alt="image" src="https://github.com/user-attachments/assets/1c9968f2-aa1a-44d0-88d3-6388d4248557" />
<img width="1261" height="714" alt="image" src="https://github.com/user-attachments/assets/db951aad-0181-4df6-a188-61516021880f" />

| View | Question | Short Answer |
|---|---|---|
| Key Influencers: Increase | What makes profit go up? | Unit Price above 36 (+1.21K), higher Total Excluding Tax (+751), Quantity 26–120 (+663.7) |
| Key Influencers: Decrease | What makes profit go down? | Lower Total Excluding Tax (−751) and low unit prices (12–16: −413.4, 12 or less: −240.9) |
| Scatter plot | How does order value relate to profit? | Positive relationship: higher Total Excluding Tax goes with higher average profit |
| Top Segments: High | Which groups earn the most? | 4 segments, average profit from 489.3 up to 2.93K |
| Top Segments: Low | Which groups earn the least? | Average profit from 19.42 up to 181.9 |

### Page 3 — Customer & Employee Performance

<img width="1205" height="680" alt="image" src="https://github.com/user-attachments/assets/01fa39bb-b90c-4e5d-a36e-5d4b61327d31" />


| Chart | Question | Short Answer |
|---|---|---|
| KPI cards | How big are the customer base and the team? | 402 customers, 19 employees |
| Count of Customer per Year | How does customer activity evolve? | 7.1K → 7.7K → 8.3K, then 3.3K in 2016 (partial year) |
| Top 5 Less Customer by Sales | Who is at the lower end of sales? | Between $170K and $223K |
| Top 10 Customer by Number of Orders | Who orders the most? | "Unknown" with 2,842 orders, then Wingtip Toys (Kapa'a, HI) with 132 |
| Sales Employee by Profit Status | Are employees profitable? | All employees show profit values between 2,462 and 2,749 |
| Top 5 less Employee per Sales | Is the lower end of the team far behind? | Between $1.79M and $1.98M |
| Top 10 Employee by Profit | Who contributes the most profit? | Sophia Hinton ($1.088M), Lily Code ($1.049M), Kayla Woodcock ($1.027M) |

---

## 📅 Reading 2016 Correctly

The data ends in **May 2016**, so 2016 holds five months. Comparing its total with a full year is misleading, so a monthly average is a fairer first look:

| Year | Months | Sales | Avg Sales / Month | Orders | Avg Orders / Month |
|---|---:|---:|---:|---:|---:|
| 2013 | 12 | $5.26M | ≈ $0.438M | 2,210 | ≈ 184 |
| 2014 | 12 | $5.84M | ≈ $0.487M | 2,400 | ≈ 200 |
| 2015 | 12 | $6.35M | ≈ $0.529M | 2,571 | ≈ 214 |
| 2016 | 5 | $2.43M | ≈ $0.486M | 1,007 | ≈ 201 |

- Monthly sales in 2016 are **≈ 8.1% below 2015** and orders **≈ 6.0% below**, but about level with the 2014 monthly pace.
- **Qtr 1** is the cleanest comparison (three months in both years): **$1,472,718 in 2016 vs $1,609,291 in 2015, ≈ −8.5%**.
- **Qtr 2 2016** has only April and May (**≈ $478.8K per month**), against a full Qtr 2 2015 (**≈ $534.6K per month**), which is ≈ −10.4% per month.
- Seasonality is not accounted for here. The like-for-like check is **Jan–May 2016 vs Jan–May 2015** with the Month slicer.

---

## 🎛️ Filters (Slicers) and Navigation

| Slicer | Purpose |
|---|---|
| Month | Filter by month (useful for comparing the same months across years) |
| Brand | Filter by brand |
| Profitstatus | Filter by profit status |

**Navigation:**
- Page 1 → Page 2: orange arrow at the bottom-right.
- Page 2 → Page 1: back arrow at the top-left.
- Page 1 ↔ Page 3: orange header button (*Customer&EmployeeDashboard* / *Sales&BusinesDashBoard*).

**Design:** a dark navy and orange theme shared by all pages, white chart cards, icon-based KPI cards and a left filter panel.

---

## 📄 Page 1 — Sales & Business Performance


<img width="1236" height="683" alt="image" src="https://github.com/user-attachments/assets/b28c84f8-4094-4efa-be0d-6c986dffb6ac" />


### 📖 Page Story

**The business at a glance.** Between 2013 and May 2016 the company generated **$19.88M** from **8K orders** at a **49.92% profit margin**. Sales climbed every full year, from $5.3M (2013) to $5.8M (2014) and $6.3M (2015), and profit followed the same path ($2.6M → $2.9M → $3.2M) because cost never moved away from about half of sales. Growth was real but slowing: **+11.1% in 2014**, then **+8.6% in 2015**.

**Where the money comes from.** Packaging. Nine of the top 10 products are packaging materials, led by the Air cushion machine ($1.198M), and together they bring in about a third of sales. Profit by city is spread out: Akhiok leads with $259.55K, yet the top 5 cities hold only about 10% of total profit.

**What happened in 2016.** The data stops at May, so 2016 holds five months ($2.43M in sales and 1,007 orders). Per month that is **≈ $0.486M vs ≈ $0.529M in 2015** and **≈ 201 orders vs ≈ 214**. Qtr 1 2016 ($1,472,718), a like-for-like quarter, is about **8.5% below** Qtr 1 2015 ($1,609,291).

**Bottom line.** A profitable, packaging-anchored business that grew steadily until 2015 and is running at a slightly lower monthly pace in early 2016.

### 🔢 KPI Cards

| KPI | Value |
|---|---:|
| 💰 TotalSales | **$19.88M** |
| 🛒 Total Orders | **8K** (8,188 when the yearly orders are added up) |
| 📦 Total Quantity | **1M** |
| 📈 TotalSalesGrowth | **13.93%** |
| 💵 Profit Margin | **49.92%** |

Average order value is about **$2,428** ($19.88M ÷ 8,188 orders).

### 📈 Chart 1 — TotalSales and totalprofit per Year
*Line chart*

| Year | Total Sales | Total Profit |
|---|---:|---:|
| 2013 | $5.3M | $2.6M |
| 2014 | $5.8M | $2.9M |
| 2015 | $6.3M | $3.2M |
| 2016 (Jan–May) | $2.4M | $1.2M |

**Insight:** Sales and profit rise together every full year, and the two lines run almost parallel because the margin is stable (profit is about half of sales each year). 2016 covers only January–May, so its lower values mostly reflect the seven missing months.

### 🏙️ Chart 2 — Top 5 City per Profit
*Column chart*

| City | Profit |
|---|---:|
| Akhiok | $259.55K |
| San Jacinto | $185.16K |
| Meadowdale | $176.75K |
| Haycock | $168.00K |
| Fieldbrook | $163.72K |

**Insight:** Akhiok is about **40% above** the second city. The five cities together hold about **$0.95M of ≈ $9.9M** total profit (roughly 10%), so profit is spread across many cities.

### 📋 Chart 3 — Performance Sales & Cost by Year
*Matrix with year → quarter drill-down and trend arrows*

| Year | Total Sales | Sales Previous Year | Cost | Cost % of Sales |
|---|---:|---:|---:|---:|
| 2013 | $5,257,949.00 | — | 2,620,208.10 | 49.8% |
| 2014 | $5,843,430.00 | $5,257,949 | 2,935,371.65 | 50.2% |
| 2015 | $6,347,853.00 | $5,843,430 | 3,185,771.25 | 50.2% |
| 2016 · Qtr 1 (Jan–Mar) | $1,472,718.00 | $1,609,291 | 727,136.20 | 49.4% |
| 2016 · Qtr 2 (Apr–May) | $957,639.00 | $1,603,760 | 487,210.10 | 50.9% |
| 2016 · Qtr 3 | — | $1,537,835 | — | — |
| 2016 · Qtr 4 | — | $1,596,967 | — | — |

**Insight:** Sales grew **+11.1% in 2014** and **+8.6% in 2015**, so growth was already slowing before 2016. Cost stays locked at about half of sales, so the margin does not move. The 2016 values add up to **$2,430,357 in sales** and **$1,214,346 in cost** (50.0%). Qtr 2 holds only April and May, so it should be compared per month, not against a full Qtr 2 of 2015.

### 🛍️ Chart 4 — Top10 Product per Sales
*Bar chart*

| Rank | Product | Sales |
|---:|---|---:|
| 1 | Air cushion machine (Blue) | $1,198.27K |
| 2 | 10 mm Anti static bubble wrap (Blue) 50m | $866.25K |
| 3 | 20 mm Double sided bubble wrap 50m | $790.56K |
| 4 | 32 mm Double sided bubble wrap 50m | $769.44K |
| 5 | 32 mm Anti static bubble wrap (Blue) 50m | $631.05K |
| 6 | 10 mm Anti static bubble wrap (Blue) 50m | $605.85K |
| 7 | 20 mm Anti static bubble wrap (Blue) 50m | $587.52K |
| 8 | Void fill 400 L bag (White) 400L | $405.50K |
| 9 | 32 mm Anti static bubble wrap (Blue) 20m | $360.00K |
| 10 | 20 mm Anti static bubble wrap (Blue) 20m | $309.60K |

**Insight:** The top 10 add up to about **$6.52M (≈ 32.8% of total sales)**. Nine of the ten are packaging materials, and the air cushion machine leads, which points to a machine → consumables relationship.

### 🔁 Chart 5 — Total Orders per Sales by Year
*Column + line combo chart*

| Year | Total Orders | Total Sales | Average Order Value |
|---|---:|---:|---:|
| 2013 | 2,210 | $5.3M | ≈ $2,379 |
| 2014 | 2,400 | $5.8M | ≈ $2,435 |
| 2015 | 2,571 | $6.3M | ≈ $2,469 |
| 2016 (Jan–May) | 1,007 | $2.4M | ≈ $2,413 |

**Insight:** Orders grew **+8.6% (2014)** and **+7.1% (2015)**, while sales grew faster (+11.1% and +8.6%). Growth therefore came mainly from more orders, with a small additional lift from higher average order value.

### 🥧 Chart 6 — Profit vs Loss
*Pie chart*

| Status | Share |
|---|---:|
| Profit | 97.86% |
| Loss | 2.14% |

**Insight:** Loss is a small share. The Profitstatus slicer can isolate the loss-making records.

---

## 📄 Page 2 — What Drives Sales Profitability

This page uses two Power BI AI visuals: **Key Influencers** (with an *Increase / Decrease* dropdown) and **Top Segments** (with a *High / Low* dropdown).
<img width="1289" height="715" alt="image" src="https://github.com/user-attachments/assets/28dd7c01-bfc8-4902-bf29-9a00d36eb890" />
<img width="1290" height="717" alt="image" src="https://github.com/user-attachments/assets/7fc505e1-3f65-4ceb-bbda-8298f396305c" />

### 📖 Page Story

**The question.** The margin is steady at about 50%, so what makes an individual sale more or less profitable?

**The answer starts with order value.** In Key Influencers, when Total Excluding Tax goes up by 1,473.82 the average profit rises by **751**, and when it goes down by the same amount it falls by **751**, a mirror image. The scatter plot confirms it: the points climb along a trend line from 0 to 20K.

**Price and quantity add detail.** A unit price above 36 is the strongest increase factor (**+1.21K**), and a quantity of 26–120 adds **663.7**. At the other end, unit prices of 12–16 (**−413.4**) and 12 or less (**−240.9**) pull profit down.

**Segments make the gap concrete.** Top Segments splits the records purely by order value. Orders above 2,560 form the best segment, with **2.93K average profit (≈ 7.8× the 375.9 overall average)** from only 4.9% of records. Orders of 60 or less form the weakest, with **19.42 average profit** across 14.0% of records.

**Bottom line.** Profit is made in bigger orders and higher-priced items; small, low-priced orders are numerous but earn very little.

### ⬆️ Key Influencers — What Influences Profit to *Increase*
<img width="1279" height="712" alt="image" src="https://github.com/user-attachments/assets/4f2e0f9d-0c7a-4467-bb85-6811cce7b554" />

| Condition | Average Profit Increases By |
|---|---:|
| Sum of Unit Price is more than 36 | **1.21K** |
| Sum of Total Excluding Tax goes up 1473.82 | 751 |
| Sum of Quantity is 26 – 120 | 663.7 |
| Sum of Unit Price is 16 – 24 | 153.9 |

| Screen | What it shows |
|---|---|
| Total Excluding Tax (scatter plot) | On average, when Sum of Total Excluding Tax increases, Profit also increases |
| Unit Price (column chart) | Profit is more likely to increase when Unit Price is more than 36 (average excluding selected: 216.86) |
| Quantity (column chart) | Profit is more likely to increase when Quantity is 26 – 120 (average excluding selected: 183.28) |
| Unit Price 16 – 24 (column chart) | Profit is more likely to increase when Unit Price is 16 – 24 (average excluding selected: 346.78) |

**Insight:** Unit price above 36 is the strongest influencer on the page, followed by order value and a mid-size quantity range (26–120 units).
<img width="1289" height="715" alt="image" src="https://github.com/user-attachments/assets/28dd7c01-bfc8-4902-bf29-9a00d36eb890" />


### ⬇️ Key Influencers — What Influences Profit to *Decrease*
<img width="1261" height="714" alt="image" src="https://github.com/user-attachments/assets/0dd00d55-ff84-4f79-8705-824f3c8a0112" />

| Condition | Average Profit Decreases By |
|---|---:|
| Sum of Total Excluding Tax goes down 1473.82 | 751 |
| Sum of Unit Price is 12 – 16 | 413.4 |
| Sum of Unit Price is 12 or less | 240.9 |

| Screen | What it shows |
|---|---|
| Total Excluding Tax (scatter plot) | On average, when Sum of Total Excluding Tax decreases, Profit also decreases |
| Unit Price 12 – 16 (column chart) | Profit is more likely to decrease when Unit Price is 12 – 16 (average excluding selected: 463.19) |
| Unit Price 12 or less (column chart) | Profit is more likely to decrease when Unit Price is 12 or less (average excluding selected: 419.23) |

**Insight:** Profit is tied to order value more than anything else, and low unit prices (16 and below) also pull profit down.


### 🔵 Scatter Plot — Total Excluding Tax vs Average Profit

The x-axis shows **Total Excluding Tax** (0 to 20K) and the y-axis shows **Average of Profit**. The points follow an upward trend line.

**Insight:** As order value rises, average profit rises almost proportionally. A few points sit far above the line (up to roughly 9K profit at about 11K order value), representing deals with unusually high profit.

### 🎯 Top Segments — *High* Profit
<img width="1291" height="721" alt="image" src="https://github.com/user-attachments/assets/9e864f43-084c-4969-bc92-96871d463beb" />

Overall average profit: **375.9**

| Segment | Rule (Sum of Total Excluding Tax) | Average Profit | Data Points | Share of Data |
|---|---|---:|---:|---:|
| 1 | greater than 2560 | **2.93K** | 1,283 | 4.9% |
| 2 | greater than 1610 and up to 2560 | 926.8 | 2,394 | 9.1% |
| 3 | greater than 1199 and up to 1610 | 641.4 | 1,571 | 6.0% |
| 4 | greater than 864 and up to 1199 | 489.3 | 1,303 | 4.9% |

### 🎯 Top Segments — *Low* Profit

<img width="1275" height="723" alt="image" src="https://github.com/user-attachments/assets/1ac0a76d-0d6d-4549-85da-b8f3e55d1e53" />
| Segment | Rule (Sum of Total Excluding Tax) | Average Profit | Data Points | Share of Data |
|---|---|---:|---:|---:|
| 1 | up to 60 | 19.42 | 3,702 | 14.0% |
| 2 | greater than 60 and up to 90 | 42.91 | 2,131 | 8.1% |
| 3 | greater than 90 and up to 125 | 61.78 | 2,774 | 10.5% |
| 4 | greater than 125 and up to 216 | 91.51 | 4,005 | 15.2% |
| 5 | — | 131.8 | — | — |
| 6 | — | 181.9 | — | — |

**Insight:** Every segment is defined by order value. The best high-profit segment earns **≈ 7.8× the overall average** and **≈ 150× the weakest low-profit segment** (2,930 ÷ 19.42), with a much smaller population (1,283 vs 3,702 records). Low-profit segments 1–4 together cover about **47.8% of the data**.

<img width="1249" height="705" alt="image" src="https://github.com/user-attachments/assets/1f89c4b7-e5d3-48ce-9b10-38098264dbb1" />

---

## 📄 Page 3 — Customer & Employee Performance
<img width="1245" height="687" alt="image" src="https://github.com/user-attachments/assets/2011f9cd-e944-4d37-82b1-71806120d4fe" />



### 📖 Page Story

**Customers.** The base is **402 customers**. Among named customers the order counts are remarkably even (**126–132 orders** for the top five), so no single account dominates. The customer count by year follows the sales curve: **7.1K → 7.7K → 8.3K**, then **3.3K in January–May 2016**. The big exception is **"Unknown"**: **2,842 orders (≈ 34.7% of 8,188)** with no customer identity attached.

**Employees.** The **19-person team** is tightly clustered. Profit-status values run from 2,462 to 2,749, the lower end of the team still sells **$1.79M–$1.98M** each, and the top 5 sit within about **8%** of each other on profit. The most profitable employee is **Sophia Hinton ($1,087,990)**, who edges out Lily Code ($1,048,804) with **18 fewer orders**, because her average order is larger (**≈ $2,668 vs ≈ $2,486**).

**Bottom line.** A balanced customer base and a balanced team, where the winning habit is bigger orders rather than more orders, and where about a third of the orders still cannot be traced to a customer.

### 🔢 KPI Cards

| KPI | Value |
|---|---:|
| 👥 NumberOfCustomer | **402** |
| 🧑‍💼 Count of Employee | **19** |
| 🛒 Customer Purchase | **12.19%** |
| ✅ Employee Active | **46.92%** |

### 👥 Customers

**Count of Customer per Year** *(area chart with trend line)*

| Year | Count |
|---|---:|
| 2013 | 7.1K |
| 2014 | 7.7K |
| 2015 | 8.3K |
| 2016 (Jan–May) | 3.3K |

**Top 5 Less Customer by Sales** *(column chart)*

| Customer | Sales |
|---|---:|
| Tailspin Toys (Lemeta, AK) | $223K |
| Tailspin Toys (Ikatan, AK) | $218K |
| Wingtip Toys (Lostine, OR) | $213K |
| Tailspin Toys (Magalia, CA) | $183K |
| Wingtip Toys (Marin City, CA) | $170K |

**Top 10 Customer by Number of Orders** *(table)*

| Customer | Total Orders |
|---|---:|
| Unknown | 2,842 |
| Wingtip Toys (Kapa'a, HI) | 132 |
| Tailspin Toys (Fieldbrook, CA) | 130 |
| Wingtip Toys (Salt Wells, NV) | 129 |
| Tailspin Toys (Kwethluk, AK) | 126 |
| Tailspin Toys (Sekiu, WA) | 126 |

**Insight:** Named customers are very even (126–132 orders), so no single account dominates. The exception is **"Unknown" with 2,842 orders, ≈ 34.7% of all 8,188 orders**, which cannot be tied to a customer identity. The lower-ranked customers by sales sit in a narrow band of $170K–$223K.

### 🧑‍💼 Employees

**Sales Employee by Profit Status** *(bar chart: Loss vs Profit)*

| Employee | Value |
|---|---:|
| Sophia Hinton | 2,749 |
| Kayla Woodcock | 2,738 |
| Lily Code | 2,729 |
| Archer Lamble | 2,665 |
| Amy Trefl | 2,663 |
| Hudson Hollinworth | 2,641 |
| Jack Potter | 2,607 |
| Hudson Onslow | 2,573 |
| Taj Shand | 2,570 |
| Anthony Grosse | 2,462 |

**Top 5 less Employee per Sales by Year** *(column chart)*

| Employee | Sales |
|---|---:|
| Amy Trefl | $1.89M |
| Anthony Grosse | $1.87M |
| Hudson Hollinworth | $1.98M |
| Hudson Onslow | $1.92M |
| Jack Potter | $1.79M |

**Top 10 Employee by Profit** *(table, ranked here by Total Profit, with derived per-order metrics)*

| Employee | Total Orders | Total Profit | Total Sales | Sales / Order | Profit / Order |
|---|---:|---:|---:|---:|---:|
| Sophia Hinton | 832 | $1,087,989.90 | $2,219,626 | ≈ $2,668 | ≈ $1,308 |
| Lily Code | 850 | $1,048,804.05 | $2,112,720 | ≈ $2,486 | ≈ $1,234 |
| Kayla Woodcock | 831 | $1,027,053.50 | $2,081,322 | ≈ $2,505 | ≈ $1,236 |
| Archer Lamble | 817 | $1,010,010.10 | $2,005,041 | ≈ $2,454 | ≈ $1,236 |
| Taj Shand | 795 | $1,005,794.15 | $2,008,876 | ≈ $2,527 | ≈ $1,265 |

**Insight:** The team is very balanced: the top 5 sit within about **8%** of each other on profit, and the lower end of the team ($1.79M–$1.98M in sales) is not far behind. **Sophia Hinton leads even though Lily Code handles more orders**, because her average order is larger (≈ $2,668 vs ≈ $2,486). This matches the Key Influencers page, where order value matters more than order count.

---

## 🧩 The Whole Story in 6 Sentences

1. The company sells **$19.88M across 8K orders** with a **49.92% margin**, and cost stays at about 50% of sales every year.
2. Sales grew every full year (**+11.1% in 2014, +8.6% in 2015**), though the growth rate slowed.
3. 2016 covers January–May only, so its lower totals mostly reflect the missing months; on a monthly basis it runs **≈ 8% below 2015**.
4. **Order value drives profit:** a fall in order value cuts profit most, low unit prices hurt, and the best segment earns ≈ 150× more per record than the weakest.
5. The business is anchored on packaging products (**top 10 ≈ 32.8% of sales**), while profit is widely spread across cities, customers and employees.
6. About **a third of orders have an "Unknown" customer**, and the top employee wins through **bigger orders, not more orders**.

---

## 💡 Recommendations

Each recommendation is tied to evidence shown in the dashboard.

| Finding (evidence) | Recommended action | Measure to track |
|---|---|---|
| 2016 (Jan–May) runs ≈ 8.1% below 2015 per month, and Qtr 1 is ≈ 8.5% below Qtr 1 2015 | Compare Jan–May 2016 with Jan–May 2015 using the **Month** slicer, and drill by Brand and City to see where the gap sits | Jan–May sales and orders growth vs 2015 |
| Profit rises with order value (scatter plot, −751 / +751 influencer) | Pilot bundles and order-value incentives with existing products | Average order value (≈ $2,428 today), profit per order |
| Unit price of 16 or below is linked to lower profit (−413.4, −240.9) | Attach low-price items to higher-value orders and review margins on a few of them | Profit per unit, share of low-price-only orders |
| Best segment averages 2.93K vs 19.42 for the weakest | Open the best segments in Top Segments, list their customers, products and order sizes, and offer similar mixes to similar customers | Share of records in high-profit segments |
| "Unknown" customer has 2,842 orders (≈ 34.7%) | Find out what "Unknown" represents (walk-in channel, missing key or null) and require a customer ID on new orders | "Unknown" share of orders |
| Top 10 products ≈ 32.8% of sales, mostly packaging, led by a machine | Keep top products available and promote consumables with every machine sale | Sales outside the top 10 |
| Sophia Hinton out-earns Lily Code with fewer orders | Share her order-building approach with the team | Average order value per employee |

### 📊 KPIs to Track on the Dashboard

| KPI | Current value | Direction |
|---|---:|---|
| Average order value | ≈ $2,428 | ⬆️ Increase |
| Profit margin | 49.92% | ➡️ Hold or improve |
| "Unknown" customer orders | 2,842 (≈ 34.7%) | ⬇️ Decrease |
| Top-10 product share of sales | ≈ 32.8% | ⬇️ Gradually decrease |
| Loss share of records | 2.14% | ⬇️ Decrease |
| Monthly sales run-rate (Jan–May 2016) | ≈ $0.486M (vs ≈ $0.529M in 2015) | ⬆️ Increase |

---

## 🧰 Tools Used

- **Power BI Desktop**
- **Power Query**: data cleaning and preparation
- **DAX measures**: Total Sales, Total Profit, Profit Margin, Sales Growth, Orders, Quantity
- **Data Modeling**: relationships between Sales, Customer, Employee, Product, City and Date
- **AI Visuals**: Key Influencers, Top Segments
- **Dashboard design**: custom navy and orange theme, icons, slicers, navigation buttons

---

## 🚀 How to Use the Dashboard

1. Open `[FileName].pbix` in **Power BI Desktop**.
2. Use the slicers on the left (**Month, Brand, Profitstatus**) to filter the data.
3. Use the arrow at the bottom-right of Page 1 to open *What Drives Sales Profitability*, and the back arrow to return.
4. Use the orange header button to switch between *Sales & Business* and *Customer & Employee* pages.
5. On the profitability page, switch between **Key influencers** and **Top segments**, and change the dropdown (*Increase / Decrease*, *High / Low*) to see other views.
6. To compare 2016 fairly, select the same months in each year with the **Month** slicer.

---

⭐ If you like this dashboard, leave a star on the project!
