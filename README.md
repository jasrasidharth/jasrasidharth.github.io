# Sid Jasra — Personal Resume Website

Live at: [sidjasra.github.io](https://sidjasra.github.io)

## About
Personal resume website built with plain HTML, CSS, and JavaScript. No frameworks, no dependencies — just clean, fast, mobile-friendly code.

## Project Structure
```
sidjasra.github.io/
├── index.html        # Entry point — loads styles and scripts
├── css/
│   └── style.css     # All styling and layout (Warm Sand theme)
├── js/
│   └── render.js     # Builds the page from content data
└── data/
    └── content.js    # ← Edit this file to update resume content
```

## How to Update the Resume
All resume content lives in **`data/content.js`**. You never need to touch HTML or CSS.

| What you want to change | Where to edit |
|---|---|
| Name, email, phone, location | `contact` object |
| Executive summary | `summary` string |
| Certifications in header | `certifications_header` array |
| Core competencies | `competencies` array |
| Add / update a job | `experience` array |
| Technical skills | `skills` array |
| Education | `education` array |

After saving your changes, GitHub Pages automatically redeploys within ~1 minute.

## Tech Stack
- HTML5 / CSS3 / Vanilla JavaScript
- [DM Sans + Source Serif 4](https://fonts.google.com/) via Google Fonts
- Hosted on GitHub Pages
