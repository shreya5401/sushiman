# Sushiman

A modern, responsive Japanese food restaurant landing page built with vanilla HTML, CSS, and JavaScript.

## Overview

Sushiman is a visually rich landing page for a Japanese food delivery and dining experience. The site showcases popular dishes, trending sushi and drinks, and allows customers to sign up for offers — all wrapped in smooth scroll animations and an elegant dark aesthetic.

## Features

- **Hero Section** — Striking full-screen banner with a call-to-action and social proof (24k+ happy customers)
- **About Us** — Brand mission centered around *Omotenashi* (Japanese hospitality)
- **Popular Foods** — Filterable menu catalogue with dish cards showing ratings and prices
- **Trending Section** — Highlights trending sushi varieties and traditional Japanese drinks
- **Newsletter Subscription** — Email sign-up form for exclusive offers
- **Scroll Animations** — Smooth entrance animations powered by AOS (Animate On Scroll)
- **Responsive Design** — Mobile-friendly navigation and layout

## Tech Stack

| Tool | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Styling with custom properties and modular section files |
| JavaScript (ES Modules) | Interactivity and dynamic rendering |
| [Vite](https://vitejs.dev/) | Development server and build tool |
| [AOS](https://michalsnik.github.io/aos/) | Scroll-triggered animations |

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher)

### Installation

```bash
# Clone the repository
git clone <your-repo-url>
cd sushi

# Install dependencies
npm install
```

### Development

```bash
npm run dev
```

Opens the site at `http://localhost:5173` with hot module replacement.

### Production Build

```bash
npm run build
```

Output is generated in the `dist/` folder.

### Preview Production Build

```bash
npm run preview
```

## Project Structure

```
sushi/
├── assets/          # Images, icons, and SVGs
├── css/
│   ├── style.css    # Root styles and CSS variables
│   └── sections/    # Per-section stylesheets
│       ├── header.css
│       ├── hero.css
│       ├── about.css
│       ├── popular.css
│       ├── trending.css
│       ├── subscribe.css
│       └── footer.css
├── js/
│   └── script.js    # AOS init, food cards, and trending data
├── index.html       # Main HTML entry point
├── package.json
└── vite.config.js
```

## Sections

| Section | ID | Description |
|---|---|---|
| Hero | — | Welcome banner with order CTA |
| About Us | `#about-us` | Brand story and mission |
| Popular Foods | `#menu` | Filterable food catalogue |
| Trending | `#food` | Featured sushi and Japanese drinks |
| Services | `#services` | Newsletter subscription |

## Fonts

- **Playfair Display** — Headings and titles
- **Plus Jakarta Sans** — Body text and UI elements
