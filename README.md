# WG KPI Audit Platform

WeMasterTrade Audit Operations — KPI payout audit tool (v2.0, Nov 2026).

**3-step calculation**
1. **Marketing KPI** → Actual Base = Agreed Base × MKT %
2. **Attendance** → Attendance Salary = Actual Base × min(actual, standard) / standard days
3. **Sales KPI Hold** → 20% / 30% / 50% hold by consecutive-miss tier (Standby Safety Net suspends hold: tenure ≥ 6m, 1 use / 3 months)

Features: EN/VI toggle, PH/VN/TR regions, batch audit table, Excel export with live formulas, copy-as-table.

## Run
Static single file — no build step. Open `index.html` in a browser, or deploy with GitHub Pages:
**Settings → Pages → Source: Deploy from a branch → `main` / root**.

Dependencies load from CDN (React 18.3.1, Babel 7.23.9, Tailwind 3.4.17, SheetJS 0.18.5).

> Batch data is mock data for preview only.
