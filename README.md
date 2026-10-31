# EPPU Drill Manager (demo)

A free, self-contained demo of an emergency-drill lifecycle app for a hospital
emergency-preparedness unit. It is a prototype to agree the solution before it is rebuilt on SAP BTP.

It covers the whole drill lifecycle:

1. **Schedule and changes:** annual plan from frequency rules, proponent date picking with checks,
   OEMC approval, copy for MOH / MSMD, change control with the original date kept.
2. **Script and drill day:** scenario script with a story vs event-list check and OEMC review;
   observer drill-day screen (checklist, participants by badge, findings, result).
3. **Report and gaps:** After Action Report with 8 continuity checks and 4 timed signatures;
   gaps with owner, type and due date, escalation at 30/60/90 days, mock SAP maintenance and Datix links;
   KPI dashboard and a handover pack (data model, roles, rules, sample data download) for the SAP team.

- Open `index.html` in any browser. No sign-in, no install.
- All data is fictional sample data. Changes are saved only in your browser; **Reset** restores the sample.
- "View as" in the header switches between the seven roles. "Load mid-year" on Overview shows half a year of history.
