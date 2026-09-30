MN Ice Fishing Depth & Target Navigator 🎣📱

A lightweight, single-file Progressive Web Application (PWA) designed for Minnesota ice anglers. Locate target water depth contours, navigate directly to structures on the ice using real-time relative compass guidance, and query official Minnesota DNR bathymetry GIS data directly from your smartphone.

✨ Features

📱 Built-in PWA & Dynamic App Icon: Fully self-contained single-file HTML app. Automatically generates high-resolution 512x512 app icons and a web manifest directly in memory—no external PNG files required when adding to your iPhone Home Screen.

🗺️ MN DNR Bathymetry GIS Querying: Real-time integration with official Minnesota DNR Enterprise REST GIS servers to fetch lake names and contour depths at your exact location.

🧭 Real-Time Relative Steering HUD: Hold your phone flat in your hand on the ice to get live directional guidance ("STRAIGHT AHEAD", "TURN RIGHT 20°", etc.) and distance tracking toward target depth contours or logged holes.

📍 Ice Hole Logger: Save hole coordinates, water depth, and timestamps with one tap. Export your logged holes to a CSV file anytime.

🌊 Drawdown Depth Adjustment: Set custom water level drawdown offsets (e.g., winter reservoir level drops) for accurate depth calculations.

🧪 Off-Ice Simulator Mode: Test navigational features with built-in lake presets (Mille Lacs Lake, Lake Minnetonka, Lake of the Woods).

🚀 Quick Start with GitHub Pages

Upload File: Add the index.html file to the root of your GitHub repository.

Enable GitHub Pages:

Go to your repository Settings.

Scroll down to Pages in the left sidebar.

Under Build and deployment > Source, select Deploy from a branch.

Choose the main (or master) branch and click Save.

Access Your App: GitHub will provide a live URL (e.g.,(https://github.com/furgus-crash/gps-lake-depth/).

📲 Adding to iPhone Home Screen (iOS Safari)

Open your live GitHub Pages URL in Safari on your iPhone.

Tap the Share button (the square with an arrow pointing up at the bottom of the screen).

Scroll down and tap Add to Home Screen.

Confirm the name and tap Add.

The app icon (a dark ice badge with a compass needle and depth indicator) will appear on your home screen and run full-screen without Safari browser bars.

🛠️ Built With

HTML5 / CSS3 / ES6 JavaScript (Single-file zero-dependency framework)

Leaflet.js for map rendering and spatial visuals

HTML5 Canvas API for dynamic app icon generation

Minnesota DNR Bathymetry MapServer API for spatial depth queries

⚠️ Disclaimer

Always check local ice thickness guidelines provided by the Minnesota Department of Natural Resources (MN DNR) before heading out onto frozen water. Never rely solely on electronic navigation for ice safety.
