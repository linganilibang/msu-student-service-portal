# MSUAS Student Services Portal

A responsive single-page student-services information portal prototype for Manicaland State University of Applied Sciences.

## Run locally
1. Extract the project folder.
2. Open `index.html` in a modern browser. Internet access is needed for the hosted p5.js and Google Fonts imports; the rest of the project is local.
3. For a local server, run `python -m http.server 8000` from this folder and open `http://localhost:8000`.

## Folder map
- `index.html` — page structure and service content
- `css/styles.css` — responsive layout, typography, cards, modal and theme
- `js/app.js` — search/filter, service detail toggles, contact mailto, navigation and demo dashboard
- `p5/campus-network.js` — interactive p5.js service-network visual
- `assets/campus-banner.svg` — original local vector banner
- `docs/sitemap-user-flow.svg` — sitemap/user-flow diagram
- `docs/wireframe.svg` — low-fidelity interface mock-up
- `docs/project-report.docx` and `.md` — project report
- `screenshots/` — browser screenshots if browser capture is supported in the environment
- `tests/test-plan.md` — test cases and known limitations

## Important prototype limitations
- This is an academic prototype, not an official MSUAS system.
- The student portal login/dashboard is simulated in client-side JavaScript. It is not secure authentication and must never be used for real credentials.
- The enquiry form prepares a message in the user's email application; it does not send/store messages on a server.
- Confirm official service hours, contacts, fees and policies directly with the university.


## GitHub Pages / mobile troubleshooting
The homepage is named `index.html` (lowercase). The p5.js animation scripts have been disabled in this mobile-friendly version to reduce the chance of the animation freezing or overwhelming mobile browsers. Upload the contents of this folder to the root of your GitHub repository, preserving the `css/`, `js/`, and `assets/` folders.
