# 📊 Sales Pipeline & Rep Performance Toward Quota — Pendula

> **Portfolio case study · Sales Analytics & FP&A**

| | |
|---|---|
| **Client** | Pendula (Zipline Cloud Pty Ltd) |
| **Industry** | SaaS · B2B2C Two-Way Communication Platform |
| **Role** | Principal BI & Data Analyst |
| **Period** | June 2022 – October 2025 |
| **Tools** | Domo · SQL · Salesforce · Excel |

---

## Impact at a glance

| Metric | Result |
|---|---|
| ⏱ Month-end time saved | **2–3 working days per month** |
| 📈 Upsell revenue growth | **+15%** driven by pipeline visibility |
| ✅ Self-service reporting | **100%** — zero manual data pulls |
| 💬 Commission disputes | **0** in two quarters post go-live |

---

## 1. Executive Summary

Pendula is a B2B2C two-way communication platform that enables enterprise clients to send, receive, and act on messages across SMS and email at scale. What sets Pendula apart is its real-time data engine — personalising and contextualising every message using live signals such as weather conditions, geolocation, and customer behaviour. AI-powered sentinel analytics sits at the core of the platform, allowing clients to trigger the right message to the right person at exactly the right moment.

As Pendula scaled globally, its commercial reporting didn't keep pace. Leadership — including the CEO, CRO, and CFO — had no reliable, real-time view of pipeline health or how individual sales representatives were tracking against quota. Reporting was fragmented: manual Salesforce exports stitched together with individual Excel trackers, compiled weekly, and already stale by the time it reached the inbox.

This project delivered a **Salesforce-integrated Domo BI solution** that gave the full leadership team a single source of truth across pipeline stages, deal velocity, quota attainment, and commission exposure — while also giving every sales rep direct visibility into their own numbers, their team's progress, and the company's overall target.

---

## 2. Business Problem

As Pendula transitioned from a founder-led sales motion to a globally scaling team with defined territories and quotas, its reporting infrastructure remained stuck in start-up mode. Sales and Finance operated in separate data silos, each maintaining their own version of the truth with no mechanism to reconcile them.

| Problem | Business impact |
|---|---|
| 🔴 No real-time pipeline visibility | Leadership made decisions on week-old Salesforce snapshots — by the time data landed, deals had already moved or been lost |
| 🔴 Quota tracking was fragmented and manual | Sales managers kept individual Excel trackers with no consolidated team view, making it impossible to spot and rescue an at-risk rep before month-end |
| 🔴 Finance had no forecast it could rely on | Revenue forecasts were built on intuition rather than weighted pipeline data — committed deals and upside were not differentiated, making board reporting unreliable |
| 🔴 Reps flew blind on their own targets | Sales representatives had no self-serve view of where they stood against quota, their team's trajectory, or the company's overall performance — reducing accountability and motivation |
| 🔴 Commission disputes created rework | Without a single source of truth for closed-won deals and OKR attainment, commission calculations were regularly contested, pulling Finance and Sales Ops into time-consuming back-and-forth |

---

## 3. Methodology

The project was delivered in **four structured phases over eight weeks**, working in close partnership with the CEO, CRO, CFO, Sales Director, and two sales reps who served as data champions and validators.

### Phase 1 — Discovery & Requirements
- Ran structured workshops with Sales, Finance, and Leadership to surface reporting needs, pain points, and decision-making gaps
- Defined the quota mechanics in detail: territory structures, monthly vs quarterly cycles, tiered accelerators, and OKR scoring rules
- Audited the existing Salesforce data model — mapping custom objects, pipeline stage definitions, and field-level data quality issues specific to Pendula's global sales motion

> `Deliverables: Workshop notes · Salesforce data audit · Requirements specification`

### Phase 2 — Data Extraction & Modelling
- Built SQL queries to extract Opportunity, Account, User, and Activity data from Salesforce into Domo's data pipeline
- Designed a clean, scalable data model with deal-level, rep-level, and time-intelligence dimensions to support all planned report views and future extensibility
- Applied calculated fields for rolling periods, probability-weighted ARR, and NRR contribution from new logo deals

> `Deliverables: SQL extraction scripts · Domo data model · Calculated field library`

### Phase 3 — Dashboard Design & Build
Built four interconnected Domo report views, each designed for a specific audience:

1. **Pipeline Health Overview** *(Leadership)* — stage-by-stage waterfall, global deal velocity, and stall alerts for deals inactive 21+ days
2. **Rep vs Quota Attainment** *(Sales Managers)* — individual drill-through with OKR scoring, commission exposure, and pacing-to-target
3. **Rep Self-Serve View** *(Sales Reps)* — personal target progress, team ranking, and company-wide target tracker to drive accountability
4. **Revenue Forecast** *(CFO / Finance)* — probability-weighted pipeline mapped directly to the quarterly rolling financial model

> `Deliverables: Domo dashboard · UX wireframes · Measure documentation`

### Phase 4 — Validation, Training & Handover
- Ran a two-week parallel period comparing Domo outputs against the existing manual process — resolving discrepancies in stage definitions, multi-territory deal attribution, and commission edge cases
- Delivered role-specific training sessions for Sales Reps, Sales Managers, Finance, and the Leadership team
- Documented all data definitions, refresh schedules, and ownership rules to support long-term data governance

> `Deliverables: UAT log · Role-based training materials · Governance documentation`

---

## 4. Skills Demonstrated

**Data & BI**
`Domo` `SQL` `ETL & data pipelines` `Salesforce data extraction` `Dimensional data modelling` `Dashboard UX design`

**Finance & FP&A**
`Revenue forecasting` `Weighted pipeline modelling` `Quota design & attainment tracking` `Commission calculation (tiered + OKR)` `SaaS metrics — ARR · NRR · ACV`

**CRM & Sales Ops**
`Salesforce CRM` `Pipeline stage governance` `Sales funnel analysis` `Deal velocity & cycle time` `Territory management`

**Soft Skills**
`C-suite stakeholder management` `Business-to-data translation` `Role-based user training` `Data governance & documentation`

---

## 5. Results & Business Recommendations

The solution was fully adopted by Sales and Finance within the first month and became the standing view for weekly pipeline reviews and monthly board reporting. The following outcomes were measured in the first quarter post-launch.

### Outcomes

**⏱ Operational efficiency**
Eliminated 2–3 working days per month previously spent compiling pipeline reports and validating commission calculations manually. Sales Ops redirected that time to active deal support.

**📈 Revenue impact**
Real-time visibility into stalled deals — those inactive for 30+ days — enabled the Sales Director to intervene before opportunities were lost. Combined with improved customer usage visibility, upsell revenue grew by 15% in the quarter following launch.

**🎯 Forecast accuracy**
Probability-weighted pipeline gave Finance a credible 12-week revenue outlook for the first time. Forecast-to-actuals variance fell by an estimated 20–25%, giving the CFO reliable numbers for board-level reporting.

**🧑‍💼 Rep accountability & motivation**
Reps gained direct, self-serve visibility into their personal progress against quota, their team's trajectory, and the company's overall target. Anecdotally, this transparency drove stronger pipeline hygiene and earlier escalation of at-risk deals.

**✅ Commission confidence**
Zero disputes in two full quarters following go-live. With reps able to track their own attainment in real time, queries to Finance and Sales Ops dropped by an estimated 80%.

---

### Business Recommendations Delivered to Leadership

> **→** Introduce a structured deal review gate at Stage 3 (Proposal). Analysis showed that 61% of lost opportunities had stalled at this stage for more than 21 days without activity — making it the single highest-leverage point for Sales Manager intervention.

> **→** Rebalance territory assignments. Two reps were consistently exceeding 110% of quota while two others hovered below 60% — a pattern that pointed to territory size and lead quality imbalance rather than individual performance gaps.

> **→** Separate enterprise and SMB pipelines in Salesforce. Pendula's deal economics — average contract value, cycle length, and win rate — differed significantly between segments, but blended reporting was masking this and distorting the forecast.

> **→** Connect the sales pipeline to Pendula's own platform data. Given that Pendula's product is built on real-time customer signals, there was a natural opportunity to use customer engagement data to trigger timely renewal and expansion conversations — closing the loop between product usage and commercial action.

---

## 6. Next Steps

| Phase | Initiative | Description |
|---|---|---|
| **Phase 2** | Predictive close scoring | A rules-based deal health score — using activity recency, stage age, deal size, and stakeholder engagement — to surface a close probability indicator alongside the existing pipeline view |
| **Phase 3** | Lifetime value integration | Connect new-logo ARR from closed-won deals into the customer LTV model, enabling Sales and Finance to report on blended NRR that includes new business — not just renewals and expansions |
| **Phase 4** | Real-time Salesforce sync | Replace the daily scheduled data refresh with a near-real-time Salesforce integration, giving Sales Managers a live view of deal movements without leaving the Domo environment |

---

## About

**Thuy Tu** — Data & FP&A Analyst (Freelance)

CPA, MBA-qualified finance and data professional with 15+ years across SaaS, fintech, and professional services. Specialist in Domo, Power BI, SQL, Salesforce, and financial modelling — with a track record of turning fragmented reporting into decisions that stick.

📧 [thuthuy.tu@gmail.com](mailto:thuthuy.tu@gmail.com)
🔗 [linkedin.com/in/thuytu](https://www.linkedin.com/in/thuytu)
📞 (+61) 436 104 308

---

*This case study is part of Thuy Tu's freelance portfolio. Client data has been anonymised.*
