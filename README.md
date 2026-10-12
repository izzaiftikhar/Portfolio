# Izza Iftikhar | Portfolio

Personal portfolio of **Izza Iftikhar**, a computer science student and Python backend developer who builds Flask applications, REST APIs and web platforms.

**Live site:** https://izza-iftikhar-portfolio.vercel.app/

## Features

- Looping typewriter headline and a tilting code card in the hero
- About, Skills, Projects (linked to GitHub), Experience and Education
- Contact buttons for WhatsApp, LinkedIn and email, plus a message form that opens WhatsApp or email pre-filled
- Download CV link in the navigation bar (the CV is embedded in the page)
- Sections slide in on scroll, with a progress bar and active nav highlighting
- Responsive on desktop, tablet and mobile, and respects reduced-motion settings

## Tech stack

HTML5, CSS3 and vanilla JavaScript, with Google Fonts (Fraunces, Instrument Sans, JetBrains Mono). No frameworks and no build step.

## Run locally

Open the folder in VS Code and use the **Live Server** extension, or run this from the project folder and visit `http://localhost:8000`:

```bash
python -m http.server 8000
```

## Deploy

The site is fully static. On Vercel: push the repo to GitHub, import it, set the framework preset to **Other**, leave the build settings empty and deploy. Netlify and GitHub Pages work the same way.

## Customise

- **Colours:** edit the variables at the top of the `<style>` block in `index.html`.
- **Text and links:** edit the HTML sections directly.
- **CV:** the PDF is a base64 string in `CV_B64` near the end of `index.html`. To replace it, run `base64 -w0 CV.pdf` (or `[Convert]::ToBase64String([IO.File]::ReadAllBytes("CV.pdf"))` in PowerShell) and paste the result in.

## Palette

Pale Gray `#EBEFF0`, Stone `#C6C7BD`, Graphite `#676A70`, Slate Blue `#4B5C6C`, Midnight Blue `#1C2B3C`

## Contact

[LinkedIn](https://www.linkedin.com/in/izza-iftikhar-a7400a373) | [GitHub](https://github.com/izzaiftikhar)

## License

All rights reserved. Please get in touch before reusing the design or content.
