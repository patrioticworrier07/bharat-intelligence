# Bharat Intelligence — Interactive Globe Update

This is a static GitHub Pages website update. It adds a rotatable 3D Earth globe using the open-source globe.gl library and a public Earth texture. Markers represent broad news-monitoring regions and categories; they are NOT verified live incident locations, battlefield positions, or official intelligence.

## Globe features
- Rotate the globe by dragging; tap/click a marker to view its monitoring topic.
- Each marker offers a GDELT public-news search and a general news search.
- Existing India and global headline panels continue to request GDELT headlines in the browser and refresh periodically.
- Globe library and Earth textures load from public CDNs, so internet access is required.

## Publish on GitHub Pages
Replace the repository's root `index.html` with the included `index.html`, then commit the change to the `main` branch. Keep the file at the repository root, not inside a nested folder.

## Limitations
This does not geolocate individual news reports into confirmed incident coordinates. Markers are broad monitoring areas, and headlines are not proof that an event occurred. Check original reporting and official advisories. The site is an independent public-source research project, not an official intelligence service.
