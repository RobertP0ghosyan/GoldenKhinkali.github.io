# Golden Khinkali — website demo

A static, mobile-first pitch site built with plain HTML, CSS and JavaScript. No build step or dependencies.

## Run locally

Open `index.html` directly, or serve the folder for the closest match to production:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to GitHub Pages

1. Push the contents of this folder to a GitHub repository.
2. In **Settings → Pages**, set **Build and deployment** to **Deploy from a branch**.
3. Select your branch (usually `main`) and the **/ (root)** folder, then save.
4. Open the Pages URL GitHub provides. The site uses relative asset paths and needs no build action.

## Before a public launch

- Replace the `MENU_ITEMS`, `REVIEWS`, `GALLERY`, `SIGNATURE_IDS`, and menu combinations near the top of `js/main.js` with approved content. Sample prices and review copy are marked on the page.
- Confirm the address, phone, hours and current rating with the owner. These were gathered from third-party listings and may change.
- Replace the illustrative generated photos in `assets/images/` with licensed restaurant photography and update alt text.
- Connect `CONFIG.reservationEndpoint` and the TODO in `handleReservation()` to a backend before presenting the form as a live booking system.
- Set absolute production URLs for `og:image` and the JSON-LD `image` property after the final domain is known.
- Check the translated UI and menu wording with native speakers.

## Content and image notes

The food images were generated for this demo using the built-in image generation tool. Prompts described editorial restaurant photographs of khinkali, khachapuri, grilled skewers, and pkhali in warm, dark Caucasian tavern lighting. They do not depict the actual venue or menu.

Public listing references: [Tripadvisor](https://www.tripadvisor.com/Restaurant_Review-g293932-d32742322-Reviews-Golden_Khinkali-Yerevan.html), [Electronic Armenia](https://www.pages.am/en/pages/golden-khinkali-yerevan/), and the supplied [Yandex Maps](https://yandex.com/maps/org/golden_khinkali/2185213809/) and [Instagram](https://www.instagram.com/goldenkhinkali/) links.
