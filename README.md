# GSurf Website — Revamped Design

This repository contains the redesigned HTML pages for the GSurf fiber broadband website.

---

## 📁 Folder Structure

```
gsurf-website/
│
├── index.html                    ← Homepage (Root)
│
├── pages/
│   ├── about.html                ← About Us
│   ├── contact.html              ← Contact Us
│   ├── coverage.html             ← Coverage Page
│   ├── business.html             ← Business Page
│   ├── plans.html                ← Common Plans Page
│   ├── sitemap.html              ← HTML Sitemap
│   │
│   ├── chennai/
│   │   ├── index.html            ← Chennai City HyperLocal Page
│   │   └── plans.html            ← Chennai Plans Page
│   │
│   ├── adyar/
│   │   └── index.html            ← Adyar Area Drilldown Page
│   │
│   └── t-nagar/
│       └── index.html            ← T. Nagar Area Drilldown Page
```

---

## 🧭 Page Hierarchy (How pages are connected)

```
Homepage (index.html)
│
├── About Us
├── Contact Us
├── Coverage
├── Business
├── Plans (Common)
├── Sitemap
│
└── Chennai (City Level)
    ├── Chennai Plans
    ├── Adyar (Area Level)
    └── T. Nagar (Area Level)
```

---

## 📌 Notes

- All pages are **static HTML** — no backend or database required.
- Styling uses **Tailwind CSS** loaded via CDN — no separate CSS files needed.
- To add more city/area pages, follow the same folder pattern: `pages/{city-name}/index.html`
- Images currently use hosted URLs (Google-hosted). These should be replaced with actual brand assets before going live.

---

## 🚀 Viewing Locally

Just open `index.html` in any browser. All pages work independently.

---

*Prepared for: GSurf Fiber Connectivity*
