# Grants Page — How to Add to Your Existing Website

## Files in this package:
- `grants.html` — The new Grants & Funding page (complete)
- `js/components.js` — Updated nav component with "Grants" link added

## Steps to update your existing site:

1. **Add `grants.html`** to your repo root (same folder as index.html, research.html, etc.)

2. **Replace `js/components.js`** with the updated version in this package.
   This adds "Grants" to the navigation bar on every page automatically.

3. Push to GitHub / re-upload to Netlify — done!

## Page sections:
- Summary strip (Active Awards / Under Review / In Pipeline / Collaborating Institutions)
- Active Awards: American Heart Association (Co-PI grant)
- Under Review: MIDAS PODS 2026, UM Bold Challenges A2D2 Boost, PMRC Fellowship
- In Development pipeline: NSF ISP, NSF ERI, Industry (Autonomous Systems), NIH R21
- Collaboration CTA at the bottom

## To update grant status:
Find the grant card and change the class on the left-border div:
- `grant-card active`    → green left border (Active award)
- `grant-card submitted` → gold left border  (Under review)
- `grant-card pending`   → blue left border  (In development)

And update the status pill class:
- `status-active` / `status-submitted` / `status-pending` / `status-pipeline`
