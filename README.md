# Dental Resources Library — clinic cloudstack property

The reference and data-led property of the Dr Shahid Islam Dental Clinic cloudstack. It deploys to **GitHub Pages** from the repo `cloudstack-clinic-resources`. Theme: slate grey with an amber accent, table-forward reference design, plain static HTML/CSS with no build step and no external fonts or CDNs.

## What this site is

A free patient reference library published for Dr Shahid Islam Dental Clinic, DHA Phase 5, Karachi. It holds treatment comparison tables, an explainer on how dental treatment costs are quoted, a first-visit checklist, a library of plain-language patient guides, aftercare references, a dental X-ray guide and a dentures care guide. It carries direct links to the matching pages on https://drshahidislam.com and interlinks with the three sister properties (Karachi Dental Guide flagship, Dental Knowledge Centre, DHA Karachi Dental Local Guide).

## Structure

| Path | Page |
|---|---|
| `/` | Library home |
| `/about/` | About the library and the clinic |
| `/resources/` | Resources index |
| `/treatment-comparison/` | Treatment comparison tables |
| `/how-dental-costs-are-quoted/` | How dental costs are quoted |
| `/first-visit-checklist/` | First visit checklist |
| `/patient-guide-library/` | Patient guide library (flagship) |
| `/aftercare-guides/` | Aftercare reference guides |
| `/dental-xray-guide/` | Dental X-ray guide |
| `/dentures-care-guide/` | Dentures care guide |
| `/faq/` | Reference FAQs |
| `/contact/` | Clinic contact, hours and map |
| `/privacy/` | Privacy and disclosure |

Plus `styles.css`, `robots.txt`, `404.html` and `favicon.svg`. A `sitemap.xml` is added at freeze time.

## Build notes

- Canonical and Open Graph URLs use the build token `{{BASE}}`, replaced with the live GitHub Pages base URL at freeze time. Sister-site links use `{{SISTER_FLAGSHIP}}`, `{{SISTER_KNOWLEDGE}}` and `{{SISTER_LOCAL}}` tokens, replaced in the same pass. Tokens appear in href attributes only, never in visible text.
- All clinic facts (address, phone, hours, geo coordinates) follow the master cloudstack SPEC and match the main clinic website.
- No prices are stated anywhere on this property: the clinic quotes after examination, and the cost pages explain how quotes are built and link to the cost guides on the main site.
