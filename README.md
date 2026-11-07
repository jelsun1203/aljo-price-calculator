# ALJO Price Wizard

Price calculator for ALJO Trucking Services (Foton 6-wheeler closed van).

## How the distance is found

1. Distances ALJO checked on Google Maps (the `SAVED_ROUTES` list in `index.html`).
2. A live road lookup from OpenStreetMap, free.
3. If the lookup is down, an approximate distance, clearly marked on the quote.

## Changing rates

Open `index.html` and edit the `CONFIG` block near the top of the script: fuel price, km per liter, base fee, price per km and driver fee. Add Google Maps distances to `SAVED_ROUTES` using the exact city names from the dropdowns.

The page asks search engines not to list it.
