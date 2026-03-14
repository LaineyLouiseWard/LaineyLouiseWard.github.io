# Portfolio — LaineyLouiseWard.github.io

![Astro 5](https://img.shields.io/badge/Astro-5-FF5D01?logo=astro&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-deployed-222?logo=github&logoColor=white)

Personal research portfolio showcasing PhD work in AI for weather and climate
prediction at University College Dublin. Includes project write-ups,
professional development, education history, and technical skills.

This is the central hub linking to all other repositories in the research
portfolio.

---

## Tech Stack

| Category | Tools |
|----------|-------|
| **Framework** | Astro 5 (static site generator) |
| **Language** | TypeScript |
| **Content** | Markdown with Astro Content Collections (Zod schemas) |
| **Styling** | CSS custom properties, dark/light theme toggle |
| **Deployment** | GitHub Pages |

---

## Development

```bash
npm install
npm run dev       # Start dev server at localhost:4321
npm run build     # Build to ./dist/
npm run preview   # Preview production build
```

---

## Project structure

```
src/
├── pages/              Route pages (index, about, work, development)
├── components/         Reusable Astro components (Hero, Nav, Skills, etc.)
├── layouts/            Base layout wrapper
├── content/work/       Markdown project write-ups
└── styles/             Global CSS with design system variables
public/                 Static assets (images, CV, icons)
```
