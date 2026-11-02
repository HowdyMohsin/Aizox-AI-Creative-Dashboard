<div align="center">

<img src="images/logo/logo.svg" alt="AIZOX logo" width="240" />
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="images/logo/logo.svg" />
  <img src="images/logo/logo-white.svg" alt="AIZOX logo" width="360" height="126" style="width: 360px; max-width: 100%; height: auto;" />
</picture>

# AIZOX — AI Creative Dashboard

**A responsive dashboard interface for AI-powered creative tools.**

Explore a polished front-end concept for image generation and editing, AI chat, video creation, code generation, and website building.

![HTML5](https://img.shields.io/badge/HTML5-markup-e34f26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-styles-1572b6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-interactions-f7df1e?style=flat-square&logo=javascript&logoColor=222)
![Responsive](https://img.shields.io/badge/layout-responsive-0d8668?style=flat-square)

[Features](#features) · [Pages](#pages) · [Getting started](#getting-started) · [Project structure](#project-structure) · [Author](#author) · [License](#license)

</div>

## Overview

AIZOX is a multi-page dashboard UI concept for creative AI workflows. It brings common generation tools, account screens, and support pages together in one consistent interface, with responsive layouts and reusable styles.

> **Front-end UI only:** this project is a static HTML/CSS/JavaScript interface. AI generation, authentication, billing, and form submissions require backend services and are not provided here.

## Features

- AI assistant and question-answering screens
- Text-to-image, image-to-image, and image editing interfaces
- Text-to-video and video-to-video interfaces
- Code generator and website builder screens
- Login, sign-up, password recovery, and pricing pages
- FAQ, documentation, contact, and changelog pages
- Responsive dashboard layout with light/dark theme support
- Sass source files alongside compiled CSS

## Pages

| Page | File |
| --- | --- |
| Dashboard | [`index.html`](index.html) |
| AI chat | [`ai-chat-bot.html`](ai-chat-bot.html) |
| Question AI | [`question-ai.html`](question-ai.html) |
| Question AI results | [`question-ai-results.html`](question-ai-results.html) |
| Text to image | [`text-to-image.html`](text-to-image.html) |
| Image to image | [`image-to-image.html`](image-to-image.html) |
| Image results | [`image-to-image-results.html`](image-to-image-results.html) |
| Image editing | [`image-edit.html`](image-edit.html) |
| Text to video | [`text-to-video.html`](text-to-video.html) |
| Video to video | [`video-to-video.html`](video-to-video.html) |
| Code generator | [`code-generator.html`](code-generator.html) |
| Website builder | [`website-builder.html`](website-builder.html) |
| Pricing | [`pricing.html`](pricing.html) |
| Login / sign up / password recovery | [`login.html`](login.html), [`sign-up.html`](sign-up.html), [`forgot-password.html`](forgot-password.html) |
| Help and contact | [`faq.html`](faq.html), [`faq-document.html`](faq-document.html), [`contact.html`](contact.html) |
| Changelog | [`change-log.html`](change-log.html) |

## Getting started

No package installation or build step is required to preview the included pages.

1. Download or clone this repository.
2. Open `index.html` in a browser.

For a local web server, run this command from the project directory:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Project structure

```text
.
├── index.html             # Dashboard entry point
├── *.html                 # Tool, account, and support pages
├── css/                   # Compiled styles and third-party stylesheets
├── scss/                  # Sass source
├── js/                    # UI scripts and supporting libraries
├── images/                # Logos, illustrations, and interface assets
├── font/                  # Satoshi font files
└── icon/                  # Icon font assets
```

## Author

**Mohsin Ali** — MERN Stack Developer & JavaScript Specialist

- **Email:** [Mohsinalidigital0@gmail.com](mailto:Mohsinalidigital0@gmail.com)
- **GitHub:** [@HowdyMohsin](https://github.com/HowdyMohsin)
- **Portfolio:** [mohsin-ali--portfolio.vercel.app](https://mohsin-ali--portfolio.vercel.app/)

## License

This project is distributed under the [MIT License](LICENSE). Third-party assets may be subject to their own license terms.

---

<div align="center">

Built by [Mohsin Ali](https://github.com/HowdyMohsin) · [Portfolio](https://mohsin-ali--portfolio.vercel.app/)

</div>
