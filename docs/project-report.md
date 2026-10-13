# MSUAS Student Services Portal — Project Report

## 1. Introduction
The MSUAS Student Services Portal is a responsive front-end prototype designed to bring common student-service information together in one place. It is an independent academic prototype and is not an official university system.

## 2. Case study and problem identification
Students may need to navigate different pages to find information about health services, library and research, fees, admissions, online learning, student affairs and counselling guidance. This project addresses that information-discovery problem with one landing page, searchable service cards, category filtering, a service directory and links to official sources.

## 3. Aim and objectives
**Aim:** Build an accessible, responsive, interactive information hub for student services.

**Objectives:**
- Present seven service categories in a consistent card layout.
- Allow keyword search and category filtering.
- Provide expandable details and direct navigation to service cards.
- Visualise relationships between service areas with p5.js.
- Help users prepare a service enquiry using their local email application.
- Demonstrate responsive interface design and front-end scripting.

## 4. Target users
The primary audience is current and prospective students who need to locate student-service information quickly. University staff may also use the directory as a signposting prototype.

## 5. Requirements
### Functional
- Display the main service directory and official-source links.
- Search services and filter by category.
- Expand and collapse details.
- Navigate from the quick directory to a matching service card.
- Interact with a p5.js service-network diagram.
- Validate an enquiry form and prepare an email draft.
- Open a simulated student-portal modal.

### Non-functional
- Responsive across desktop and mobile widths.
- Semantic HTML and accessible form labels.
- Visible keyboard focus and skip link.
- Clear notice that this is a prototype.
- Avoid implying that mock login or email form is backed by a secure server.

## 6. Technologies
- **HTML5:** semantic page structure and form controls.
- **CSS3:** design tokens, layout, responsive breakpoints, focus states and reduced-motion handling.
- **JavaScript:** search, filters, navigation, expandable cards, modal and mailto interaction.
- **p5.js:** interactive network visualization.
- **SVG:** local campus banner and diagrams.

## 7. Design and implementation
The interface uses a navy, teal and gold palette with a two-column desktop layout that collapses for smaller screens. The page consists of a header/navigation, hero section, quick links, searchable service cards, campus-network visualization, enquiry form, service-directory sidebar and footer. The sitemap and wireframe are provided under `docs/`.

## 8. Testing
A test plan is provided in `tests/test-plan.md`, covering page loading, search, filtering, service details, directory navigation, mobile menu, form validation, p5.js interaction and responsive layout. Test cases are marked **Prepared**, not passed; execute and record actual outcomes before final submission.

## 9. Limitations and ethical considerations
- The student login is a client-side simulation. Its credential check can be inspected and bypassed; it must not be used for real accounts or passwords.
- The contact form uses `mailto:` and does not store or send data on a server.
- Some fonts and the p5.js library are loaded from external CDNs and need internet access.
- University contacts, hours, fees and policies may change and should be verified against official sources.
- This prototype does not include a database, server-side API, role-based access or production authentication.

## 10. Future improvements
Add a content-management workflow for verified service updates, server-side authentication only if officially authorised, a secure backend for enquiries, automated accessibility checks, cross-browser test evidence and an offline/local copy of required libraries where licensing permits.

## 11. Conclusion
The prototype demonstrates a complete front-end concept using HTML5, CSS3, JavaScript and p5.js. The supplied folder includes source files, diagrams, documentation and a test plan. Before submission, run the application, capture genuine screenshots, execute the test cases and update the test evidence with observed results.
