# Crystal static ES/EN demo

Generated from the supplied HAR captures.

- Captured Spanish and English HTML routes are static files.
- Links whose target was captured are rewritten to the local static page.
- Crystal `/static/` resources remain remote on `https://crystal.com.co`, as requested.
- `CAPTURED-PAGES.txt` contains the route audit and any uncaptured Crystal routes that still point to production.
- Serve the directory through HTTP (for example VS Code Live Server) rather than relying on `file://`.
