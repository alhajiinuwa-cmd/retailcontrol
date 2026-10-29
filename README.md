# Retail Control & Compliance

A simple, mobile-first interactive web application for daily shop control, sales reconciliation, cash accountability, and compliance monitoring across six retail shops.

**Businesses:**
- Albarka Harith Foodstuff Enterprises
- Azzahra Fabrics

## Super Simple Deployment on GitHub Pages

This is a single HTML file. No Node.js, no build step, no npm.

### Deploy in 3 Steps

1. Create a new public GitHub repository (e.g. `retail-control`).
2. Upload `index.html` to the root of the repository.
3. Go to **Settings → Pages** and set the source to the main branch root.

Your app will be live at `https://yourusername.github.io/retail-control/` within a minute.

### Local Testing

Just open `index.html` in any browser. No server required.

## Features

- **Login** with all roles (MD/CEO, Compliance Officer, Area Managers, Shop Managers)
- **Daily Shop Control Form** with 7 mandatory Yes/No checks
- Automatic **Sales Reconciliation** and **Cash Accountability** with green/red indicators
- **MD/CEO Dashboard** with outstanding reports, discrepancies, and shop-by-shop table
- **Compliance Officer Dashboard** for reviewing reports and recording findings
- **Monthly Scorecards** (100-point system)
- **Report History**
- Data stored in browser localStorage (demo mode)
- Mobile-first design with large touch targets
- Navy / Green / Red / Amber color system

## Demo Users

Select any role on the login screen:

| Name | Role |
|------|------|
| Hajiya Rabi I. Musa | MD / CEO |
| Abdullahi Saleh Kushaam | Compliance Officer |
| Mubarak | Kubwa Area Manager |
| Lukman | Shop Manager |
| Sani | Dutse Area Manager |
| Salmanu | Shop Manager |
| Usama (Azzahra) | Shop Manager |
| Sadiq | Shop Manager |

## Important Notes

- This is a **demo / prototype**. All data lives only in the browser.
- Submitted reports cannot be silently edited (new submissions lock the day).
- For production use with real multi-user data, connect to a backend (Supabase, Google Sheets, etc.).
- This is an internal control tool. It does not replace Shopkite or a full accounting system.

## Shops

| Shop | Manager | Assistant |
|------|---------|-----------|
| Albarka — Kubwa Shop 1 | Mubarak | Rufa'i |
| Albarka — Kubwa Shop 2 | Lukman | Abdurrahman |
| Albarka — Dutse Shop 1 | Sani | Usama |
| Albarka — Dutse Shop 2 | Salmanu | Hudu |
| Azzahra — Kubwa | Usama | Musa |
| Azzahra — Dutse | Sadiq | Abdulbasir |

---

Built for Albarka Harith Foodstuff Enterprises and Azzahra Fabrics.
