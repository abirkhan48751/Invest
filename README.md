# InvestPro V1 — Frontend Investment System Demo

A mobile-friendly bilingual (English/Bangla) static prototype for an investment website.

## Included
- Dashboard, sample investment plans, demo balance
- Deposit and withdrawal request forms
- Local demo admin review (approve/reject)
- Transaction history and referral link
- Responsive mobile layout and language toggle
- Browser localStorage persistence

## Run locally
Open `index.html` in a browser. For best results, use a local static server or deploy the folder to a static host.

## Free static hosting
1. Create a GitHub repository and upload the contents of this folder.
2. In Cloudflare Pages, create a project connected to that repository.
3. Choose no framework; build command can be left blank; output directory is `/` (or the repository root, depending on the Pages setup).
4. Deploy and test the generated URL on mobile.

## Critical security limitation
This is **frontend-only demo code**. It does not provide real authentication, a trusted database, an actual admin account, server-side authorization, payment verification, or real deposit/withdrawal processing. Data lives in the visitor's browser and the "admin" view can be accessed by anyone. Never collect real payment details or use this prototype for real-money investment.

Before any real-money deployment, build a trusted backend, server-enforced roles and permissions, audit logs, verified payment provider integration, secure session handling, anti-fraud controls, and legal/compliance review. Do not advertise guaranteed profits. Use a licensed and legally compliant business model.
