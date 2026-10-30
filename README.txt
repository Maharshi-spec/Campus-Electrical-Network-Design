CampusGrid responsive dashboard prototype
==========================================

HOW TO RUN
1. Extract the ZIP file.
2. Open index.html in a modern browser (Chrome, Edge, Firefox, Safari).
3. For best results, use VS Code + the Live Server extension and open this folder.

WHAT'S INCLUDED
- Responsive desktop and mobile layout
- Campus banner and aerial campus image supplied by you
- Separate Overview, Campus Map, Algorithm Steps, Cost Analysis, Buildings, and Scenarios pages
- Kruskal step-through, previous/next, reset, auto-play, and progress slider
- Add-building list interaction and route-cost demo input

IMPORTANT PROJECT NOTES
- The cost figures are illustrative demo data, not measured campus costs.
- The map is a visual mockup over the supplied aerial photo; the node positions and routes are illustrative, not a surveyed campus GIS map.
- The algorithm page is a teaching animation prototype. For a mathematically correct final submission, connect it to one shared edge dataset and implement Kruskal with Union-Find (Disjoint Set Union), then derive the MST cost and accepted/rejected edges from that dataset.
- Changes in Scenarios are browser-session-only and do not yet recalculate the graph or persist to a database.
