# bcoutinho-personal-web-page

Brennan Coutinho — Personal Landing Page
A clean, modern, and fully responsive personal portfolio website built for recruiters and hiring managers evaluating candidates for entry-level Data Analyst and Business Analyst roles.

Live Preview
Deploy via Replit to get a public .replit.app URL.

About the Project
This is a single-page personal landing page designed to complement a traditional resume by showcasing Brennan Coutinho's personal story, technical skills, and project experience in a more engaging format.

Built as part of a BAIS 3300 course requirement at the University of Iowa.

Sections
Section	Description
Hero	Name, tagline, headshot, and call-to-action buttons
About	Personal background, international student story, career focus
Skills	Tools & platforms + analytical techniques displayed as pill tags
Projects	Featured BIAS Analysis project + placeholders for upcoming work
Contact	Email, LinkedIn, and GitHub links
Tech Stack
HTML5 — Page structure
CSS3 — Styling, layout, and animations
Vanilla JavaScript — Scroll-triggered fade-in animations, smooth navigation
Google Fonts (Inter) — Typography
No frameworks, build tools, or dependencies required.

File Structure
/
├── index.html        # Main page (all sections)
├── styles.css        # All styles and responsive breakpoints
├── /images
│   └── profile.jpg   # Professional headshot
├── PRD.md            # Product Requirements Document
├── STANDARDS.md      # Technical design standards
└── README.md         # This file
Running Locally
No build step needed. Serve the files with any static web server.

Using Python (recommended):

python3 -m http.server 5000
Then open http://localhost:5000 in your browser.

Design Highlights
Color palette: Navy primary #1a3557, blue accent #2563eb, light neutral backgrounds
Typography: Inter (300–700 weight)
Responsive: 3-column layout on desktop → single column on mobile (breakpoints at 900px and 600px)
Animations: Intersection Observer fade-in as sections enter the viewport
Navigation: Fixed top bar with frosted glass blur effect and smooth scroll
Contact
Email: brennanncoutinho@gmail.com
LinkedIn: brennan-coutinho-a47519295
GitHub: brennan-coutinho
