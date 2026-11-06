# Hong Kong trip — GitHub Pages

This repository publishes the existing standalone travel app at https://davidkwon2.github.io/ from `main`. `index.html` is the standalone source; preserve its itinerary, embedded assets and device-local storage/backup behavior when editing. The original Sites runtime is separate.

## Map fix — 2026-11-07

Restored the OpenStreetMap background tile layer removed during offline export. Only `https://tile.openstreetmap.org` image requests are permitted in addition to existing data/blob images. External scripts, API connections and forms remain blocked. Leaflet stays embedded, no API key or paid service is added, and no device position is requested. Tiles load only for the displayed view with normal browser caching; no bulk download or offline tile prefetch. Keep OpenStreetMap attribution and the origin Referer. On network failure the visit markers/straight connections remain and the existing retry button reloads tiles. The straight lines indicate visit order, not road routes. Device-local records are unchanged.

## Reference art direction — 2026-11-07

User-approved visual direction from the supplied packaging-app reference: warm ivory canvas, clear dark headings and restrained muted-red accents, rounded clean cards and subtle press/hover feedback. Keep large readable text, five tabs, cat photographs, working map, itinerary data and device-local records. This supersedes the previous lavender diary palette on GitHub Pages. No new remote assets or fonts are required. Honor reduced-motion preferences.

## Compact, low-intensity header — 2026-11-07

The user found the tall red hero and strong color uncomfortable. This supersedes the large red-gradient hero: use a compact warm-neutral header, small cat photograph, dark readable title, and muted brick-red accents limited to small controls. Keep existing text sizes and functional targets; reclaim space by reducing decorative header height, not shrinking schedule text. Selected date/navigation use pale neutral-red fills without bright glow. Remove the large wallet gradient too. Preserve itinerary and device storage.
