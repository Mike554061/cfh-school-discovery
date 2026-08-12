# Chefs For Hire — School Schedule · 2026 Fall Discovery

Login-gated schedule + route fact-find for the Chefs For Hire school accounts
(13 stops across 3 driver routes; origin = CFH Production, 3619 Walton Ave, Cleveland).

- Per-school throttle on/off, editable delivery days, window (start→stop), notes,
  and holiday schedule. No contact fields.
- Route map + per-driver loops with live OSRM drive times (straight-line fallback).
- Shared, persistent record with append-only audit (Apps Script disc_set/disc_get, ns=cfh).
- Gate reuses the shared SupplyNow endpoint (SITE=cfh).

Single self-contained index.html. .nojekyll required for GitHub Pages.
