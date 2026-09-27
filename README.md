# Maenam Villa V5

Static GitHub Pages / shared-hosting friendly website rebuilt from the supplied `public_html.zip` and `maenam.sql` snapshot.

## V5 highlights
- 5 room detail pages
- Real room photos copied from `admin/upload/img`
- Room prices imported from `maenam.sql`
- Thai / English toggle
- Gallery uses local assets, no iframe dependency
- Google Maps embed from the legacy site
- Booking form creates a mailto request
- Editable JSON data: `data/rooms.json`, `data/site.json`, `data/gallery.json`
- One GitHub Pages workflow is intentionally not included yet; add your preferred deploy workflow.

## Edit room price / text / photos
Edit `data/rooms.json`. Each room has `price`, `desc_th`, `desc_en`, `fac_th`, `fac_en`, and `images`.

## Local test
Run a static server, e.g. `python3 -m http.server 8080`, then open `http://localhost:8080`.

## Important
The supplied SQL contains the historical room records and prices used by this build. Verify current prices and contact details before publishing. No database credentials from the legacy PHP application are included in V5.
