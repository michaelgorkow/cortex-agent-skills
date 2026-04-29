# MEDDPICC Coach Skill

A Cortex Agent skill that scores deals against the [MEDDPICC framework](https://www.meddpicc.com/) and provides actionable coaching advice. It evaluates each of the 7 dimensions (Metrics, Economic Buyer, Decision Criteria, Decision Process, Implicate Pain, Champion, Competition) on a 1–5 scale and highlights gaps with specific next actions.

## How It Works

1. Provide a free-text deal summary describing your opportunity.
2. The skill scores each MEDDPICC dimension based on the evidence present.
3. You receive a scorecard, top gaps, and a coaching summary with concrete next steps.

## Example

### Input

> We're working a $400K expansion opportunity with Acme Corp for their data lakehouse migration. They're currently on Databricks and experiencing performance issues with their BI workloads. Our main contact is Sarah Chen, a Senior Data Engineer who reached out to us after seeing a Snowflake webinar. She's been great at getting us meetings but reports to a Director who reports to the VP of Data. We haven't met the VP yet. Sarah says they want "better performance and lower costs" but we don't have specific numbers. They're evaluating us alongside Databricks (staying put) and possibly Google BigQuery. Sarah mentioned they'd like to make a decision by end of Q3 but there's no formal procurement process documented. We did a POC last month that went well

### Output

## MEDDPICC Deal Assessment: Acme Corp — $400K Data Lakehouse Migration

### MEDDPICC Scorecard

| Dimension | Score | Summary |
|-----------|-------|---------|
| **Metrics** | 2/5 | Only qualitative goals ("better performance and lower costs") — no specific KPIs, dollar amounts, or time-based targets quantified. POC results not translated to business metrics. |
| **Economic Buyer** | 1/5 | VP of Data is likely the EB but has not been identified by name or engaged. You're two levels removed, working through a Senior Data Engineer. No confirmed budget authority. |
| **Decision Criteria** | 2/5 | Performance and cost are assumed criteria, but nothing formal or validated. No understanding of weighting, must-haves vs. nice-to-haves, or evaluation rubric. |
| **Decision Process** | 2/5 | Loose "end of Q3" timeline from Sarah with no formal procurement process documented. No known approval steps, sign-off chain, legal/security reviews, or procurement involvement. |
| **Implicate Pain** | 2/5 | Surface-level pain identified ("performance issues with BI workloads") but not connected to measurable business impact — no data on revenue loss, delayed decisions, analyst productivity, or SLA breaches. |
| **Champion** | 3/5 | Sarah is engaged and proactively arranging meetings, which shows initiative. However, as a Senior Data Engineer she has limited organizational power and no documented personal win tied to this deal. |
| **Competition** | 3/5 | Competitors identified (Databricks status quo + possibly BigQuery), but no differentiation strategy, no understanding of incumbent relationships, and no insight into how Acme perceives each option. |

**Overall Score: 15/35** — 🔴 **At Risk**

---

### Top 3 Gaps

**1. Economic Buyer (1/5) — CRITICAL**
You have zero engagement with the person who controls budget. At $400K, this will absolutely require VP-level (or higher) sign-off. Sarah getting you meetings is helpful, but if the VP of Data has a different agenda or a strong Databricks relationship, this deal dies without you ever knowing why.

> **Next action:** Ask Sarah directly: *"For an investment of this size, who ultimately approves the budget and signs the contract? Can you tell me about the VP of Data — what are their top priorities this year? What would make them personally excited about this project?"* Then work with Sarah to architect an executive briefing or sponsor session with the VP within the next 2 weeks.

**2. Metrics (2/5) — CRITICAL**
Without quantified business outcomes, you can't build an ROI case, you can't arm your champion, and you can't differentiate against "just stay on Databricks." The POC is a wasted asset if you don't translate it into dollars.

> **Next action:** Go back to the POC results and quantify everything. Ask Sarah: *"When your BI workloads underperform today, what's the downstream impact? How many analysts are affected? How many hours per week are lost waiting on queries? What's the cost of the Databricks environment today — compute, storage, support?"* Build a before/after comparison from the POC with dollar values.

**3. Implicate Pain (2/5)**
"Performance issues" is a technical complaint, not a business problem. Until you connect slow BI workloads to executive-level pain (missed revenue targets, poor customer experience, compliance risk, inability to scale), the VP of Data has no urgency to act — and the status quo wins.

> **Next action:** Ask Sarah: *"When BI reports are slow or delayed, who in the business feels it? Has there been a specific incident where a slow dashboard or failed report caused a real problem — a missed deadline, a bad decision, an escalation?"* Document these stories in the customer's own words and use them to build the narrative for the EB meeting.

---

### Coaching Summary

**This deal is in a precarious position.** You have a willing contact and a successful POC, which are real assets — but you're operating in a dangerous comfort zone. The biggest red flag is that a $400K deal is progressing without any engagement with the economic buyer, and your "champion" doesn't have the organizational gravity to push this through on her own. The end-of-Q3 timeline is Sarah's aspiration, not a validated business deadline — which means this deal can easily slip or go dark.

**🎯 The single most important thing to do this week:** Have an honest conversation with Sarah to gauge her willingness and ability to get you a meeting with the VP of Data. Ask her: *"If you were presenting this to the VP today, what would their biggest concern be?"* Her answer will tell you whether she's truly a champion or just an enthusiastic user. If she can't or won't facilitate that executive access, you need to find another path in — through your own executive network, an AE-to-VP outreach, or a different internal sponsor.
