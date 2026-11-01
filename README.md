# Golden Khinkali — website demo

Static, mobile-first restaurant website built with HTML, CSS, and vanilla JavaScript. No build step.

## Run locally

Open `index.html`, or run `python -m http.server 8000` from this repository and visit `http://localhost:8000`.

## GitHub Pages

In **Settings → Pages**, deploy branch `main` from `/ (root)`. Every website file is kept at the repository root, so `index.html` loads `styles.css`, `main.js`, and the `.webp` images by relative path.

## Before public launch

- Replace the clearly marked sample dishes, prices, and reviews in the data objects at the top of `main.js`.
- Confirm the address, phone, hours, and rating with the owner.
- Replace the generated illustrative food images with licensed restaurant photos and update their alt text.
- Connect `CONFIG.reservationEndpoint` and the TODO in `handleReservation()` to a backend. The form currently validates locally and does not send bookings.
- Set absolute production URLs for Open Graph and JSON-LD images if the domain changes.
- Review RU/HY/ES translations with native speakers.

The four food images were generated for this demo using prompts for warm editorial photography of khinkali, khachapuri, grilled skewers, and pkhali. They do not depict the actual venue or menu.
