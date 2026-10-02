# Peyton T. Smith &mdash; Personal Website & Portfolio

A professional, responsive multi-page personal website and portfolio built for **Peyton T. Smith**, an Information Systems undergraduate at **Louisiana State University** (Expected May 2027).

* **Live Site:** [https://peytonsmith-geaux.github.io/peyton-smith/](https://peytonsmith-geaux.github.io/peyton-smith/)
* **Repository:** [https://github.com/peytonsmith-geaux/peyton-smith](https://github.com/peytonsmith-geaux/peyton-smith)

---

## 1. Project Overview & Specification

This repository houses a clean, hand-crafted personal website designed from the ground up to present academic credentials, technical skills, coursework projects, and professional background. The project adheres to a strict four-file core web structure, avoiding third-party front-end frameworks in favor of real, inspectable, semantic source code.

### Core File Structure
* **[`index.html`](index.html)** &mdash; **Home & About:** Introduces professional background, career aspirations in Information Systems, embedded high-resolution portrait (`headshot.jpg`), LSU coursework highlights, and quick-contact cards.
* **[`resume.html`](resume.html)** &mdash; **Curriculum Vitae:** Comprehensive interactive resume detailing education, technical competencies (SQL, Python, Excel, Git), fine dining client-facing leadership experience, industry certifications, and direct actions to view or print the official 1-page resume ([`Peyton_Smith_CV.pdf`](Peyton_Smith_CV.pdf)).
* **[`project.html`](project.html)** &mdash; **Technical Showcase:** Featured system showcase detailing completed web solutions along with in-progress technical projects across Python application design (ISDS 3107), relational database management (ISDS 3110), and AWS cloud foundational studies.
* **[`style.css`](style.css)** &mdash; **Master Design System:** Vanilla CSS stylesheet driven by custom CSS variables (`:root`), modular typography, flexible grid/flexbox layouts, micro-interaction transitions, responsive breakpoints, and print media optimization.

### Supporting Assets
* **[`headshot.jpg`](headshot.jpg)** &mdash; Professional portrait integrated into the homepage about section.
* **[`Peyton_Smith_CV.pdf`](Peyton_Smith_CV.pdf)** &mdash; Standardized, high-resolution 1-page resume PDF linked directly to header action buttons.
* **[`qrcode.png`](qrcode.png) / [`qrcode.svg`](qrcode.svg)** &mdash; Custom branded QR codes with monogrammed PTS emblem for digital and physical networking materials.

---

## 2. Design System & Aesthetics

* **Color Palette:** Warm LSU-inspired pastel lavender (`#8a65a8`, `#5c3b78`) paired with refined antique gold accents (`#c59b27`, `#a67c17`) over soft ambient card surfaces (`rgba(255, 255, 255, 0.88)`).
* **Typography:** Classic, high-editorial **EB Garamond** for headers and body narrative, harmonized with **Plus Jakarta Sans** for metadata pills, tags, action buttons, and navigational elements.
* **Responsive Architecture:** Mobile-first considerations with dynamic fluid grid structures (`grid-cols-2`, `grid-cols-3`) and media queries adapting cleanly to phone, tablet, and desktop viewports.
* **Print Optimization:** Dedicated `@media print` rules strip away web chrome (navbar, buttons, footer) to ensure crisp, printer-friendly page reproduction without awkward layout clipping.

---

## 3. Project Reflection

### Balancing Responsive Web UX Against Fixed-Format Document Delivery

A key design challenge encountered during the development of this project was determining how best to present a professional resume on the web. Early in the design process, we experimented with embedding an inline PDF viewer directly inside the resume webpage. While an embedded document preview seemed initially convenient, user testing quickly revealed significant usability friction: on smaller screens and mobile devices, an embedded PDF container created nested scrollbars, hindered touch navigation, and broke the natural vertical rhythm of the site.

To resolve this, we made the architectural decision to decouple the presentation layers:

1. **The Interactive Web CV:** We built the on-page curriculum vitae using native, semantic HTML5 elements and CSS Grid cards. This format is fully fluid, screen-reader accessible, searchable, and natively responsive across every device size.
2. **The Archival Document Layer:** We linked the standardized 1-page PDF ([`Peyton_Smith_CV.pdf`](Peyton_Smith_CV.pdf)) through explicit top-level action buttons (`Print / Save as PDF` and `Peyton Smith CV`) configured with `target="_blank"`. This delegates document rendering directly to the browser's native PDF engine, allowing recruiters to view, download, or print a pixel-perfect physical document with a single click.

**Takeaway:** In business information systems, understanding user context is paramount. Forcing a static, print-oriented document into a fluid web viewport compromises both formats. Separating the fluid exploratory interface from the fixed archival document provided a cleaner user experience, reduced cognitive load, and honored the strengths of both mediums.

---

## 4. Author & Contact

**Peyton T. Smith**  
B.S. in Information Systems &bull; Louisiana State University (Expected May 2027)  
* Email: [psmi136@lsu.edu](mailto:psmi136@lsu.edu)  
* Phone: (214) 226-8848  
* Location: Baton Rouge, LA &bull; Dallas, TX  
* LinkedIn: [linkedin.com/in/peyton-smith](https://linkedin.com)  
* GitHub: [github.com/peytonsmith-geaux](https://github.com/peytonsmith-geaux)
