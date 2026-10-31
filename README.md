# DLS Calculator

Works out the revised target when rain cuts a limited-overs cricket match short, using the Duckworth-Lewis-Stern (DLS) method.

**Live site:** https://yuvrajkhetan.github.io/dls-calculator/

## What it does

- Revised targets for 50-over, 20-over and custom-length matches
- Rain breaks in either innings, including more than one break
- Par scores at each break, and the result if play is called off
- A plain-English explanation of how each target was worked out

## Method

Uses the published DLS Standard Edition resource table, interpolated between rows. International matches use the official Professional Edition software, which can differ by a few runs, so the umpires' figure always stands.

## Privacy

Visits are counted with [GoatCounter](https://www.goatcounter.com/), which uses no cookies and collects no personal data.

## Running it

It is a single self-contained `index.html` with no build step. Open it in a browser, or serve the folder with any static file server.
