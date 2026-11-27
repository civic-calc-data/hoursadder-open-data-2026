# HoursAdder Open Data (2026)

Open CSV datasets covering 2026 US statutory minimum wages and state overtime rules across all 50 states and Washington, D.C., sourced from U.S. Department of Labor Wage and Hour Division (WHD) tables and state labor agencies.

All rates reflect the federal Fair Labor Standards Act (FLSA) floor ($7.25/hr) and state statutory rules verified against DOL WHD updates as of November 2026. Interactive time card, overtime, and payroll hour calculators live at [hoursadder.com](https://hoursadder.com/).

## Datasets in this repository

| File | Coverage | Live report & calculator |
|---|---|---|
| [`data/us-state-minimum-wage-2026.csv`](data/us-state-minimum-wage-2026.csv) | All 50 US states + DC (51 rows, DOL updated `2026-11-05`): state statutory wage, effective minimum wage, spread above $7.25 federal floor, minimum 1.5× overtime floor, notes, and state labor office URL | [US Minimum Wage by State 2026 Report](https://hoursadder.com/reports/us-state-minimum-wage-2026/) / [Time and a Half Calculator](https://hoursadder.com/time-and-a-half-calculator/) |
| [`data/us-state-overtime-rules-2026.csv`](data/us-state-overtime-rules-2026.csv) | All 50 US states + DC (51 rows): weekly overtime threshold, daily overtime threshold, double-time rule, statutory 1.5× overtime floor, state notes, and labor office URL | [US State Overtime Rules 2026 Report](https://hoursadder.com/reports/us-state-overtime-rules-2026/) / [Overtime Calculator](https://hoursadder.com/overtime-calculator/) |

---

## 1. US State Minimum Wages & 1.5× Overtime Floors (2026)

Key findings from [`data/us-state-minimum-wage-2026.csv`](data/us-state-minimum-wage-2026.csv):
- **31 jurisdictions** set an effective minimum wage above the **$7.25/hr** federal FLSA floor.
- **20 states** sit at **$7.25/hr** (matching federal, setting a lower state rate superseded by FLSA, or having no state minimum wage law), giving a **$10.88/hr** statutory 1.5× overtime floor.
- **Highest 2026 effective minimums:**

| Jurisdiction | Effective minimum | Spread over $7.25 | Minimum 1.5× overtime |
|---|---:|---:|---:|
| District of Columbia (DC) | **$18.40** | +$11.15 | $27.60 |
| Washington (WA) | **$17.13** | +$9.88 | $25.70 |
| Connecticut (CT) | **$16.94** | +$9.69 | $25.41 |
| California (CA) | **$16.90** | +$9.65 | $25.35 |
| Hawaii (HI) | **$16.00** | +$8.75 | $24.00 |
| New York (NY, upstate rate) | **$16.00** | +$8.75 | $24.00 |

---

## 2. State Daily Overtime & Double-Time Rules (2026)

From [`data/us-state-overtime-rules-2026.csv`](data/us-state-overtime-rules-2026.csv), while federal FLSA sets a 40-hour weekly threshold, **4 states** enforce general private-sector daily overtime rules:
- **Alaska (AK):** 1.5× after **8 hours/day** (40h/week; exempts employers with fewer than 4 employees).
- **California (CA):** 1.5× after **8 hours/day** and **2× double time** after **12 hours/day** or after 8 hours on the 7th consecutive workday.
- **Colorado (CO):** 1.5× after **12 hours/day** (or 12 consecutive hours) and 40 hours/week.
- **Nevada (NV):** 1.5× after **8 hours/day** (for qualifying wage tiers) and 40 hours/week.

---

## Primary Official Sources

- U.S. Department of Labor (WHD): [State Minimum Wage Laws](https://www.dol.gov/agencies/whd/minimum-wage/state), [Fact Sheet #22: Hours Worked](https://www.dol.gov/agencies/whd/fact-sheets/22-flsa-hours-worked), [Fact Sheet #23: Overtime Pay](https://www.dol.gov/agencies/whd/fact-sheets/23-flsa-overtime-pay)
- eCFR: [29 CFR § 778.104](https://www.ecfr.gov/current/title-29/subtitle-B/chapter-V/subchapter-B/part-778/subpart-B/section-778.104) and [29 CFR § 785.48 (time-clock rounding)](https://www.ecfr.gov/current/title-29/subtitle-B/chapter-V/subchapter-B/part-785/subpart-D/section-785.48)
- State agencies: [California DIR Overtime FAQ](https://www.dir.ca.gov/dlse/faq_overtime.htm), [Alaska DOLWD](https://labor.alaska.gov/lss/whfaq.htm), [Colorado COMPS Order](https://cdle.colorado.gov/sites/cdle/files/2026_comps_order_poster_english_%5Baccessible%5D.pdf)
- IRS: [26 U.S.C. § 225](https://www.law.cornell.edu/uscode/text/26/225) and [Form 1040 Schedule 1-A](https://www.irs.gov/pub/irs-pdf/f1040s1a.pdf)

## Interactive Calculators and Embeds

- Time Card Calculator: https://hoursadder.com/
- Overtime Pay Calculator (50 states + daily/double-time): https://hoursadder.com/overtime-calculator/
- Time and a Half Calculator: https://hoursadder.com/time-and-a-half-calculator/
- No Tax on Overtime Deduction Calculator (26 U.S.C. § 225): https://hoursadder.com/no-tax-on-overtime-calculator/
- Work Hours & Minutes-to-Decimal Chart: https://hoursadder.com/work-hours-calculator/ · https://hoursadder.com/minutes-to-decimal-chart/
- PTO Accrual & Salary-to-Hourly Calculators: https://hoursadder.com/pto-accrual-calculator/ · https://hoursadder.com/salary-to-hourly-calculator/
- Lightweight iframe embeds: `https://hoursadder.com/embed/time-card/`, `https://hoursadder.com/embed/overtime/`, `https://hoursadder.com/embed/time-and-a-half/`

## License and Citation

Licensed under [CC-BY-4.0](LICENSE). Citation metadata is in [`CITATION.cff`](CITATION.cff).

```text
HoursAdder (2026). HoursAdder Open Data 2026: US State Minimum Wages and Statutory Overtime Rules Across All 50 States and DC [Dataset]. https://hoursadder.com/reports/ (CC-BY-4.0).
```
