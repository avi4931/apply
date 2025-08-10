## Project Overview

This is a web project for ISBR Business School. The project aims to create a landing page that provides information about the school and allows users to apply. The project uses basic HTML, CSS, and JavaScript, with no external frameworks.

## Implemented Features and Design

- **Initial Structure:** The project has a basic HTML structure with linked CSS and JavaScript files.
- **Navigation Bar:** A navigation bar with links to different sections of the page.
- **Header Section:** A header section with a background image and a title.
- **About Us Section:** A section providing information about the school with an image, video, and description.
- **Programs Section:** A section detailing the academic programs offered with flip cards that show program details on hover.
- **Admissions Section:** A section with information about the admission process and an application form.
- **Recruiters Section:** A section showcasing key recruiters with their logos in an Owl Carousel.
- **Footer Section:** A footer with contact information and social media links.
- **Owl Carousel:** Integrated Owl Carousel for displaying recruiters.
- **Bootstrap:** Added Bootstrap CSS and JavaScript for potential future use of Bootstrap components and styling.
- **Flip Cards:** Implemented flip cards for the programs section with a flip animation on hover and styled to appear as rounded rectangles with a border and no images on the front. The layout of the About section has been adjusted.

## Plan for Current Change

The user wants to add two new sections to the `programs.html` page: "Law" and "Executive Education & Doctoral". Each section should contain flip cards for the programs listed in the provided screenshot, following the existing flip card design.

1.  Add new `<h3>` titles for "Law" and "Executive Education & Doctoral" in `programs.html`.
2.  Below each new title, add a `.flip-card-container` to hold the flip cards for that section.
3.  Within each container, add the necessary `.flip-card`, `.flip-card-inner`, `.flip-card-front`, and `.flip-card-back` divs for each program listed in the screenshot (BBA LLB, LLB, Certification Course in Law, Executive PGDM, FPM, Ph.D. in Management, Ph.D. in Commerce).
4.  Add the program names to the front of the cards and placeholder descriptions to the back, similar to the existing flip cards.
