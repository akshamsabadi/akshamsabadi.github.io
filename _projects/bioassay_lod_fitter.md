---
layout: page
title: Bioassay LOD Fitter
description: A web application for analysing concentration-response data, performing advanced sigmoidal curve fitting, and rigorously calculating the Limit of Detection (LOD).
importance: 1
category: work
related_publications: false
---

Bioassay LOD Fitter (v0.6.23) is a web application built to analyse concentration-response data, perform advanced sigmoidal curve fitting, and calculate the Limit of Detection (LOD) for biological and chemical assays using validated statistical frameworks (Currie 1968, Holstein et al. 2015).

- **Live Demo:** [akshamsabadi.github.io/bioassay-LOD-fitter](https://akshamsabadi.github.io/bioassay-LOD-fitter/)
- **Source Code:** [akshamsabadi/bioassay-LOD-fitter](https://github.com/akshamsabadi/bioassay-LOD-fitter)

### Key Features

- **Multi-Curve Plot Overlay:** Overlay multiple curves (e.g. Wild-Type vs Mutants, Buffer A vs B) on a shared broken logarithmic axis with color-coordinated trendlines, interactive hover-focus, and a Multi-Curve Sensitivity Leaderboard displaying fold-change shifts.
- **Direct Spreadsheet Clipboard Paste:** Copy rows and columns directly from **Microsoft Excel** or **Google Sheets** (`Ctrl+V` / `Cmd+V`) into the sidebar for instant table parsing.
- **Unified Single-View Analytics:** View the prominent LOD Hero Card, fitted parameter micro-grid, interactive AICc comparison table, and collapsible statistical noise limits ($L_C, L_D$, blank SD, pooled SD) in a cohesive single view without tab-hopping.
- **Completely client-side processing:** Fast, secure local calculations without uploading sensitive biological or chemical data to external servers.
- **Interactive Multi-Model Comparison:** Renders a live statistical table showing R² and AICc metrics side-by-side for Linear, Langmuir, 4PL, and 5PL models, with dynamic best-fit gold-star selectors and one-click `Auto (AICc)` optimization.
- **Assay Quality Checks Widget:** Automated diagnostic checks that flag high replicate variance (CV), poor fits, or non-monotonic trends (like high-dose Hook Effects).
- **Continuous Hover Telemetry Tooltips:** Shows predicted values, 95% Confidence Interval bounds, and raw replicates at any coordinate, accompanied by dashed crosshair cursor guides.
- **Bidirectional Table-to-Chart Highlights:** Hovering over standard or blank input table rows instantly illuminates all corresponding replicate circles on the chart with animated pulsing halos.
- **Publication-Ready Export:** Download high-resolution 300 DPI PNG plots and comprehensive CSV / Markdown statistical reports.
