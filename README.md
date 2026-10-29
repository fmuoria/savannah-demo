# Savannah product demo

This is a clickable 5-step walkthrough of Savannah, a system that predicts medicine stock-outs in hospitals, drafts purchase orders and pools orders across hospitals for bulk discounts.

**All data in this demo is simulated.** No patient or hospital data is used.

## Steps

The demo opens on an intro screen that sets out the problem. It then walks through five steps:

1. **Prescriptions in.** Raw prescription entries become structured consumption events.
2. **Forecast.** Stock on hand compared with forecast daily use, with a stock-out warning 14 days ahead.
3. **Purchase order.** The order quantity is worked out from the forecast, the 6-day supplier lead time and safety stock.
4. **Group buying.** Demand from 5 facilities is pooled to reach Tier 1 distributor pricing (12% lower).
5. **Impact.** Quarterly KPIs for hospital finance and medical directors.

Use the **Next** and **Back** buttons or the arrow keys to move between steps. To open a specific step directly, add `#step-3` (or any step number) to the end of the URL.

## Running it

The whole demo is one file, `index.html`, with no build step and no server. You can open it in any browser or host it on GitHub Pages.
