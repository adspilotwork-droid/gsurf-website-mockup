# GSurf Website — Revamped Design (v3)

## 📁 Folder Structure

```
gsurf-website-v2/
│
├── index.html                        ← Homepage
│
└── pages/
    ├── about.html
    ├── contact.html
    ├── coverage.html                 ← Has Popular Hubs section
    ├── business.html
    ├── plans.html
    ├── sitemap.html
    │
    ├── bangalore/
    │   ├── index.html                ← Bangalore City HyperLocal
    │   └── plans.html                ← Bangalore-specific Plans
    │
    ├── hsr-layout/
    │   └── index.html                ← HSR Layout Area Drilldown
    │
    └── btm-layout/
        └── index.html                ← BTM Layout Area Drilldown
```

## 🧭 Hierarchy

```
Homepage
│
├── Fiber Plans / Business / Coverage / About / Contact
│
└── Bangalore  (pages/bangalore/)
    ├── Bangalore Plans
    ├── HSR Layout  (pages/hsr-layout/)
    └── BTM Layout  (pages/btm-layout/)
```

## ✅ What Was Updated (v3)

- Chennai → Bangalore (city page, all content, title, office address, hotline)
- Adyar → HSR Layout (area page, all content, local landmarks, team location)
- T. Nagar → BTM Layout (area page, all content, pincode, landmarks)
- Coverage page: Bangalore card is now a clickable link
- Coverage page: New "Popular Hubs" section with HSR Layout + BTM Layout cards
- Footer and nav updated sitewide across all 11 pages
- Internal links: HSR + BTM pills inside Bangalore page are clickable

## 📌 Developer Notes

- To add more areas under Bangalore: copy `pages/hsr-layout/` → `pages/koramangala/`, update content, add card to Coverage Popular Hubs + Bangalore coverage grid
- All links use relative paths — no domain hardcoded
