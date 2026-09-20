# AG Price Scope Website

Official Urdu-first product website for **AG Price Scope**, a Windows desktop application by AG Pixel Creater. The application helps users search for a product across available supported sources, compare observed prices, and generate a price-analysis report.

## Features

- Fully localized Urdu and English interface with persisted language preference
- Persisted dark and light themes with RTL/LTR layout switching
- Responsive product, process, features, report, installation, and documentation sections
- Clearly labeled product UI mockup with no invented market prices
- Honest download state that does not invent an installer or release URL
- Confirmed repository link: [AG-Pixel-creater/AG-Price-Scope-Website-](https://github.com/AG-Pixel-creater/AG-Price-Scope-Website-)

## Tech Stack

React, TypeScript, Vite, and CSS design tokens. Centralized copy lives in `src/localization.ts`.

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## Development

```bash
npm install
npm run dev
```

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the Oxlint configuration

## Build

```bash
npm run build
npm run preview
```

```json
{
  "$schema": "./node_modules/oxlint/configuration_schema.json",
  "plugins": ["react", "typescript", "oxc"],
  "options": {
    "typeAware": true
  },
  "rules": {
    "react/rules-of-hooks": "error",
    "react/only-export-components": ["warn", { "allowConstantExport": true }]
  }
}
```

## Deployment

Deploy the generated `dist/` directory to a static host. Add a canonical URL and a real release download asset when those production details are available.

## Version

Website and product information are aligned to version 0.0.1.

## License

No license information was provided for this project.
