# Pixelshift

> **Turn your `.sketch` files into production-ready websites. Matched to the pixel.**

Pixelshift is a specialized frontend engineering studio converting Sketch design files into semantic, ultra-performant, responsive HTML5, modern CSS3, and JavaScript.

---

## ✦ Key Features

- **Sub-Pixel Accuracy Engine**: Hand-crafted CSS tokens and layout architecture matched 1:1 against original Sketch artboards.
- **Interactive Before/After Showcase**: In-browser split-view slider comparing Sketch vector layers with the rendered DOM.
- **Instant Project Estimator**: Transparent, real-time pricing calculator for artboard count, framework stack (HTML5/CSS3, Tailwind, React/Next), and delivery speed.
- **Enterprise Security & Strict NDA**: Private client sandbox workflows ensuring confidential design assets remain protected under mutual NDA.
- **Zero Auto-Export Bloat**: Human-authored, accessible markup with 98+ Lighthouse scores across Performance, Accessibility, and Best Practices.
- **Client Intake Studio**: Integrated file drag-and-drop intake system for `.sketch` and archive uploads.

---

## ✦ Brand Palette & Design Tokens

Pixelshift uses an Apple-inspired editorial visual hierarchy built around a warm, premium color palette:

| Token | Hex | Role |
| :--- | :--- | :--- |
| **Cream** | `#F9E6A8` | Background highlights, soft accents |
| **Gold** | `#F2A900` | Primary interactive elements, accents, status indicators |
| **Burnt Ochre** | `#CC6F00` | CTA buttons, active links, emphasis states |
| **Espresso** | `#4D2A00` | Primary body ink, typographic contrast |
| **Dark Espresso** | `#1A0D02` | Hero billboard, dark section canvas |

---

## ✦ Project Structure

```text
pixelshift/
├── index.html            # Main production landing page & interactive application
├── assets/               # Brand assets, vectors, and imagery
│   ├── favicon.svg       # Vector browser icon
│   ├── logo.svg          # Official brand vector logo
│   ├── icon-check.svg    # UI status vector icon
│   ├── icon-folder.svg   # Dropzone folder vector icon
│   ├── icon-lock.svg     # Security badge vector icon
│   ├── icon-upload.svg   # Upload vector icon
│   ├── palette.png       # Brand color palette reference
│   └── sketch-to-code-transformation.jpg
├── .env.example          # Safe configuration template (no secrets committed)
├── .gitignore            # Enterprise security exclusions & credential protection
└── README.md             # Project documentation
```

---

## ✦ Quick Start

Pixelshift is built with standard web technologies (vanilla HTML5, modern CSS3, and vanilla ES6+ JavaScript) and requires zero build steps or package managers.

### Run Locally

You can serve the project using any local HTTP server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (npx)
npx serve .
```

Open `http://localhost:8000` in your web browser.

---

## ✦ Security & Confidentiality

- **Mutual Non-Disclosure Agreement (NDA)**: All uploaded design files and proprietary artboards remain the exclusive intellectual property of their respective owners.
- **Zero Secret Ingestion**: This repository enforces strict credential exclusion via `.gitignore` to ensure no sensitive API keys, certificates, or tokens are ever committed.

---

## ✦ License

Copyright © 2026 Pixelshift Inc. All rights reserved.
