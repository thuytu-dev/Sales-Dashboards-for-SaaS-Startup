# 📊 Sales Workspace & Dashboards 

> **Sales Operations · Sales Analytics · Sales Pipeline · Customer Segmentation · Sales Performance**

| | |
|---|---|
| **Industry** | SaaS · B2B2C |
| **Role** | Principal BI & Data Analyst |
| **Tools** | Domo · SQL · Salesforce |

---

## 1. Executive Summary

Data from the source of truth was not complete, neither verified. We validated data of Salesforce, filled in missing pieces and put in place processes to ensure data quality and complete workflow. I pulled data to Domo BI to further process and created Sales workplace with automated dashboards and reports. As the result, the Company, espeically Leadership and Go-to-market team could rely on one source of truth with real-time data. That also gives every sales rep direct visibility into their own numbers, their team's progress and the company's overall target achivement. 

**Impact at a glance**

✅ Provided one source of truth on the sales numbers, making the whole company aligned on the sales performance, saving times to resolve conflicting reported numbers.

✅ Interactive dashboards provided stakeholders the ability to self-serve when doing more in-depth analysis. 

---

## 2. Business Problem

There was no centralised information within the Company. Salesforce was used to track sales funnels but information was incomplete and not up to date. As the result, each team needed to manage their own records of sales that need to be aligned every month to prepare for Board meeting. Sales rep kept the record of their pipelines in their own spreadsheets and would pass that along in meetings or when requested for Leader's information.  

| Problem | Business impact |
|---|---|
| 🔴 No trust worthy source of sales data | Each team maintained their own version of data that needed to be aligned every month |
| 🔴 No real-time pipeline visibility | Leadership made decisions on week-old Salesforce snapshots — by the time data landed, deals had already moved or been lost |
| 🔴 Salesforce was not used properly | The investment on the platform was not justified |
| 🔴 Finance had no forecast it could rely on | Revenue forecasts were built on intuition rather than weighted pipeline data — committed deals and upside were not differentiated, making board reporting unreliable |
| 🔴 Reps flew blind on their own targets | Sales representatives had no self-serve view of where they stood against quota, their team's trajectory, or the company's overall performance — reducing accountability and motivation |

---

## 3. Methodology

1. 

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
