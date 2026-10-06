# JadedNailz

Booking website for JadedNailz: acrylic sets, gel and custom nail art in a private home studio in the Commerce City / Denver area.

Instagram: [@jaded.nailzzz](https://instagram.com/jaded.nailzzz)

## What's in here

- `index.html` – the whole site (Home, Menu, Book, Policies)
- `icon.png` – the little logo in the browser tab
- `schedule-template.csv` – starter schedule to import into Google Sheets

## Updating open times

Open times come from a Google Sheet with three columns: **Date**, **Time**, **Status**.

- Add a row for each opening, like `11/3/2026, 10:00 AM, open`
- Change Status to `booked` once the deposit comes in, and that time disappears from the site
- Changes show up on the site within about 5 minutes

The sheet's "Publish to web" CSV link goes in `index.html` on the line that starts with `const SHEET_CSV_URL=`.
