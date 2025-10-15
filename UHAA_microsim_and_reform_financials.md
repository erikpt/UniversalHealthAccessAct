# Microsimulation Results (Co-pays by Income Tier)
Assumptions: ~130M tax units; AGI distribution {60%,30%,8%,2%} with average AGIs {$45k,$120k,$280k,$1.2M}. Utilization and co-pay schedules per Section 4(d); 5% of AGI annual OOP cap applied per unit; partial preventive exemption for primary care and labs.

| AGI Tier    | Tax Units   | Avg AGI    | Gross Co-pays / Unit   | 5% AGI Cap / Unit   | Net Co-pays / Unit   |   Total Co-pays (B) |
|:------------|:------------|:-----------|:-----------------------|:--------------------|:---------------------|--------------------:|
| <= $75k     | 78,000,000  | $45,000    | $228                   | $2,250              | $228                 |                17.8 |
| $75k–$200k  | 39,000,000  | $120,000   | $536                   | $6,000              | $536                 |                20.9 |
| $200k–$500k | 10,400,000  | $280,000   | $1,136                 | $14,000             | $1,136               |                11.8 |
| >$500k      | 2,600,000   | $1,200,000 | $1,822                 | $60,000             | $1,822               |                 4.7 |

**Total net co-pays (microsim): ~$55.2B**

---
# Re-modeled Financials (with proposed gap-closers)
- Indexation updated to **core CPI** (not CPI-M) for growth caps and automatic adjustments (affects forward growth, not this 2026 snapshot).
- Added inflows: **Medicare Parts B/D general revenues** (≈$750B), **Medicaid Fed+State MOE** (≈$950B), **Employer MOE** (≈7.5% of payroll ≈ $998B).
- Additional outlay savings: **Site-neutral ($60B)** + **Global budgets ($90B)** + **Drug expansion ($40B)** = **$190B** per year.

## Inflows vs Outflows (billions) — central employee rate 7%
- **Inflows (mid): ~$5,783B**
- **Outflows (reform): ~$5,089B** (base $5,279B minus $190B new savings)
- **Balance (mid): ~$693B**

### Range with employee rate at 5% and 9.5%
- **Inflows (5%): ~$5,517B** → Balance **~$427B**
- **Inflows (9.5%): ~$6,116B** → Balance **~$1,026B**