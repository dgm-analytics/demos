# dgm-demos

Sample analytics dashboards for DGM Analytics client prospects.

Live at: [demos.dgmanalytics.com](https://demos.dgmanalytics.com)

## Structure

```
dgm-demos/
├── index.html              # Main landing page — lists all demos
├── dosie/
│   └── index.html          # Dosie health tech — launch analytics plan
├── restaurant/
│   └── index.html          # Restaurant — revenue & labor (coming soon)
├── salon/
│   └── index.html          # Salon & barbershop — chair analytics (coming soon)
├── retail/
│   └── index.html          # Retail — inventory & revenue (coming soon)
├── tattoo/
│   └── index.html          # Tattoo studio — artist analytics (coming soon)
└── hvac/
    └── index.html          # HVAC & services — job metrics (coming soon)
```

## Adding a new demo

1. Create a folder with the client or vertical name: `mkdir new-client`
2. Add `index.html` inside it with the dashboard
3. Add a card for it in the root `index.html` demo grid
4. Commit and push — GitHub Pages deploys automatically

## Deployment

Hosted via GitHub Pages. Custom domain configured via CNAME record pointing `demos.dgmanalytics.com` to GitHub Pages.

To update: commit changes to `main` and push. Pages redeploys within ~60 seconds.

---

DGM Analytics · dexter@dgmanalytics.com · Birmingham, AL
