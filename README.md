# Sukun Apparel — Event Sales Dashboard

A single-page web application built to track event performance, inventory, and revenue for **Sukun Apparel**, a modest fashion brand based in Chicago, IL.

Built as a real business tool to replace manual tracking across pop-up events and conventions — including recurring sell-out appearances at MAS ICNA (2,000+ attendees).

---

## Features

- **Sales Dashboard** — KPI summary cards showing total revenue, units sold, sell-out rate, and average revenue per event; interactive bar and doughnut charts powered by Chart.js
- **Event Log** — full CRUD table of all pop-up appearances with date, location, attendees, units sold, revenue, and notes
- **Inventory Tracker** — product cards with live stock-level progress bars and low-stock alerts
- **Log New Event** — validated form to record new pop-up appearances; data persists across sessions

---

## Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5, Semantic markup |
| Styling | CSS3, CSS Variables, Responsive Grid |
| Logic | Vanilla JavaScript (ES6+) |
| Charts | Chart.js 4.4 |
| Data | localStorage (relational-style key-value store) |

No frameworks, no build tools, no dependencies beyond Chart.js — opens directly in any browser.

---

## Getting Started

```bash
git clone https://github.com/Sadeen-Hmeidan/sukun-sales-dashboard.git
cd sukun-sales-dashboard
open index.html
```

Or just download `index.html` and open it in your browser — no server required.

---

## Project Structure

```
sukun-sales-dashboard/
│
├── index.html        # Full SPA — markup, styles, and logic in one file
└── README.md
```

---

## Screenshots

### Dashboard — KPI Cards & Charts
The dashboard view displays total revenue, units sold, sell-out count, and average revenue per event alongside a revenue bar chart and units-sold doughnut chart.

### Inventory Tracker
Product cards show real-time stock levels with color-coded progress bars that flag low-stock items automatically.

### Event Logger
A validated form captures all event details — name, date, city, venue, estimated attendees, units sold, revenue, and notes — and persists them to the local data store.

---

## Business Context

Sukun Apparel is a sister-owned modest fashion brand that sells at Muslim community events and pop-up markets across the Midwest. This dashboard replaced spreadsheet-based tracking and supports data-driven decisions about inventory, pricing, and event selection.

**Real data highlights:**
- MAS ICNA Convention — 2,000+ attendees, 500+ units sold, consecutive sell-outs
- Average revenue per event: $2,600+
- Total tracked revenue across logged events: $13,240

---

## Author

**Sadeen Hmeidan**  
BS Computer Science — DePaul University (Jarvis College of Computing and Digital Media)  
[LinkedIn](https://www.linkedin.com/in/sadeen-hmeidan) · [GitHub](https://github.com/Sadeen-Hmeidan)
