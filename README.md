# GSurf Website — Revamped Design (Linked & Ready)

## 📁 Folder Structure

```
gsurf-website-v2/
│
├── index.html                        ← Homepage
│
└── pages/
    ├── about.html                    ← About Us
    ├── contact.html                  ← Contact / Support
    ├── coverage.html                 ← Coverage Map
    ├── business.html                 ← Business Solutions
    ├── plans.html                    ← Common Plans
    ├── sitemap.html                  ← HTML Sitemap
    │
    ├── chennai/
    │   ├── index.html                ← Chennai City HyperLocal Page
    │   └── plans.html                ← Chennai-Specific Plans
    │
    ├── adyar/
    │   └── index.html                ← Adyar Area Drilldown
    │
    └── t-nagar/
        └── index.html                ← T. Nagar Area Drilldown
```

## 🧭 Page Hierarchy

```
Homepage
│
├── Fiber Plans (Common Plans)
├── Business
├── Coverage
├── Support / Contact
├── About Us
├── Sitemap
│
└── Chennai  ← City hub
    ├── Chennai Plans
    ├── Adyar
    └── T. Nagar
```

## ✅ What Was Fixed

- **Logo** — GSurf brand image applied in header & footer on all 11 pages
- **Nav bar** — Fully consistent across every page; all links working
- **Footer** — Consistent across every page with full nav links including Chennai, Adyar, T. Nagar
- **Mobile menu** — Hamburger toggle working on all pages
- **Relative paths** — Correct for every page depth (root / pages / pages/city)

## 📌 Notes for Developer

- All pages are static HTML — no backend needed
- Tailwind CSS loaded via CDN — no build step required
- Logo is embedded as base64 — no separate image file needed
- To add a new city (e.g. Velachery): copy `pages/adyar/` → `pages/velachery/`, update content, add link to Chennai page and footer
- Images in page body still use Google-hosted URLs — replace with actual CDN/brand assets before go-live

## 🚀 Push to GitHub Pages

```bash
git init
git add .
git commit -m "Revamped design — linked, logo fixed"
git branch -M main
git remote add origin https://github.com/YOUR_ORG/gsurf-website.git
git push -u origin main
```

Then enable GitHub Pages from repo Settings → Pages → Deploy from `main` branch root.

---
*GSurf Velocity Fiber — Revamp v2*
