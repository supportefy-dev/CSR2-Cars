# CSR2 Cars — Complete Car Database & Tuning Guide

A comprehensive static website for **CSR Racing 2** — the popular mobile drag racing game. Browse all 740+ cars with their best tune settings, shift patterns, and performance data.

## What's Inside

- **740+ Car Pages** (`/car/`) — individual pages for every car in CSR2, each with:
  - Best tune (Nitro, Final Drive, Tire pressure)
  - Optimal shift pattern
  - Best time on 1/2 mile
- **Cars Index** (`cars.html`) — full sortable/searchable car database
- **Finder** (`finder.html`) — car finder tool
- **Blog** (`blog/`) — guides and news
- **Event Calendar** (`calendar.html`) — in-game event schedule
- **Shop** (`shop.html`) — in-game shop tracker
- **Auth Pages** — login, register, password recovery UI
- **3D Car Viewer** (`cars3ddb.html`)

## Tech Stack

- HTML5 / Bootstrap 4
- Vanilla JavaScript
- ApexCharts (performance charts)
- DataTables (sortable car lists)
- FontAwesome icons

## Structure

```
/
├── index.html          # Dashboard / home
├── cars.html           # Full cars list
├── finder.html         # Car finder
├── calendar.html       # Event calendar
├── shop.html           # Shop tracker
├── blog.html           # Blog index
├── car/                # Individual car pages (1.html – 741.html)
├── blog/               # Blog post pages
├── assets/
│   ├── css/            # Stylesheets
│   ├── js/             # Scripts
│   └── img/            # Images & icons
├── bootstrap/          # Bootstrap 4 CSS/JS
└── plugins/            # Third-party plugins (ApexCharts, DataTables, etc.)
```

## Data Coverage

| Category        | Count         |
|----------------|---------------|
| Car pages       | 740+          |
| Tiers covered   | T1 – T5 + Legends |
| Tune types      | Stage 1–6, Elite   |

## Source

Originally mirrored from [dragracing.space](https://dragracing.space) — a community-built CSR2 resource site.

---

> CSR Racing 2 is developed by NaturalMotion / Zynga. This is a fan-made, community reference resource.
