---
layout: page
title: F1 Data Viz Portal
description: An interactive D3.js and HTML dashboard mapping Formula 1 timing data, lap charts, and model-estimated corner speeds.
importance: 1
category: fun
related_publications: false
---

F1 Data Viz Portal (v1.16.26) is a highly interactive, responsive web dashboard built with D3.js and vanilla ESM JavaScript mapping real-time session telemetry, driver performance, and race classification results.

- **Live Demo:** [akshamsabadi.github.io/f1-data-viz-portal](https://akshamsabadi.github.io/f1-data-viz-portal/)
- **Source Code:** [akshamsabadi/f1-data-viz-portal](https://github.com/akshamsabadi/f1-data-viz-portal)

### Key Features

- **Interactive Track Position (Bump Chart):** Maps driver positions lap-by-lap with customized transparent 12px hover-target hitboxes for effortless line selection and focus states.
- **Model-Estimated Corner Speeds:** Sub-plots analyzing telemetry estimates for low, medium, and high-speed corner profiles.
- **Lap Times (Beeswarm):** Force-directed D3 simulation mapping every single lap time by driver with outlier toggle controls.
- **Live Classification Standings Widget:** HTML standings panel that automatically parses session timing results, winner gap margins, and DNF/DNS retirement status.
- **Cross-Dashboard Hover Highlights:** Hovering over a driver in the Standings table instantly highlights and isolates their vectors across all three D3 telemetry charts!
- **Glassmorphic Paddock Header & Hybrid Selectors:** Responsive custom-select controls synced with hidden native nodes, styled with high-contrast official team colors.
