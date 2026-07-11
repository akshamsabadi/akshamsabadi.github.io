---
layout: page
title: Bioassay LOD Fitter
description: A web application for analysing concentration-response data, performing advanced sigmoidal curve fitting, and rigorously calculating the Limit of Detection (LOD).
importance: 1
category: work
related_publications: false
---

Bioassay LOD Fitter (v0.5.18) is a web application built to analyse concentration-response data, perform advanced sigmoidal curve fitting, and rigorously calculate the Limit of Detection (LOD) for diagnostic assays using validated statistical frameworks.

- **Live Demo:** [akshamsabadi.github.io/bioassay-LOD-fitter](https://akshamsabadi.github.io/bioassay-LOD-fitter/)
- **Source Code:** [akshamsabadi/bioassay-LOD-fitter](https://github.com/akshamsabadi/bioassay-LOD-fitter)

### Features

- **Completely client-side processing:** Fast, secure local calculations (no server uploads needed).
- **Interactive Multi-Model Comparison:** Renders a live statistical table showing R² and AICc metrics side-by-side for Linear, Langmuir, 4PL, and 5PL models, with dynamic best-fit gold-star selectors.
- **Assay Quality Checks Widget:** Automated diagnostic checks that flag high replicate variance (CV), poor fits, or non-monotonic trends (like high-dose Hook Effects).
- **Continuous Hover Telemetry Tooltips:** Shows predicted values, 95% Confidence Interval bounds, and raw replicates at any coordinate, accompanied by dashed crosshair cursor guides.
- **Bidirectional Table-to-Chart Highlights:** Hovering over standard or blank input table rows instantly illuminates all corresponding replicate circles on the chart with animated pulsing halos.
- **High-Resolution Export:** Download publication-ready, 300 DPI PNG plots and CSV reports of analytical results.
