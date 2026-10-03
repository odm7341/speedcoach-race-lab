# SpeedCoach Race Lab

A mobile-friendly, browser-only analyzer for SpeedCoach CSV exports.

## Features

- Upload or drag in a SpeedCoach CSV
- Inspect the GPS route on a Leaflet map with OpenStreetMap tiles
- Color the route by speed, split, meters per stroke, stroke rate, steering change, or anomaly score
- Select any stroke from the map, timeline, scrubber, anomaly list, or nearby-strokes table
- Review automatic incident candidates based on abrupt performance and heading changes
- Keep all workout data in the browser; no CSV data is uploaded to a server

## Local preview

Serve the `dist` folder with any static web server, then open `index.html`.

## Privacy

The repository does not contain a workout CSV. Files selected in the analyzer are processed locally in the browser.

