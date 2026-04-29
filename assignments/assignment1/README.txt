AIA-GraphML Assignment 1: Building Topology Graph Analysis
============================================================

This assignment explores spatial relationships in buildings using graph-based representations.

Final Graph Visualization
--------------------------
The final graph visualization displays the building topology with nodes (vertices) representing cells in the building. Each node's appearance encodes information about the apertures (windows/doors) in that cell:

NODE COLOR (Aperture Count):
  - Black: 0 apertures
  - Red: 1 aperture
  - Blue: 2 apertures
  - Green: 3 or more apertures

NODE SIZE (Volume-to-Aperture Ratio):
  The vertex size is determined by a ratio calculated as (total_aperture_area / cell_volume) * 200. 
  This metric represents the proportion of apertures relative to cell volume, providing insight into 
  how "open" or "transparent" a cell is. Larger nodes indicate cells with more aperture area relative 
  to their volume, while smaller nodes represent more enclosed spaces.

This visualization combines topological connectivity with quantitative metrics to identify patterns 
in how natural light and openings are distributed throughout the building.
