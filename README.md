# VUSA Consultancy — Website

Single-page editorial website for VUSA Consultancy. Static HTML, zero build step, deploys anywhere.

## Files
- `index.html` — full site (HTML, CSS, JS in one file)
- `vercel.json` — Vercel config with security headers
- `assets/vusa-logo.png` — brand mark

## Deploy to Vercel (recommended)

1. Push this folder to a GitHub repo
2. In Vercel: New Project → Import Git Repo → select repo
3. Framework preset: **Other** (no build needed)
4. Deploy. Done.

## Connect your Wix domain

1. In Vercel project: Settings → Domains → Add `vusaconsultancy.com`
2. Vercel shows two records to add:
   - A record: `@` → `76.76.21.21`
   - CNAME: `www` → `cname.vercel-dns.com`
3. Log into Wix → Domains → manage DNS → paste those records
4. Wait 10–60 minutes. SSL provisions automatically.

## Import to Lovable

1. Lovable: New Project → Import code
2. Paste the contents of `index.html` or upload the folder
3. Lovable will recognise it as a static HTML project. Edit visually from there.

## Editing notes

- All colours are CSS variables at the top of `<style>` — change once, applies everywhere
- Fonts loaded from Google Fonts (Fraunces + Inter Tight)
- Logo is rendered as inline SVG in the nav for crispness; the PNG is in `/assets` for fallback
- Replace `contact@vusaconsultancy.com` once your VUSA domain email is set up
- Companies House number, registered name, and copy are accurate to current records
- 
