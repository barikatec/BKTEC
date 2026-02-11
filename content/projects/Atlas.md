# tldr
One of my first project with the help of AI. Started the work on this because I am a big fan of the maps made by the [IGN](https://www.ign.fr/) and I do go as often as possible in the mountains, also:
- I didn't find any free & open source tools
- vibe coding was emerging
- it has been cool to work on it and learn
#### How to try it ?
just clink on that link: https://igpx.netlify.app/

<div style="text-align: center; margin: 4rem 0 2rem 0; color: #888;">
  <p style="font-size: 0.85rem; text-transform: uppercase; letter-spacing: 1px; margin-bottom: 0.5rem;">
    Technical details
  </p>
  <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
    <line x1="12" y1="5" x2="12" y2="19"></line>
    <polyline points="19 12 12 19 5 12"></polyline>
  </svg>
</div>
### **The app that finally gets you away from your computer.**

Visualize your GPX tracks, analyze elevation profiles, overlay map layers (OSM / IGN), and export professional, to-scale "Atlas" PDFs.

🌍 **React + Vite** • 🗺️ **Leaflet / React-Leaflet** • 📈 **Recharts** • 🧾 **html2canvas + jsPDF** • 📱 **PWA**

---

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap: 20px; margin-bottom: 2rem;">
  
  <div style="text-align: center;">
    <img src="attachments/ATLAS-001.jpg" alt="Work on your gpx" style="width: 100%; height: auto; border-radius: 8px; border: 1px solid #ddd; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
    <p style="font-weight: bold; margin-top: 10px; margin-bottom: 0;">Work on your gpx</p>
  </div>

  <div style="text-align: center;">
    <img src="attachments/ATLAS-002.jpg" alt="export & print" style="width: 100%; height: auto; border-radius: 8px; border: 1px solid #ddd; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
    <p style="font-weight: bold; margin-top: 10px; margin-bottom: 0;">Export & print</p>
  </div>

  <div style="text-align: center;">
    <img src="attachments/ATLAS-003-.jpg" alt="go out !" style="width: 100%; height: auto; border-radius: 8px; border: 1px solid #ddd; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
    <p style="font-weight: bold; margin-top: 10px; margin-bottom: 0;">Go out !</p>
  </div>

</div>

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

<img src="attachments/ATLAS-004.jpg" 
     alt="Screenshot of the Atlas App" 
     style="display: block; margin: 2rem auto; width: 400px; max-width: 100%; height: auto; border-radius: 8px; border: 1px solid #ddd; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
     