# bushraanjum_2511048_part2_kpi_experiment

# README.md

# Experiment Evaluation: Onboarding Campaign Impact

## Student Information
**Name:** Bushra Anjum
**Student ID:** 2511048  
**Repository:** bushraanjum_2511048_part2_kpi_experiment 

---

## Executive Summary
This project investigates whether a redesigned onboarding and activation campaign improves subscription conversion and early engagement compared to the existing onboarding process.  

The analysis applies a KPI framework to identify the **North Star Metric**, evaluates experiment outcomes, and considers **guardrail metrics** to ensure sustainable growth. Results show that the Treatment group achieved **higher conversion, stronger engagement, and increased revenue**, with risks remaining within acceptable limits.  

**Recommendation:** Launch the new onboarding experience, supported by ongoing monitoring of refund and support metrics.

---

## Business Context
The company operates a subscription‑based digital product. User onboarding is a critical driver of conversion and long‑term retention.  

To test improvements, an A/B experiment was conducted:  
- **Control Group:** Existing onboarding flow  
- **Treatment Group:** New campaign experience  

Leadership must decide whether to roll out the Treatment experience to all users.

---

## Business Problem Statement
The decision at hand: **Should the new onboarding campaign be launched to all users?**  

This decision impacts:  
- **Revenue growth** through higher paid conversions  
- **Customer acquisition quality**  
- **Product adoption and engagement**  
- **Customer experience and satisfaction**  

The **success metric** is **Paid Conversion Rate**, supported by engagement and revenue measures. Guardrail metrics (refunds, support tickets) must be monitored to avoid unintended risks.  

Evidence required:  
- Statistically significant uplift in conversion  
- Positive revenue impact  
- No major increase in refunds or support burden  

---

## Dataset Overview
The dataset (`campaign_experiment_data.xlsx`) contains user‑level experiment results.  

**Key Features:**  
- User demographics: Region, Device, Traffic Source, Plan Type  
- Funnel progression: Landing Page Visit → Trial Start → Onboarding Completion → Paid Conversion  
- Financial outcomes: 30‑day Revenue, Refund Requests  
- Operational signals: Support Tickets  
- Behavioral signals: Days to Convert, Engagement Score  

---

## KPI Framework
### North Star Metric
**Paid Conversion Rate** — percentage of users converting to paid subscriptions.  

### Primary Drivers
1. **Acquisition Quality**  
   - Landing Page Visit Rate  
   - Trial Start Rate  

2. **Onboarding Effectiveness**  
   - Onboarding Completion Rate  
   - Days to Convert  

3. **Revenue Performance**  
   - Average Revenue per User  
   - Revenue per Converted User  

### Guardrail Metrics
- Refund Rate  
- Support Ticket Rate  
- Engagement Score  

---

## Data Validation
Before analysis, the dataset was validated:  
- No duplicate User IDs  
- Balanced group sizes (Control vs Treatment)  
- Binary fields checked for consistency  
- Revenue outliers reviewed  
- Segment distributions (region, device, plan type) confirmed balanced  

---

## Experiment Results
| Metric                   | Control | Treatment |
| ------------------------ | ------- | --------- |
| User Count               | 693     | 715       |
| Paid Conversion Rate     | 3.17%   | 6.99%     |
| Average Revenue per User | 51.75   | 53.88     |
| Refund Rate              | 0.00%   | 0.42%     |
| Engagement Score         | 57.03   | 62.93     |

**Highlights:**  
- Conversion rate more than doubled in Treatment group  
- Revenue per user increased modestly  
- Engagement score improved significantly  
- Refund rate rose slightly but remained low  

---

## Hypothesis Testing
- **Null Hypothesis (H0):** Treatment does not improve conversion  
- **Alternative Hypothesis (H1):** Treatment improves conversion  
- **Test Type:** One‑tailed test at α = 0.05  
- **Result:** p‑value < 0.05 → Reject H0 → Treatment improves conversion  

---

## Recommendation
**Decision: Launch Treatment Onboarding Experience**  

Rationale:  
- Conversion uplift is statistically significant  
- Revenue and engagement improved  
- Guardrail metrics remain acceptable  

---

## Risks & Limitations
### Risks
- Long‑term churn not yet visible  
- Potential increase in refunds if conversion quality declines  
- Operational load may shift post‑launch  

### Limitations
- Results limited to experiment population  
- 30‑day revenue window may not capture lifetime value  
- Requires continuous monitoring after rollout  

---

## Next Steps
1. Roll out Treatment onboarding to all users  
2. Monitor refund and support ticket rates closely  
3. Track retention and revenue quality over time  
4. Run follow‑up experiments to optimize onboarding further  

---

## Conclusion
The experiment demonstrates that the new onboarding campaign delivers **meaningful improvements in conversion, engagement, and revenue**. Risks are manageable, and evidence supports a **full rollout** with ongoing monitoring.  
