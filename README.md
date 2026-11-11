# Anit Vishal Srivastava — Advocate Website

A lightweight, responsive static website built with **HTML, CSS and vanilla JavaScript**. No React, build tools or backend are required.

## Run locally

1. Extract the ZIP file.
2. Open the `anit-vishal-srivastava-website` folder.
3. Double-click `index.html` to preview it in a browser.

For a local development server, open the folder in VS Code and use the Live Server extension, or run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Update the details

All professional details are centralized in:

```text
js/config.js
```

Edit the values after confirming them with the advocate. The website pages read from this file automatically.

Fields currently set as placeholders:
- Bar Council and enrolment details
- Enrolment year
- Qualifications
- Years of practice
- Courts / forums
- Office address
- Phone and email
- Office hours

Practice areas and their descriptions can also be edited in `js/config.js`.

## Project structure

```text
anit-vishal-srivastava-website/
├── index.html
├── about.html
├── practice-areas.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   ├── config.js
│   └── script.js
├── assets/
│   └── images/
└── README.md
```

## Before publishing

- Verify every professional detail with the advocate.
- Remove any practice area that does not accurately describe the practice.
- Add only accurate office and contact details.
- Check the current Bar Council of India rules and applicable requirements for advocate websites, including any required intimation or approval.
- Do not add testimonials, client solicitation, outcome guarantees, rankings, superlatives or promotional claims.
- The general-information disclaimer is not a substitute for compliance with professional rules.

## Hosting

This is a static site and can be hosted on GitHub Pages, Vercel, Netlify or another static hosting provider. Upload the contents of this folder; no build command is needed.
