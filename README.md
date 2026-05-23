
# 📊 Performance Marketing — Campaign Analysis

**Multi-Market Social Media Campaign Analysis | Jul–Nov 2024**

A comprehensive analysis of a global performance marketing campaign spanning **649 posts**, **2 channels** (Facebook & Instagram), and **13 markets** across APAC and Europe. Built using Excel for data wrangling and PowerPoint for executive reporting.

---

## 🔍 Project Overview

A consumer electronics brand ran a multi-market social media campaign across Facebook and Instagram from July to November 2024. This project analyses raw post-level data (666 records) to surface performance trends, content strategy insights, channel effectiveness, and actionable recommendations.

### Business Questions Answered

- What are the key performance trends across months, markets, and channels?
- Which content pillars and formats drive the strongest engagement?
- How do APAC markets compare to European markets — and why?
- What caused the October engagement collapse (99.9% drop)?
- Where should the brand invest next for maximum ROI?

---

## 📁 Repository Structure

```
├── data/
│   └── Market_Campaign_Analysis_Working_File.xlsx   # Cleaned dataset + all analysis tabs
├── reports/
│   └── Campaign_Analysis_Cheil.pptx                 # Final executive presentation (19 slides)
├── images/
│   ├── kpi_scorecard.png
│   ├── monthly_trend.png
│   ├── channel_split.png
│   └── market_tiers.png
└── README.md
```

---

## 📈 Key Findings

### KPI Scorecard

| Metric | Value |
|--------|-------|
| Total Posts | 649 |
| Total Engagements | 1.07M |
| Total Impressions | 9.18M |
| Total Reach | 6.19M |
| Avg Engagement Rate | 11.6% (industry benchmark: 1–5%) |
| Peak Month | September (585K engagements, 29.3% ER) |

### 1. Monthly Performance Trends

Performance followed a **build → peak → crash → recovery** pattern:

- **Jul → Aug**: Strong early traction (+94.8% engagement growth)
- **Aug → Sep**: Engagement exploded to 585K (+179.8%), driven by a viral Thailand video (310K engagements alone)
- **Sep → Oct**: **Critical anomaly** — engagement collapsed by 99.9% (450 total engagements across 134 posts)
- **Oct → Nov**: Massive rebound (+36,696% engagement) with Campaign Pillar launch driving 3.75M impressions

### 2. Channel Performance — Facebook vs Instagram

| Metric | Facebook | Instagram |
|--------|----------|-----------|
| Posts | 335 | 314 |
| Total Engagements | 1.07M | 1,024 |
| Avg Reach/Post | 18,451 | 37 |
| Avg Engagement Rate | 11.6% | 8.9% |

Facebook drove **99.9% of all engagements**, primarily through viral APAC video content. Instagram showed higher engagement quality with a consistent ER and untapped Carousel potential (only 15 posts, highest ER of any format).

### 3. Content Pillar Analysis

| Pillar | Posts | Avg Eng/Post | Avg ER |
|--------|-------|-------------|--------|
| Campaign | 8 | 18,854 | 15.4% |
| Product Education | 202 | 4,425 | 18.2% |
| Giveaway Promotion | 17 | 224 | 5.0% |
| Influencer Repost | 5 | 112 | 22.8% |
| Product Feature | 113 | 3.5 | 2.8% |
| Bousai Education | 36 | 3.3 | 14.7% |

Product Education drove **84% of total engagement volume** (894K out of 1.07M). Campaign Pillar had the highest per-post impact but was active only in November.

### 4. Market Tiering

| Tier | Markets | Avg Eng/Post |
|------|---------|-------------|
| 🥇 Tier 1 — Star | Thailand, Vietnam, International | >5,000 |
| 🥈 Tier 2 — Solid | Taiwan, Hong Kong, España | 700–2,000 |
| 🥉 Tier 3 — Developing | Belgium, Greece, Hungary, Česká Republika | 175–265 |
| ⚠️ Tier 4 — Low | Turkey, Middle East, Japan | <110 |

**APAC markets outperformed Europe by 30×**, with the Top 10 posts globally all being Product Education videos from Thailand, Vietnam, and Taiwan.

### 5. October Anomaly

October recorded only **450 total engagements** across 134 posts (avg 3.4 per post vs September's 4,840). Instagram maintained ~245 engagements, isolating this as a **Facebook-specific issue** — likely a tracking failure, algorithm change, or campaign budget pause requiring investigation.

---

## 💡 Strategic Recommendations

| Priority | Recommendation | Expected Impact |
|----------|---------------|-----------------|
| 🔴 High | Invest in APAC Product Education video production; localize Thailand/Vietnam scripts for underperforming markets | +200–400K engagements/quarter |
| 🔴 High | Investigate & resolve October data anomaly; audit against native platform analytics | Accurate planning baseline |
| 🟡 Medium | Scale Instagram Carousel format — run a 20-post structured test with paid amplification | +3–5pp ER lift on Instagram |

---

## 🛠 Tools & Methodology

| Tool | Purpose |
|------|---------|
| **Microsoft Excel** | Data cleaning, pivot analysis, statistical summaries, anomaly detection |
| **Microsoft PowerPoint** | Executive presentation design and data storytelling |
| **Descriptive Statistics** | Mean, median, std dev, IQR for engagement distribution analysis |

### Analysis Workflow

```
Raw Data (666 rows, 13 columns)
    ↓
Data Cleaning & Validation
    ↓
Pivot Analysis (Monthly, Channel, Pillar, Market, Format)
    ↓
Statistical Summary & Anomaly Detection
    ↓
Insight Synthesis → Executive Presentation (19 slides)
```

---

## 📊 Dataset Schema

| Column | Description |
|--------|-------------|
| Month | Campaign month (Jul–Nov 2024) |
| Channel | Facebook or Instagram |
| Profile (Market) | 13 markets across APAC and Europe |
| Format | Video, Album (Carousel), Photo |
| Posted Date | Individual post date |
| Pillar / Master Pillar | Content category hierarchy |
| Engagements | Total interactions (likes, comments, shares, clicks, video views) |
| Comments | Comment count |
| Like | Like count |
| Impressions | Total content display count (includes repeats) |
| Reach | Unique accounts reached |
| Engagement Rates | Engagements ÷ Reach |

---

## 📋 Excel Workbook Tabs

| Tab | Contents |
|-----|----------|
| DATA | Raw dataset (666 rows) |
| Cleaned Data | Validated and standardized data |
| Monthly Summary | Month-over-month KPIs and growth rates |
| Channel Analysis | Facebook vs Instagram comparison |
| Pillar Analysis | Master Pillar performance breakdown |
| Format Analysis | Video vs Album vs Photo metrics |
| Market Analysis | 13-market tiering with ER and reach |
| Statistical Summary | Descriptive statistics and distribution |
| Anomaly Detection | October deep-dive with Sep vs Oct comparison |
| Insights | Consolidated findings and narrative |

---





