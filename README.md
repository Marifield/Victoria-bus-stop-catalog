# 🚌 Victoria Bus Stop Conditions — Community Map

An interactive web map for Victoria, BC residents to report and document bus stop conditions. Built as part of a political action project for ES407 at UVic, advocating for safer, more accessible, and more equitable public transit infrastructure.

---

## 🌐 Live Map

👉 [View the map here](https://github.com/Marifield/Victoria-bus-stop-catalog)

---

## 📋 What This Map Does

- **Report a bus stop** — drop a pin anywhere in Victoria and describe your experience
- **Rate conditions** across four categories: Safety, Shelter, Accessibility, and Comfort
- **Tag issues** — no shelter, poor lighting, no seating, muddy ground, accessibility barriers, and more
- **View all reports** — browse community submissions with colour-coded pins:
  - 🔴 Poor conditions (1–2 stars)
  - 🟡 Moderate (3 stars)
  - 🟢 Good conditions (4–5 stars)

---

## 🗺️ How to Use the Map

### Submitting a report
1. Click the **"＋ Report a Stop"** button in the top right
2. Click anywhere on the map where your bus stop is located — a pin will drop
3. Fill in the form on the left:
   - **Stop name** — e.g. "Douglas & Fort, Stop #4012"
   - **Your experience** — describe lighting, shelter, seating, safety, etc.
   - **Issues present** — click any tags that apply
   - **Star ratings** — rate Safety, Shelter, Accessibility, and Comfort out of 5
4. Click **"Submit Report"**

### Viewing reports
- Click any **coloured pin** on the map to see a summary popup
- Click **"View Details"** in the popup for the full report with rating bars
- Switch to the **"All Reports"** tab in the sidebar to browse all submissions

### Navigation
- **Scroll** to zoom in/out
- **Click and drag** to pan around the map
- Click **☰ Panel** to hide/show the sidebar for a fuller map view

---

## 🏫 Project Context

This map was created as part of a **Political Action Project** for ES407 at the University of Victoria. The project team audited bus stop conditions across Victoria and submitted a formal proposal to the City of Victoria recommending improvements to lighting, shelter, seating, and accessibility infrastructure.

**Team:** Olivia T, Quinn G, Morgan W, Kerwin W, Keira M
**Course:** ES407 — University of Victoria
**Date:** March 2026

---

## 🛠️ Technical Notes

- Built with [Leaflet.js](https://leafletjs.com/) and [MapTiler](https://www.maptiler.com/)
- Single `.html` file — no server, no database, no dependencies to install
- Report data is stored in shared browser storage and persists across sessions
- Fully open source — feel free to adapt for other cities or transit advocacy projects
