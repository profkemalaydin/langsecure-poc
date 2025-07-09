# langsecure-poc

A proof-of-concept project with Tailwind CSS v4 setup.

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Build Tailwind CSS:
   ```bash
   npm run build
   ```

3. For development with automatic rebuilding:
   ```bash
   npm run dev
   ```

## Project Structure

- `src/input.css` - Main CSS file with Tailwind imports
- `dist/output.css` - Generated CSS file (do not edit manually)
- `index.html` - Demo HTML file showcasing Tailwind CSS
- `tailwind.config.js` - Tailwind CSS configuration
- `postcss.config.js` - PostCSS configuration

## Usage

- Open `index.html` in your browser to see the Tailwind CSS demo
- Edit HTML classes in `index.html` or add new files
- Run `npm run build` to regenerate CSS after changes
- Use `npm run dev` for automatic rebuilding during development

## Tailwind CSS Version

This project uses **Tailwind CSS v4.1.11**, which includes the new CSS engine and improved performance.

## Available Scripts

- `npm run build` - Build CSS for production
- `npm run dev` - Start development mode with file watching
- `npm test` - Run tests (placeholder)