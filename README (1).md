# Dealer Watch: which dealers need management attention

Static prototype (one file, no backend) that triages an OEM dealer network using synthetic data.

**Flow:** monthly dealer data → 4 separate flags (Sales, Inventory, Financial, Customer) → cause check (supply / weak market / dealer execution / OEM-pushed stock) → ₹ exposure and tier → recommended action.

## Run
Open `index.html`, or publish: Settings → Pages → Deploy from branch → main → / (root).

## Pages
Dealer Triage (KPIs, sliders, ranked list, OEM-side tab, CSV download) · Dealer Detail (why flagged, charts) · How it works · Assumptions

## Key assumptions
Synthetic data (seeded, 49 dealers, Oct 2025 to Sep 2026). Stock valued at ex-GST cost. 80/20 bank/dealer funding at 10% (sensitivity at 70/30 and 90/10). Thresholds are judgment-based and adjustable.

## Key limitation
Flags are evidence for a conversation, not proof of cause. Thresholds need calibration on real data.

## Not included
CRM funnel, sentiment, ERP CSV upload (next steps).
