# WG KPI Audit Platform

WeMasterTrade Audit Operations — KPI payout audit tool (v2.0, Nov 2026).

**3-step calculation**
1. **Marketing KPI** → Actual Base = Agreed Base × MKT %
2. **Attendance** → Attendance Salary = Actual Base × min(actual, standard) / standard days
3. **Sales KPI Hold** (on Attendance Salary)

| Month | Hold |
|---|---|
| 1 · Probation | 0% — no KPI (MKT = 100%, Sales = Exempt) |
| 2 · 1st miss | 20% |
| 3 · 2nd consecutive miss | 30% |
| 4 · 3rd consecutive miss | 50% |
| 5+ · Still missing | Commission-only / Zero Base |

Target met → no hold, tier resets to 20%. Standby Safety Net suspends hold (tenure ≥ 6m, 1 use / 3 months).

Features: probation toggle & filter, policy ladder, EN/VI toggle, PH/VN/TR regions, batch audit table, Excel export with live formulas, copy-as-table.

## Run
Static single file — no build step. Open `index.html` in a browser, or deploy with GitHub Pages:
**Settings → Pages → Source: Deploy from a branch → `main` / root**.

Dependencies load from CDN (React 18.3.1, Babel 7.23.9, Tailwind 3.4.17, SheetJS 0.18.5).

> Batch data is mock data for preview only.
