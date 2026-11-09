# The Garage

Private-source vehicle comparison prototype, with 24 models and provisional measurements.

## Privacy
Favorites you select in the browser remain in that browser's local storage only. Do not commit personal data to this repository.

## Usage
The standalone `index.html` contains the data and runs in a JavaScript-capable browser. `data/vehicles.json` is a reference copy of the same public vehicle specifications. A private GitHub repository alone does not publish a Safari-accessible website; hosting remains to be configured.

## Status
Prototype only. All vehicle dimensions are provisional and need verification. No authentication, cloud database, or cross-device synchronization.

## Home Screen application and appearance

- `manifest.webmanifest` uses relative identity, start URL and scope for this GitHub Pages project.
- `icons/` contains opaque 180, 192 and 512 pixel adaptations of the existing navy/gold favicon. The browser favicon is unchanged.
- On iPhone/iPad, open the published HTTPS site in Safari and use Share → Add to Home Screen; enable Open as Web App if offered.
- Appearance follows `prefers-color-scheme`; no manual switch or saved theme override is introduced.
- No service worker or offline content cache is registered. Content continues through the existing online publication workflow; there is no app cache to version or clear.
- Keep the manifest identity and project path stable when publishing updates. A future move needs a separate migration plan.
