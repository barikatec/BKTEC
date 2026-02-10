# Intro
One of my first project with the help of AI. Started the work on this because I am a big fan of the maps made by the [IGN](https://www.ign.fr/) and I do go as often as possible in the mountains, also:
- I didn't find any free & open source tools
- vibe coding was emerging
- it has been cool to work on it and learn

### **The app that finally gets you away from your computer.**

Visualize your GPX tracks, analyze elevation profiles, overlay map layers (OSM / IGN), and export professional, to-scale "Atlas" PDFs.

🌍 **React + Vite** • 🗺️ **Leaflet / React-Leaflet** • 📈 **Recharts** • 🧾 **html2canvas + jsPDF** • 📱 **PWA**

---
<img src="attachments/ATLAS-001.jpg" style="width: 220px; object-fit: cover; border: 2px solid #eee; margin-bottom: 1rem;"> <img src="attachments/ATLAS-002.jpg" style="width: 220px; object-fit: cover; border: 2px solid #eee; margin-bottom: 1rem;"> <img src="attachments/ATLAS-003-.jpg" style="width: 220px; object-fit: cover; border: 2px solid #eee; margin-bottom: 1rem;"> 
## Features (The Practical Side)

### GPX / Track Management

- **Multi-file GPX Import:** Drag & drop or use the "+" button.
- **Multi-track Management:** Toggle visibility, change colors, opacity, and line thickness.
- **Automatic Calculations:** Distance, elevation gain/loss ($D+/D-$), and min/max altitude.
- **Reverse Track Direction:** Flip your route with one click (🔁).
- **Directional Arrows:** Visual flow indicators along the path.
- **Kilometer Markers:** Optional "km" checkbox to display markers directly on the map.
- **Persistence:** Your tracks are automatically saved in the browser (**localStorage**).
### Maps & Layers

- **Base Maps:** OpenStreetMap + CyclOSM.
- **IGN Integration:** PlanIGN v2 + additional IGN layers (subject to availability).
- **Useful Overlays:** Slope gradients > 30°, kilometer grids, boundaries, cadastre, and drone restrictions.
- **Layer Lock:** "Keep this layer for all zoom levels" option.

### Elevation Profile

- **Interactive Profile:** Powered by Recharts.
- **Sync Hover:** Hovering over the profile highlights the corresponding point on the map.
- **Live Metrics:** Progress tracking for distance and elevation (done vs. remaining).

### Atlas Mode (PDF Export)

- **To-Scale Multi-page PDF:** Generated via an **offscreen** Leaflet map for stable, high-quality exports.
- **Clean Crop:** Perfectly aligned rendering of tiles, overlays, and tracks.
- **PDF Overlays:** Frame, logo, North arrow, custom notes, page numbers, and scale bar.
- **The Goal:** An "unbreakable" export ready for printing or sharing.

### How to try it 
Simple ! just clink on that link: https://igpx.netlify.app/

![[ATLAS-004.jpg]]