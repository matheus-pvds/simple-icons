# Simple Icons — 3400+ Brand SVG Icons

A massive open-source collection of **over 3400 SVG icons for popular brands**, licensed under **CC0 1.0**. Served via CDN (simpleicons.org) and distributed as npm/Packagist packages.

## Features

- **3400+ brand icons** — continuously growing collection
- **CDN Delivery** — `cdn.simpleicons.org` with dynamic color support and auto viewbox
- **npm Package** — tree-shakable ES/CJS modules
- **PHP Packagist** — `simple-icons/simple-icons` for PHP projects
- **SDK** — programmatic icon manipulation
- **JSON Metadata** — full metadata in `data/simple-icons.json`
- **TypeScript Support** — type definitions included
- **Third-party Extensions:**
  - Figma, Raycast, Blender, Drawio, Stream Deck, Webflow, etc.
- **Third-party Libraries:**
  - Angular, Astro, Blazor, Elm, Flutter, Go, Hugo, Java, Kirby, LaTeX, Laravel, Python, React, Ruby, Rust, Svelte, Vue

## Tech Stack

Node.js, SVG, TypeScript, esbuild, svgo, svglint, PHP (Composer), Docker

## Architecture

```
icons/               → SVG icon files (3400+)
data/
  simple-icons.json  → Full metadata (titles, hex colors, source URLs, aliases, guidelines)
scripts/             → Build, release, lint, and utility scripts
tests/               → Mocha test suite
sdk.mjs / sdk.d.ts   → JavaScript SDK with type definitions
types.d.ts           → Shared TypeScript types
```

### CDN Usage

```html
<img src="https://cdn.simpleicons.org/{icon}/{color}" />
<!-- Dynamic color: https://cdn.simpleicons.org/{icon}/{color} -->
```

### npm Usage

```bash
npm install simple-icons
```

### PHP Usage

```bash
composer require simple-icons/simple-icons
```

## License

[CC0 1.0](LICENSE.md)
