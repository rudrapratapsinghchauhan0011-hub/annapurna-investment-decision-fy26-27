```
{
 "meta": {
  "company": "Annapurna Foods Pvt. Ltd.",
  "decision": "FY2026-27 incremental investment",
  "currency": "INR crore",
  "prepared_for": "CFO",
  "data_status": "fictional case data"
 },
 "options": [
  {
   "id": "A",
   "name": "Quick commerce",
   "investment_cr": 15,
   "incremental_revenue_cr": 30,
   "cm_pct": 12,
   "incremental_contribution_cr": 3.6,
   "contribution_per_rs1": 0.24,
   "receivable_days": 15,
   "incremental_receivables_cr": 1.23,
   "receivables_guardrail_pass": true
  },
  {
   "id": "B",
   "name": "Modern trade",
   "investment_cr": 15,
   "incremental_revenue_cr": 22,
   "cm_pct": 14,
   "incremental_contribution_cr": 3.08,
   "contribution_per_rs1": 0.205,
   "receivable_days": 55,
   "incremental_receivables_cr": 3.32,
   "receivables_guardrail_pass": false
  },
  {
   "id": "C",
   "name": "General trade, Tier-2/3",
   "investment_cr": 15,
   "incremental_revenue_cr": 26,
   "cm_pct": 22,
   "incremental_contribution_cr": 5.72,
   "contribution_per_rs1": 0.381,
   "receivable_days": 38,
   "incremental_receivables_cr": 2.71,
   "receivables_guardrail_pass": true
  }
 ],
 "weights": {
  "base": {
   "contribution_margin": 0.3,
   "growth_potential": 0.25,
   "working_capital": 0.15,
   "execution_risk": 0.15,
   "brand_price_control": 0.15
  },
  "growth_40": {
   "contribution_margin": 0.2,
   "growth_potential": 0.4,
   "working_capital": 0.15,
   "execution_risk": 0.15,
   "brand_price_control": 0.1
  }
 },
 "scores": [
  {
   "option": "A",
   "criterion": "contribution_margin",
   "weight": 0.3,
   "score": 2.73,
   "justification": "CM 12% (34% GM - 22% commission), lowest of three"
  },
  {
   "option": "A",
   "criterion": "growth_potential",
   "weight": 0.25,
   "score": 5.0,
   "justification": "Rs 30 cr incremental and channel +85% YoY, but 2.5x the current Rs 12 cr base"
  },
  {
   "option": "A",
   "criterion": "working_capital",
   "weight": 0.15,
   "score": 5.0,
   "justification": "15 days gives Rs 1.23 cr receivables, best"
  },
  {
   "option": "A",
   "criterion": "execution_risk",
   "weight": 0.15,
   "score": 2,
   "justification": "Platform dependence, discounting pressure, high ad costs"
  },
  {
   "option": "A",
   "criterion": "brand_price_control",
   "weight": 0.15,
   "score": 2,
   "justification": "Platforms control price, visibility and discounts"
  },
  {
   "option": "B",
   "criterion": "contribution_margin",
   "weight": 0.3,
   "score": 3.18,
   "justification": "CM 14% (28% GM - 14% trade spend)"
  },
  {
   "option": "B",
   "criterion": "growth_potential",
   "weight": 0.25,
   "score": 3.67,
   "justification": "Rs 22 cr incremental; channel only +11% YoY"
  },
  {
   "option": "B",
   "criterion": "working_capital",
   "weight": 0.15,
   "score": 1.36,
   "justification": "55 days gives Rs 3.32 cr, breaches Rs 3 cr cap alone"
  },
  {
   "option": "B",
   "criterion": "execution_risk",
   "weight": 0.15,
   "score": 4,
   "justification": "Few counterparties, familiar negotiation; fee and payment friction"
  },
  {
   "option": "B",
   "criterion": "brand_price_control",
   "weight": 0.15,
   "score": 3,
   "justification": "Chains demand promo funding but MRP and shelf layout largely held"
  },
  {
   "option": "C",
   "criterion": "contribution_margin",
   "weight": 0.3,
   "score": 5.0,
   "justification": "CM 22% (31% GM - 9% trade spend), highest and above 18.5% blended"
  },
  {
   "option": "C",
   "criterion": "growth_potential",
   "weight": 0.25,
   "score": 4.33,
   "justification": "Rs 26 cr incremental; channel +6% YoY so growth is new outlets"
  },
  {
   "option": "C",
   "criterion": "working_capital",
   "weight": 0.15,
   "score": 1.97,
   "justification": "38 days gives Rs 2.71 cr, within cap"
  },
  {
   "option": "C",
   "criterion": "execution_risk",
   "weight": 0.15,
   "score": 3,
   "justification": "Known channel but 25,000 outlets across 4 states; distributor credit risk"
  },
  {
   "option": "C",
   "criterion": "brand_price_control",
   "weight": 0.15,
   "score": 3,
   "justification": "Distributor-led pricing; moderate leakage risk in Tier-2/3"
  }
 ],
 "weighted_totals": {
  "base": {
   "A": 3.42,
   "B": 3.13,
   "C": 3.78
  },
  "growth_40": {
   "A": 3.8,
   "B": 3.21,
   "C": 3.78
  }
 },
 "ranking": {
  "base": [
   "C",
   "A",
   "B"
  ],
  "growth_40": [
   "A",
   "C",
   "B"
  ]
 },
 "recommendation": {
  "allocation_cr": {
   "A": 4,
   "B": 0,
   "C": 11,
   "total": 15
  },
  "incremental_revenue_cr": 27.07,
  "incremental_contribution_cr": 5.15,
  "incremental_receivables_cr": 2.31,
  "blended_cm_pct_after": 18.58,
  "blended_cm_pct_before": 18.52,
  "guardrails_pass": true,
  "rationale": "C leads on the base weights; A is a growth and cash hedge capped at Rs 4 cr to keep blended CM undiluted; B excluded (lowest score, breaches receivables cap alone). Under growth_40, A edges C by 0.02 (a tie), so the mix is kept."
 },
 "assumptions": [
  "Revenue, contribution and receivables scale linearly with investment",
  "Incremental sales earn each channel's current CM% and receivable days",
  "Option figures are stand-alone Rs 15 cr; splits in Rs 1 cr steps",
  "Quantitative scores = 5 x value / best value; execution and brand scores are analyst judgement"
 ],
 "data_gaps": [
  "Existing receivables base and payment behaviour by channel",
  "Ad spend and cost-to-serve detail for quick commerce",
  "Diminishing returns and ramp timing of incremental revenue",
  "Split of the Rs 15 cr between spend and working capital",
  "Distributor credit exposure in Tier-2/3 states",
  "Cannibalisation between channels"
 ],
 "confidence": {
  "level": "medium",
  "reasons": [
   "Arithmetic is checkable and guardrails pass",
   "Linear scaling and judgement scores are untested",
   "Growth_40 run nearly flips the top rank"
  ]
 }
}
```