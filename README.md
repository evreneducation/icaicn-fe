# iccict Website – CODEMAP

_Generated automatically from the uploaded zip (well-known.zip)._

## Overview

- **Type:** Static site (HTML/CSS/JS) using the **Eventify** theme by _alithemes_ with Bootstrap and jQuery.

- **Dynamic features:** Forms (registration, sponsors, keynote-speakers, contact) and **Admin/Super Admin** dashboards interact with a remote API.

- **Backend API base:** Endpoints point to `https://icaicn-be.onrender.com/`.

## Quick File Tree (depth 2)

```
├── .gitignore
├── .htaccess
├── .well-known/
│   └── acme-challenge/
├── about.html
├── admin/
│   ├── adminDashboard.html
│   ├── index.html
│   └── superAdminDashboard.html
├── agenda.html
├── assets/
│   ├── brouchur/
│   │   └── conference-brouchur.pdf
│   ├── css/
│   │   ├── main.css
│   │   ├── main.css.map
│   │   └── vendor/
│   ├── fonts/
│   │   ├── fa-brands-400.woff2
│   │   ├── fa-regular-400.woff2
│   │   ├── fa-solid-500.woff2
│   │   ├── fa-solid-600.woff2
│   │   ├── fa-solid-700.woff2
│   │   ├── fa-solid-900.woff2
│   │   ├── fa-v4compatibility.ttf
│   │   └── fa-v4compatibility.woff2
│   ├── img/
│   │   ├── all-images/
│   │   ├── bg/
│   │   ├── brand/
│   │   ├── elements/
│   │   ├── icons/
│   │   ├── proff/
│   │   ├── sponsors_logo/
│   │   └── squ/
│   ├── js/
│   │   ├── main.js
│   │   └── vendor/
│   └── scss/
│       ├── components/
│       ├── layout/
│       ├── main.scss
│       ├── theme/
│       └── utils/
├── cgi-bin/
├── code-of-conduct.html
├── contact.html
├── event-policy.html
├── exhibition.html
├── faq.html
├── features.html
├── index.html
├── keynote-speaker-register.html
├── paper-review.html
├── paper.html
├── register.html
├── speakers.html
├── sponsor-register.html
├── sponsor.zip
└── sponsors.html
```

## Tech Stack & Libraries

**CSS**: Bootstrap, AOS, Font Awesome, Magnific Popup, Nice Select, Odometer, Owl Carousel, Slick Slider + custom `assets/css/main.css`.

**JS**: jQuery, Bootstrap, GSAP + ScrollTrigger + SplitText, Waypoints, Odometer, Owl Carousel, Slick Slider, Magnific Popup, Nice Select, Circle Progress.

**Admin**: DataTables (+ Buttons/HTML5 export), JSZip, Chart.js.

Vendor CSS files:

- `assets/css/vendor/aos.css`
- `assets/css/vendor/bootstrap.min.css`
- `assets/css/vendor/buttons.bootstrap5.min.css`
- `assets/css/vendor/dataTables.bootstrap5.min.css`
- `assets/css/vendor/fontawesome.css`
- `assets/css/vendor/magnific-popup.css`
- `assets/css/vendor/mobile.css`
- `assets/css/vendor/nice-select.css`
- `assets/css/vendor/odometer.css`
- `assets/css/vendor/owlcarousel.min.css`
- `assets/css/vendor/sidebar.css`
- `assets/css/vendor/slick-slider.css`

Vendor JS files:

- `assets/js/vendor/ScrollTrigger.min.js`
- `assets/js/vendor/Splitetext.js`
- `assets/js/vendor/aos.js`
- `assets/js/vendor/bootstrap.min.js`
- `assets/js/vendor/buttons.bootstrap5.min.js`
- `assets/js/vendor/buttons.html5.min.js`
- `assets/js/vendor/chart.js`
- `assets/js/vendor/circle-progress.js`
- `assets/js/vendor/counter.js`
- `assets/js/vendor/dataTables.bootstrap5.min.js`
- `assets/js/vendor/dataTables.buttons.min.js`
- `assets/js/vendor/fontawesome.js`
- `assets/js/vendor/gsap.min.js`
- `assets/js/vendor/jquery-3.7.1.min.js`
- `assets/js/vendor/jquery.appear.js`
- `assets/js/vendor/jquery.dataTables.min.js`
- `assets/js/vendor/jquery.odometer.min.js`
- `assets/js/vendor/jszip.min.js`
- `assets/js/vendor/magnific-popup.js`
- `assets/js/vendor/mobilemenu.js`
- `assets/js/vendor/nice-select.js`
- `assets/js/vendor/owlcarousel.min.js`
- `assets/js/vendor/sidebar.js`
- `assets/js/vendor/slick-slider.js`
- `assets/js/vendor/waypoints.js`

## Pages Inventory

| File                             | <title>                       | API endpoints (inline)                                                                                       |                                                        CSS |  JS | Inline JS |
| -------------------------------- | ----------------------------- | ------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------: | --: | --------: | --- |
| `about.html`                     | About                         | ICCICT 2026                                                                                                  |                                                          - |  11 |        18 | 1   |
| `admin/adminDashboard.html`      | Admin Dashboard               | ICCICT 2026                                                                                                  | http://localhost:5000/api, https://icaicn-be.onrender.com/ |   3 |         4 | 1   |
| `admin/index.html`               | Admin Login                   | ICCICT 2026                                                                                                  |                            https://icaicn-be.onrender.com/ |   2 |         2 | 1   |
| `admin/superAdminDashboard.html` | Super Admin Dashboard         | ICCICT 2026                                                                                                  |                            https://icaicn-be.onrender.com/ |   4 |         9 | 1   |
| `agenda.html`                    | Conference Agenda             | ICCICT 2026                                                                                                  |                                                          - |  11 |        18 | 1   |
| `code-of-conduct.html`           | Code of Conduct - ICCICT 2026 | -                                                                                                            |                                                         11 |  18 |         1 |
| `contact.html`                   | Contact Us                    | ICCICT 2026                                                                                                  |                    https://icaicn-be.onrender.com//contact |  11 |        18 | 1   |
| `event-policy.html`              | Event Policies - ICCICT 2026  | -                                                                                                            |                                                         11 |  18 |         1 |
| `exhibition.html`                | Sponsors                      | ICCICT 2026                                                                                                  |                                                          - |  11 |        18 | 1   |
| `faq.html`                       | FAQ                           | ICCICT 2026                                                                                                  |                                                          - |  11 |        18 | 0   |
| `features.html`                  | Features                      | ICCICT 2026                                                                                                  |                                                          - |  11 |        18 | 1   |
| `index.html`                     | ICCICT 2026                   | https://icaicn-be.onrender.com//contact                                                                      |                                                         11 |  18 |         1 |
| `keynote-speaker-register.html`  | ICCICT 2026                   | http://localhost:5000/api/keynote-speaker/register, https://icaicn-be.onrender.com//keynote-speaker/register |                                                         11 |  18 |         1 |
| `paper-review.html`              | Paper Review                  | ICCICT 2026                                                                                                  |  https://icaicn-be.onrender.com//speaker/speakers/${id}`); |  11 |        18 | 1   |
| `paper.html`                     | Paper Submission              | ICCICT 2026                                                                                                  |           https://icaicn-be.onrender.com//speaker/register |  11 |        18 | 1   |
| `register.html`                  | Register                      | ICCICT 2026                                                                                                  |        https://icaicn-be.onrender.com//conference/register |  11 |        18 | 1   |
| `speakers.html`                  | Our Speakers                  | ICCICT 2026                                                                                                  |                                                          - |  11 |        18 | 1   |
| `sponsor-register.html`          | Sponsor Register              | ICCICT 2026                                                                                                  |           https://icaicn-be.onrender.com//sponsor/register |  11 |        18 | 1   |
| `sponsors.html`                  | Sponsors                      | ICCICT 2026                                                                                                  |                                                          - |  11 |        18 | 0   |

## Where to Change What (Most Common Edits)

**Branding (Logo, Favicon):**

- Favicon: `<link rel="icon" href="assets/img/sponsors_logo/favicon.png">` in every HTML head.
- Logos: images in `assets/img/brand/` and `assets/img/sponsors_logo/`. Update the files, or change `<img src="...">` paths in each page.

**Navigation/Header & Footer:**

- Header/nav markup is duplicated per page (no templating). Edit in each HTML (e.g., `index.html`, `about.html`, etc.). Search for `<header` or the site nav `<nav` to update links.

**Homepage (Hero, Sections):**

- Edit `index.html`. Styling from `assets/scss/components/_hero.scss` and other partials compiled into `assets/css/main.css`. Prefer editing the SCSS in `assets/scss/` and recompiling.

**Speakers Page:**

- Static layout in `speakers.html` (no API fetch here). Update speaker cards directly in the HTML.

**Agenda / About / Exhibition / FAQ / Features pages:**

- Content is static in their respective `.html` files: `agenda.html`, `about.html`, `exhibition.html`, `faq.html`, `features.html`.

**Contact Form:**

- `contact.html` contains an inline script that POSTs to `/api/contact`. To modify fields/validations or the endpoint, update the inline `<script>` in `contact.html`.

**Conference Registration Form:**

- `register.html` has an inline script that POSTs to `/api/conference/register`. Update form fields or payload in that page's script.

**Keynote Speaker Registration:**

- `keynote-speaker-register.html` POSTs to `/api/keynote-speaker/register` (note: also contains a leftover `http://localhost:5000/...` fallback—**remove in production**).

**Sponsor Registration:**

- `sponsor-register.html` POSTs to `/api/sponsor/register`. Update inline script for field changes.

**Admin Login (token storage):**

- `admin/index.html` handles login and stores JWT as `localStorage['adminToken']`. It then redirects to dashboards.

**Admin Dashboard:**

- `admin/adminDashboard.html` includes DataTables for listings and may still reference `http://localhost:5000/api` in code. Replace with the prod API base.

**Super Admin Dashboard:**

- `admin/superAdminDashboard.html` is the most comprehensive panel. It uses many modals and `fetch` calls to endpoints such as:
  - `const response = await fetch(`${API_BASE}/admin/dashboard-stats`, {`
  - `const response = await fetch(`${API_BASE}/admin/all`, {`
  - `const response = await fetch(`${API_BASE}/admin/create`, {`
  - `const response = await fetch(`${API_BASE}/admin/admins/${adminId}`, {`
  - `const response = await fetch(`${API_BASE}/admin/registrations`, {`
  - `const response = await fetch(`${API_BASE}/admin/registrations/${id}`, {`
  - `const response = await fetch(`${API_BASE}/admin/registrations/${registrationId}`, {`
  - `const response = await fetch(`${API_BASE}/reviewing-committee/active-members`, {`
  - `const response = await fetch(`${API_BASE}/admin/speakers`, {`
  - `const response = await fetch(`${API_BASE}/admin/speakers/${speakerId}`, {`
  - `const response = await fetch(`${API_BASE}/admin/speakers/stats`, {`
  - `const response = await fetch(`${API_BASE}/reviewing-committee/send-speaker/${speakerId}`, {`

- Authorization headers are built from `localStorage.getItem('adminToken')`.
- To add/modify a CRUD section (Admins, Registrations, Speakers, Keynote Speakers, Sponsors, Reviewing Committee, Contacts), search by the related element IDs (e.g., `editRegEmail`, `editKeynoteSpeakerName`, `createCommitteeForm`) within this file.

## Configuration & Constants

- Detected `API_BASE` constants: https://icaicn-be.onrender.com/

- Token key in `localStorage`: adminToken

- Content Security Policy & caching are configured in `.htaccess` (CSP allows scripts and connections to the production API domain). Adjust if you add third-party resources.

## Notable Observations / Potential Fixes

- **Remove localhost endpoints**: Found in `admin/adminDashboard.html` and `keynote-speaker-register.html`. Keep only production API.

- **Paper pages endpoints**: `paper.html` and `paper-review.html` reference `/api/speaker/...` endpoints. Confirm naming (`/speaker/` vs `/paper/`) and adjust for clarity.

- **Heavy CSS/JS**: `assets/css/main.css` (~650KB) and `assets/css/vendor/fontawesome.css` (~650KB) are large. Consider tree-shaking Font Awesome and purging unused CSS (e.g., PurgeCSS) to improve load times.

- **Security**: Admin JWT is stored in `localStorage` (susceptible to XSS). CSP mitigates some risk, but consider moving to HTTP-only secure cookies if feasible.

- **Inline scripts**: Critical logic (forms/admin) is inline within HTML. For maintainability, consider extracting into dedicated JS modules under `assets/js/`.

- **SCSS sources included**: Prefer editing under `assets/scss/` and re-compiling to CSS for cleaner overrides, rather than editing compiled CSS directly.

## How I Can Apply Changes Quickly

- Tell me the feature you want to change (e.g., **rename a field on the Registration form**, **add a new sponsor tier**, **update the agenda layout**, **add a new Admin role**).

- I’ll point you to the exact file(s), the element IDs/classes to edit, and the code block to add/replace in the inline script or SCSS, with minimal diff-style snippets.
