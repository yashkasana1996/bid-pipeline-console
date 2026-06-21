# 🏗️ RFP Intelligence Console
### AI-Powered Pipeline Management System | Built for a ₹1,370Cr Real Estate Conglomerate

![Status](https://img.shields.io/badge/Status-Live%20in%20Production-brightgreen)
![AI](https://img.shields.io/badge/AI-Claude%20(Anthropic)-orange)
![Dashboard](https://img.shields.io/badge/Dashboard-Power%20BI-yellow)
![Impact](https://img.shields.io/badge/Pipeline%20Scaled-₹400Cr%20→%20₹750Cr-blue)

---

## 🔍 Business Problem

one of India's leading Design & Build firms (₹1,370Cr+ revenue, 2,500+ projects across 60+ cities) serving clients including **Microsoft, Google, Amazon, Accenture, SBI, Coca-Cola, ZEISS, and Schindler** — had no centralised, real-time visibility into its RFP pipeline.

The City Director was managing a growing portfolio of live deal opportunities across **7 cities** through fragmented spreadsheets, email chains, and manual daily reports. This created:

- ❌ No real-time deal status — required calling multiple teams for updates
- ❌ No automated eligibility scoring — RFPs assessed manually, causing delays
- ❌ No regional segmentation — 7 cities tracked in one flat list
- ❌ 2–3 hours daily wasted on manual report compilation

---

## 💡 Solution Built

An **AI-powered operating console** — a single-window command centre for the City Director replacing all manual pipeline reporting with real-time intelligence.

### Core Features

| Feature | What It Does |
|---|---|
| 🗺️ **Live RFP Dashboard** | Real-time pipeline with deal stage, client, value, and probability |
| 📍 **Regional Segmentation** | City-wise breakdown: Mumbai, Pune, Gujarat, NCR, Hyderabad, Bengaluru, Chennai |
| 🤖 **AI Eligibility Scoring** | Claude AI scores each RFP against company capability profile — instant bid/no-bid |
| 📊 **Deal Stage Monitoring** | Client-wise tracking from RFP receipt → bid → negotiation → closure |
| 📰 **Daily Intelligence Report** | Auto-generated executive brief delivered every morning |
| 🚨 **Bottleneck Flagging** | Identifies deals stalled beyond threshold — surfaces for director action |
| 🔗 **Contracts Team Integration** | Live sync — no double-entry, no lag |

---

## 📈 Measured Business Impact

| Metric | Before | After |
|---|---|---|
| Pipeline visibility | Fragmented, 24hr lag | Real-time, single dashboard |
| RFP eligibility assessment | Manual, 4–6 hours per RFP | **Automated, instant** |
| Active pipeline value | ₹400 Crore | **₹750 Crore (+87.5% in 2 weeks)** |
| Daily report prep time | 2–3 hours manually | **Fully automated** |
| Pipeline efficiency | Baseline | **+30–40% improvement** |
| Simultaneous deals tracked | ~15–20 | **50+ across 7 cities** |

---

## 🛠️ Tech Stack

```
Claude AI (Anthropic)     — RFP analysis, eligibility scoring, report generation
Power BI                  — Live dashboards, regional maps, deal-stage funnels
MS Excel (Advanced)       — Structured data input, formula logic, data pipeline
Automation Workflows      — Auto-report generation, scheduled data refresh
Power BI Connectors       — Integration with contracts team data sources
```

---

## 🏛️ System Architecture

```
┌─────────────────────────────────────┐
│  RFP Data Input (Contracts Team)    │
└────────────────┬────────────────────┘
                 ↓
┌─────────────────────────────────────┐
│  Data Processing Layer              │
│  Excel + Power BI Connectors        │
└────────────────┬────────────────────┘
                 ↓
┌─────────────────────────────────────┐
│  Claude AI Engine (Anthropic)       │
│  ├── RFP Eligibility Scoring        │
│  ├── Bid Priority Ranking           │
│  ├── Risk Identification            │
│  └── Daily Intelligence Report Gen  │
└────────────────┬────────────────────┘
                 ↓
┌─────────────────────────────────────┐
│  Power BI Dashboard (Director View) │
│  ├── Live Pipeline — All Cities     │
│  ├── Regional Breakdown             │
│  ├── Deal Stage Funnel              │
│  ├── Client Portfolio View          │
│  └── Bottleneck Alert Panel         │
└────────────────┬────────────────────┘
                 ↓
┌─────────────────────────────────────┐
│  Auto Daily Brief → City Director  │
│  (WhatsApp / Email / Dashboard)    │
└─────────────────────────────────────┘
```

---

## 🤖 AI Implementation — Claude Prompt Chains

### 1. RFP Eligibility Scoring
Each RFP is submitted to Claude with:
- ANJ Group capability profile (project types, city presence, team capacity, past wins)
- RFP requirements (scope, timeline, client, value, special conditions)
- Historical bid outcome data for similar project types

**Claude returns:**
- Eligibility score (0–100)
- Bid recommendation (Bid / No-Bid / Conditional)
- Key risks identified
- Suggested bid positioning

### 2. Daily Intelligence Report Prompt
Every morning, a structured prompt pulls live dashboard data and generates a 1-page executive brief:
- Top 5 priority deals requiring director attention today
- Deals at risk (stalled or approaching deadline)
- New RFPs received in last 24 hours
- Pipeline value movement vs previous day
- Recommended actions

---

## 🧠 Key Problem-Solving Learnings

> **"The biggest problem wasn't data — it was visibility."**
The contracts team had all the data. It was siloed. A single director-facing view was the highest-leverage intervention.

> **"AI works best when it replaces a specific task, not a vague one."**
Eligibility scoring had a defined input (RFP document) and defined output (score + recommendation). Claude performs this reliably at scale.

> **"Adoption requires matching the user's mental model."**
The first version was technically capable but unused — it didn't match how the director thought about deals. Rebuilding the layout around his existing workflow drove immediate adoption.

---

## 📁 Repository Structure

```
anj-rfp-intelligence-console/
├── README.md
├── docs/
│   ├── architecture-diagram.png
│   ├── dashboard-overview.png
│   └── sample-daily-report.pdf      ← anonymised
├── prompts/
│   ├── eligibility-scoring.txt
│   ├── daily-intelligence-report.txt
│   └── bid-strategy-generator.txt
├── templates/
│   ├── rfp-input-template.xlsx
│   └── pipeline-tracker-master.xlsx
└── powerbi/
    └── setup-guide.md
```

---

## 👤 Builder

**Yashwant Kumar Gurjar** — Strategy & AI Operations | Founder's Office | Digital Transformation
📞 +91 75970 92148 | 📧 yashkasana6991@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/yashwant-gurjar96)

*All client names and deal values are anonymised. Screenshots show dummy data.*
