# The School of Engineering & Technology

A South African digital-first school concept for developing engineers, technologists and innovators through practical, accessible learning.

![Learners collaborating on an engineering project](assets/engineering-hero.png)

## Institutional foundation — Phase 0

The working foundation documents are in [`docs/institutional-foundation/`](docs/institutional-foundation/README.md). Their reading order, confirmed decisions D-001 and D-002, and current in-progress status are recorded in that directory's overview.

## Starting point

This repository begins with a responsive, UI-only landing page for the proposed School of Engineering & Technology. It introduces the institution's digital-first learning approach, proposed engineering study areas, and long-term vision to grow from online and offline learning into a physical campus.

The page is a visual starting point only. It does not provide course delivery, enrolment, student accounts, assessments, or other backend services. The study areas are proposed, and this project does not claim institutional or programme accreditation, professional recognition, or authority to award qualifications. South African regulatory requirements—including relevant CHE, SAQA and professional council requirements—must be considered before any qualification claims or offerings are made.

## Run locally

No build step or package installation is required. Open `index.html` in a browser, or serve the project directory with any static file server. For example:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Files

- `index.html` — semantic landing-page structure and page copy.
- `styles.css` — visual system, responsive layouts, and reduced-motion support.
- `script.js` — mobile navigation and current-year display.
- `assets/engineering-hero.png` — original hero image used on the landing page and in this README.

The page uses Google Fonts (Manrope and DM Mono) when a network connection is available, with system fallbacks.
