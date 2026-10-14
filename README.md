# Interactive Sales Analytics Dashboard

A browser-based dashboard that tracks revenue, orders, average order value and product performance.

**Live demo:** https://nivii17.github.io/sales-dashboard/

## Features
- KPI summary: total revenue, total orders, average order value
- Line chart: revenue by month
- Bar chart: revenue by product
- Dynamic filtering: pick a product and every number and chart updates instantly

## Tech
HTML, CSS, JavaScript, Chart.js

## Run it
Download the repo and double-click `index.html`. An internet connection is needed because Chart.js loads from a CDN.

## How it works
Sales data is stored as a small array in `index.html`. The filter keeps only the rows for the selected product, then the totals and both charts are recalculated and redrawn.