# Test Plan and Results

## Test environment
- Target: modern desktop and mobile browsers
- Method: manual functional checks and browser smoke test
- Status convention: **Prepared** means a case is ready to execute; it does not claim a manual test was performed.

| ID | Test | Expected result | Status |
|---|---|---|---|
| T01 | Open `index.html` | Portal loads and sections are visible | Prepared |
| T02 | Search for “library” | Library card remains visible; unrelated cards are hidden | Prepared |
| T03 | Choose Finance category | Bursar & Student Fees card is shown | Prepared |
| T04 | Expand a service card | Extra details become visible; button label changes | Prepared |
| T05 | Use sidebar directory item | Matching card scrolls into view and is highlighted | Prepared |
| T06 | Use mobile menu | Menu opens/closes and aria-expanded updates | Prepared |
| T07 | Submit contact form with invalid data | Browser validation prevents submission | Prepared |
| T08 | Submit valid contact enquiry | Email application opens with a draft addressed to the configured contact | Prepared |
| T09 | Select p5.js node | Status text updates and matching service card is highlighted | Prepared |
| T10 | Open portal demo | Login modal appears; this is only a simulation | Prepared |
| T11 | Resize to narrow viewport | Layout changes to single-column cards and mobile navigation | Prepared |
| T12 | Use keyboard navigation | Focus indicator is visible and skip link works | Prepared |

## Known issues / limitations to verify
- The p5.js and Google Fonts CDN imports require internet access.
- The portal demo's client-side credential check is not security; replace with a server-backed identity provider before any real deployment.
- Contact form relies on a configured desktop/mobile mail application.
- Check all current university information and links before submission or publication.
