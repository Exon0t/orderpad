# OrderPad — UGE Supply Preorder

Single-file web app that recreates the **UGE Supplies – Preorder Form** as a mobile
tool: enter quantities, generate a PDF that matches the paper form, and share it.

## Live app
Once GitHub Pages is enabled: **https://exon0t.github.io/orderpad/**

- **iPhone / iPad:** open the link in **Safari** → Share → **Add to Home Screen**.
  Launches full-screen with the OrderPad icon; "Generate & Send PDF" uses the
  native iOS share sheet.
- **Android:** open in Chrome → menu → **Add to Home Screen** (or install the
  native APK from the `OrderPad` Android project).

## What it does
- Items in the order of the printed form, with tiers (how often you order):
  **T1** = yellow (most frequent), **T2**/**T3** below.
- Tap **✎** to reorder, change tier, rename, add/delete items — saved locally.
- Generates `UGE Order Form M.D.YYYY.pdf` (self-contained PDF engine, works offline).

Source of truth for the UI lives at `uge/apps/order-form/index.html` in Anthony's
projects; this repo is the hosted copy.
