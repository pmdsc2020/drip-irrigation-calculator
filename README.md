# Drip irrigation design calculator

Browser tool for field layout, emitter count, system discharge, and operating time.

Live page: https://pmdsc2020.github.io/drip-irrigation-calculator/

## What it calculates

- Lateral lines and plants per lateral from plot length, width, and spacing
- Plant population and total emitters
- Gross dose per plant from ETc, wetted-area fraction, efficiency, and irrigation interval
- Application rate (mm/h), irrigation volume, and average daily volume
- Whole-field discharge and pump flow if the field is split into shifts
- Operating time per shift

Plant count uses the grid (`floor(width / row spacing) × floor(length / plant spacing)`), so emitter totals match the layout. One millimetre on one square metre is one litre.

This is a planning estimate. It does not size pipes, check emitter uniformity, or apply a peak-month crop coefficient.

## Run locally

Open `index.html` in a browser. No build step.
