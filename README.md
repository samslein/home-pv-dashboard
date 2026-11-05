# Home PV Dashboard

A standalone dashboard for the home PV systems, imported monthly meter and inverter history, and net-metering outlook.

## Open the dashboard

Open `index.html` in a modern browser. It is self-contained and does not require a build step or external service. The page includes the monthly history currently bundled through November 5, 2026. Later Iammeter CSV imports are stored in that browser's local storage. On a phone, use **Switch to mobile view** for the compact layout; your choice is saved in that browser.

## Publish with GitHub Pages

1. In the repository, open **Settings** → **Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then click **Save**.
4. After deployment completes, open the site URL shown on that page. GitHub Pages uses the top-level `index.html` as the site entry page.

## Current system notes

- House: 5.11 kWp; Growatt MOD 6000TL3-XH from November 3, 2026 (first full day), following the 5000TL3-S.
- Barn: 10.35 kWp; Growatt MOD 8000TL3-XH from October 20, 2026 (first full day), following the MOD 6000TL3-XH. The 5.50 kWp NE array was added October 6, 2026.
- Net-metering return: 80% through October 5, 2026; 70% from October 6 onward.

## Privacy

This repository contains home energy history. Keep it private unless you intentionally want those household production and consumption records to be public.
