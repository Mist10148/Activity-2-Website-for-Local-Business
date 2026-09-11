# [BUSINESS NAME] — Website

**Activity 2: Website for a Local Business**
Web Development and Web Design

## About this site

A five-page static website for a coffee shop in Iloilo City. It is built with plain HTML and CSS only. There is no JavaScript, no framework and no backend, so every page can be opened straight from the folder with a double click.

## How to open it

Open `index.html` in any browser. The other four pages are reachable from the navigation bar at the top of every page.

## Files

| File | What it holds |
| --- | --- |
| `index.html` | Home. Hero photo, welcome text, highlights and the sidebar. |
| `about.html` | About Us. The shop's story, mission, vision and values. |
| `services.html` | Menu. Six items with photos and prices, plus a price table. |
| `gallery.html` | Gallery. Eight photos with captions. |
| `contact.html` | Contact Us. Shop details and the inquiry form. |
| `css/style.css` | The only stylesheet. Every page links to it. |
| `images/` | All photos and the logo. |
| `README.md` | This file. |
| `BUSINESS-RESEARCH.md` | Proof the business has no official website. |
| `EXPLANATION.md` | Answers to the six short questions. |

## What still needs to be filled in

Everything written in square brackets is a placeholder. Search the HTML files for `[` and replace these with the real details:

| Placeholder | Replace with |
| --- | --- |
| `[BUSINESS NAME]` | the shop's name |
| `[STREET ADDRESS]` | the street address |
| `[BARANGAY]` | the barangay |
| `[CONTACT NUMBER]` | the phone number |
| `[EMAIL ADDRESS]` | the email address |
| `[FACEBOOK PAGE NAME]` | the Facebook page name |

The footer social links are set to `#` for now. Replace them with the real Facebook, Instagram and Google Maps links.

## Images to add

Drop these files into the `images` folder. The names must match exactly or the pictures will not show.

| File | Suggested size |
| --- | --- |
| `logo.png` | square, around 128 × 128 |
| `favicon.png` | square, 32 × 32 |
| `hero-shop.jpg` | wide, around 1600 × 900 |
| `home-interior.jpg` | around 800 × 600 |
| `about-shop.jpg` | around 800 × 600 |
| `menu-espresso.jpg` | square, around 600 × 600 |
| `menu-latte.jpg` | square |
| `menu-coldbrew.jpg` | square |
| `menu-frappe.jpg` | square |
| `menu-pastry.jpg` | square |
| `menu-meal.jpg` | square |
| `gallery-01.jpg` … `gallery-08.jpg` | square, around 800 × 800 |

The gallery and menu photos are cropped by CSS, so they do not have to be the exact same size. Square photos simply crop the most neatly.

## Notes on the code

- Semantic tags are used throughout: `header`, `nav`, `main`, `section`, `article`, `aside`, `figure` and `footer`.
- The navigation block is identical on all five pages. Only the `active` class moves to the link of the page you are on.
- The contact form has no `action` attribute on purpose. The activity does not need a backend, so nothing is sent anywhere.
- `style.css` is one file, split into commented sections in this order: reset, colors, base text, nav, hero, cards, buttons, home layout, sidebar, footer, inner pages, menu, gallery, form, media queries.
- There are two breakpoints, at 900px and 700px.
