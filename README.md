# Tenfire Icons

A selected subset of [custom-brand-icons](https://github.com/elax46/custom-brand-icons), retaining the `phu:` prefix.

## Installation

Add this repository as a custom **Dashboard** repository in HACS and install Tenfire Icons. Load `/hacsfiles/hacs-tenfire-icons/hacs-tenfire-icons.js` as a JavaScript module resource if HACS does not add it automatically. Reload the browser. Use the installed repository directory in the URL if it differs. Do not load another `phu` provider alongside this one.

For manual installation, copy `dist/hacs-tenfire-icons.js` into your frontend resource directory and add it as a JavaScript module resource.

Only the icons listed in `provenance.json` are included. Both the legacy iconset API and the current icon picker API are supported. Unknown icons return an empty string.

See `LICENSE`, `UPSTREAM.md`, and `provenance.json` for attribution and pinned source details.
