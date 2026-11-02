# WEDE5020 Part 3 – Regyana Bed & Breakfast

## Student Information

- **Student Number:** ST10528245
- **Module:** WEDE5020 Web Development
- **Project:** Regyana Bed & Breakfast

## Project Overview

This project is the Part 3 update of the Regyana Bed & Breakfast website. The site provides information about accommodation, breakfast, facilities, catering, event décor and contact details for visitors to the Koster area.

## Pages

- `index.html` – Home page with introduction and FAQ accordion.
- `about_us.html` – Organisation history, mission, vision and team.
- `services.html` – Services, search/filter, tabs and image lightbox.
- `enquiry.html` – Service enquiry form with JavaScript validation and an estimated response based on the selected service.
- `contact.html` – General contact form with JavaScript validation and a compiled `mailto:` message.
- `robots.txt` – Crawler instructions.
- `sitemap.xml` – Search-engine sitemap.
- `_headers` – Basic security headers for compatible static hosting platforms.

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Responsive images using `picture`, `srcset` and `sizes`
- Google Maps embedded maps
- GitHub / GitHub Pages or another free static hosting platform

## Part 3 Functionality

### JavaScript enhancements

1. FAQ accordion on the Home page.
2. Service search and category filtering on the Services page.
3. Tabbed service information on the Services page.
4. Image gallery/lightbox for accommodation and event décor images.
5. Intersection Observer animation for content reveal.
6. Dynamic service enquiry feedback based on selected service and guest count.
7. Client-side validation for both forms.
8. Contact form compilation into a `mailto:` URL addressed to `info@regyana.co.za`.
9. Dynamic copyright year.
10. Responsive Google Maps embeds on the Contact page.

## SEO implementation

- Page-specific title tags.
- Page-specific meta descriptions.
- Relevant keywords for Koster accommodation and the business services.
- Structured H1/H2/H3 heading hierarchy.
- Descriptive image `alt` text.
- Responsive/mobile-friendly design.
- Internal links between the main pages.
- `robots.txt`.
- `sitemap.xml`.
- Local business wording and Koster location information.
- Responsive image loading to reduce unnecessary image downloads.
- CSS/JavaScript kept in external files for maintainability.

### Deployment note

The sitemap and `robots.txt` currently use placeholders:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

Before publishing, replace `YOUR-USERNAME` and `YOUR-REPOSITORY` with the actual GitHub Pages address. Do not submit the placeholder URL.

## Form Functionality

### Enquiry form

The enquiry form collects:

- Full name
- Email address
- Phone number
- Service required
- Preferred date
- Number of guests
- Enquiry message

JavaScript validates the required information and then displays service-related pricing or quotation guidance. Accommodation and breakfast provide starting estimates using the stated approximate rates; event services explain that a quotation depends on the requirements.

### Contact form

The contact form collects:

- Full name
- Email address
- Phone number
- Message type
- Full message

After validation, JavaScript compiles the information into an email body and opens the visitor's default email application with `info@regyana.co.za` as the recipient.

## Part 2 Feedback / Correction Changelog

The original Part 2 project did not contain lecturer feedback in the supplied files. Therefore, no specific lecturer comment has been invented. The following entries document corrections and improvements made to the supplied Part 2 website.

| Date | Change | Reason |
|---|---|---|
| 2026-11-01 | Corrected the Services page location by placing `services.html` in the project root so the existing navigation links resolve correctly. | The supplied Part 2 package stored the page inside `js/` while the navigation linked to `services.html` at the root. |
| 2026-11-01 | Added JavaScript functionality for accordion, tabs, filtering, lightbox, animations and form processing. | Required Part 3 functionality and improved user interaction. |
| 2026-11-01 | Added client-side validation and user-facing error messages to both forms. | Required Part 3 form validation. |
| 2026-11-01 | Added service-specific enquiry responses and starting estimates. | The enquiry form must process valid information and provide a relevant response about cost or availability. |
| 2026-11-01 | Updated the contact form so validated information is compiled into a `mailto:` message. | Required Part 3 contact-form submission behaviour. |
| 2026-11-01 | Added page-specific meta descriptions, keywords, robots directives and improved image alternative text. | Required on-page SEO improvements. |
| 2026-11-01 | Added `robots.txt` and `sitemap.xml`. | Required SEO files. |
| 2026-11-01 | Added responsive search/filter controls and service tabs. | Improves content discovery and demonstrates DOM manipulation. |
| 2026-11-01 | Added lightbox functionality for service images. | Required interactive gallery/lightbox functionality. |
| 2026-11-01 | Added basic security-related static hosting headers. | Supports safer deployment of the static website. |
| 2026-11-01 | Updated the footer year dynamically with JavaScript. | Prevents the copyright year becoming outdated. |

## References

- Google Maps. Used for the embedded location and Koster Dam maps.
- Google Developers. *Search Engine Optimisation (SEO) Starter Guide*. https://developers.google.com/search/docs/fundamentals/seo-starter-guide
- MDN Web Docs. *HTML forms*. https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms
- MDN Web Docs. *Constraint validation*. https://developer.mozilla.org/en-US/docs/Web/HTML/Constraint_validation
- MDN Web Docs. *DOM scripting*. https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting/DOM_scripting
- MDN Web Docs. *Intersection Observer API*. https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API
- MDN Web Docs. *Dialog element*. https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/dialog
- Sitemaps.org. *Sitemaps protocol*. https://www.sitemaps.org/protocol.html

## Publishing Checklist

1. Commit the updated project to the GitHub repository using descriptive commit messages.
2. Push the changes to the remote repository.
3. Replace the placeholder GitHub Pages URL in `robots.txt` and `sitemap.xml`.
4. Enable GitHub Pages or deploy the project to another free static hosting service such as Netlify.
5. Test all navigation links.
6. Test both forms with valid and invalid data.
7. Test the Services search, filter, tabs and lightbox.
8. Test the site at desktop and mobile widths.
9. Confirm that the published sitemap URL is accessible.
10. Submit the GitHub repository link and deployed website link through the LMS.
