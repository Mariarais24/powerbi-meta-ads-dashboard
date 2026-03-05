# 📣 Meta Ads Performance Intelligence Dashboard

**Transforming raw Meta Ads data into a diagnostic analytics layer for marketing and performance teams.**

---

## 🔗 [View Live Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNTQwMjk5YjctMWIyMi00OGVkLTg2ODItOGRkYzU5MzA5MjQxIiwidCI6IjNiNWIwMDgyLTczNmQtNGIwNi1hYjU1LWUyYzQ0ZGI3YWIzMSIsImMiOjl9)

---

## 🛠 Tech Stack

- 📊 Power BI Desktop
- 🧠 DAX (custom KPI measures)
- 🗄️ Microsoft SQL Server (data structuring)
- 🎨 Figma (background & layout design)
- 📝 Data Modeling (star-schema inspired)

---

## 📂 Data Source

Simulated Meta Ads–like dataset structured in **SQL Server** to mirror real-world ad delivery data; covering campaigns, ad sets, creatives, spend, impressions, clicks, conversions, revenue, device, and geography dimensions.

---

## 💡 Dashboard Breakdown

### Business Problem
Marketing teams running Meta Ads often lack structured visibility across campaigns and creatives. Spend scales, but fragmented reporting makes it hard to link budget → engagement → revenue, or spot where money is being wasted.

### Goal
Build a BI-ready analytical framework that goes beyond native ad platform dashboards. Enabling performance monitoring, cost-efficiency diagnosis, and budget optimization decisions at multiple levels.

---

### 🖥️ Walkthrough of Key Pages

---

**Page 1 — Ad Performance Overview**

![Ad Performance Overview](https://raw.githubusercontent.com/Mariarais24/meta-ads-powerbi/main/ad-performance-overview.png)

The executive entry point. Tracks the full funnel from impressions → clicks → conversions, alongside core KPIs: ROAS, CPA, CPC, and CTR; each with a week-over-week delta. A daily spend trend chart surfaces pacing anomalies, while combo charts show whether conversions are becoming more cost-efficient over time and whether reach is growing.

---

**Page 2 — Campaign Cost Efficiency Analysis**

![Campaign Efficiency](https://raw.githubusercontent.com/Mariarais24/meta-ads-powerbi/main/campaign-efficiency.png)

Built for media buyers and optimization analysts. Compares CPC across ad creatives, benchmarks ad spend vs. revenue per campaign, and tracks CPA against conversion volume over time. Filterable by campaign and device, making it easy to isolate what's working and where budget is leaking.

---

### Business Impact & Insights

- 💸 **"Discover Our Products"** creative has the highest CPC ($1.44) — a signal to test new messaging
- 📈 **"Discover Our Products"** campaign generates the highest revenue ($559) despite mid-range spend — strongest ROAS candidate for scaling
- ⚠️ CPA spikes on **Winter Sale** campaign suggest cost inefficiency that warrants reallocation
- 📅 Daily spend trend shows significant volatility — pacing strategy needs tightening to avoid underspend gaps

---

## ✅ Recommendations

| # | Action |
|---|---|
| 1 | Scale **Discover Our Products** — highest revenue return relative to spend |
| 2 | Review **Flash Sale** creative — lowest revenue despite comparable spend |
| 3 | Reduce CPA volatility on Winter Sale by tightening audience targeting |
| 4 | Use CPC by creative as a weekly diagnostic — shift budget toward lower-cost, higher-converting ads |
