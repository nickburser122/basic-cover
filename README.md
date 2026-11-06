# basic-cover

Printable Arabic cover and declaration forms in a single `index.html`. The page prints through the browser print dialog and accepts an image upload.

## Limits

- Right-to-left Arabic layout only.
- State is saved in `localStorage`; clearing site data removes it.

## Network and install

No network calls after load; loads Google Fonts from a CDN. Not installable; no service worker. The favicon is embedded in the page as data URIs, so no extra files are needed.
