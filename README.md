# Galaxy Portfolio

A personal portfolio website with a space and galaxy theme built with React, TypeScript, and Tailwind CSS. Features smooth animations, 3D particle effects, and a clean project showcase.

## Features

- **Animated Galaxy Background**: Canvas-based particle system simulating a deep-space starfield with drift and twinkle effects.
- **Project Showcase**: Filterable grid of engineering and software projects with live demo and repository links.
- **Responsive Design**: Mobile-first layout that adapts cleanly across all device widths.
- **Contact Form**: Integrated Formspree contact endpoint with client-side validation.

## Quick Start

```bash
git clone https://github.com/4techno/galaxy-portfolio.git
cd galaxy-portfolio
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

## Stack

- **Framework**: React 18 + TypeScript + Vite
- **Styling**: Tailwind CSS 3
- **Animations**: Framer Motion
- **Canvas**: Vanilla Canvas API for starfield rendering
- **Deployment**: Cloudflare Pages

## Project Structure

```
src/
├── components/
│   ├── StarField.tsx       ← Canvas particle starfield animation
│   ├── ProjectCard.tsx     ← Filterable project card component
│   └── ContactForm.tsx     ← Validated contact form
├── data/
│   └── projects.ts         ← Project entries and metadata
└── App.tsx
```

## License

MIT License.
