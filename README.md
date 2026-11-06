# Hong Kong trip — GitHub Pages

This repository publishes the existing standalone travel app at https://davidkwon2.github.io/ from `main`. `index.html` is the standalone source; preserve its itinerary, embedded assets and device-local storage/backup behavior when editing. The original Sites runtime is separate.

## Map fix — 2026-11-07

Restored the OpenStreetMap background tile layer removed during offline export. Only `https://tile.openstreetmap.org` image requests are permitted in addition to existing data/blob images. External scripts, API connections and forms remain blocked. Leaflet stays embedded, no API key or paid service is added, and no device position is requested. Tiles load only for the displayed view with normal browser caching; no bulk download or offline tile prefetch. Keep OpenStreetMap attribution and the origin Referer. On network failure the visit markers/straight connections remain and the existing retry button reloads tiles. The straight lines indicate visit order, not road routes. Device-local records are unchanged.

## Reference art direction — 2026-11-07

Earlier packaging-app direction (superseded by the approved boutique-journal direction below): warm ivory canvas, clear dark headings and restrained muted-red accents, rounded clean cards and subtle press/hover feedback. Keep large readable text, five tabs, cat photographs, working map, itinerary data and device-local records. This supersedes the previous lavender diary palette on GitHub Pages. No new remote assets or fonts are required. Honor reduced-motion preferences.

## Compact, low-intensity header — 2026-11-07

The user found the tall red hero and strong color uncomfortable. This supersedes the large red-gradient hero: use a compact warm-neutral header, small cat photograph, dark readable title, and muted brick-red accents limited to small controls. Keep existing text sizes and functional targets; reclaim space by reducing decorative header height, not shrinking schedule text. Selected date/navigation use pale neutral-red fills without bright glow. Remove the large wallet gradient too. Preserve itinerary and device storage.

## Approved boutique travel-journal UI — 2026-11-07

The user approved applying the generated boutique-travel-journal concept to the app, with large text, a compact header and a single-column itinerary. This is the current art direction and supersedes the earlier packaging-style art treatment. Use cream paper surfaces, rose-beige selections, restrained champagne borders and dark cocoa text. Date buttons are small tickets, the original cat photos sit in miniature round frames, and navigation/buttons have subtle porcelain-style highlights. Avoid bright red areas, heavy shadows, decorative text behind content, fabricated traveler portraits and staggered itinerary cards. Preserve the standalone storage/backup scripts, all itinerary data and the working map. The inline stylesheet is `#boutique-journal-style`.
