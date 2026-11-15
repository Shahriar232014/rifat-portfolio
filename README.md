# RIFAT.DEV — Personal Portfolio

Premium, responsive developer portfolio for **MD. Rashid Shahriar (Rifat)**, a CSE undergraduate at the University of Liberal Arts Bangladesh.

## Stack
- React 18 + TypeScript
- Vite 6
- Tailwind CSS 3 + custom responsive CSS
- Lucide React icons
- Native IntersectionObserver scroll reveals (no animation dependency)

## Getting started

Requires Node.js 20 or later.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually `http://localhost:5173`).

## Production build

```bash
npm run build
npm run preview
```

The deployable site is generated in `dist/`.

## Deploy on Vercel

1. Push this project to your own GitHub repository.
2. Import the repository at https://vercel.com/new.
3. Select **Vite** if prompted; build command `npm run build`; output directory `dist`.
4. Deploy. Every section uses in-page anchors, so no special SPA routing configuration is necessary.

## Deploy on GitHub Pages

The Vite `base: './'` setting supports repository-subpath deployments.

1. Push to a GitHub repository.
2. In repository Settings → Pages, select GitHub Actions.
3. The included `.github/workflows/deploy.yml` will deploy the `dist/` directory when you push to `main`.
4. Wait for the workflow to complete, then open the Pages URL shown in Settings → Pages.

## File structure

```
rifat-portfolio/
├── .github/workflows/deploy.yml
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── tsconfig.json
├── tsconfig.app.json
├── vite.config.ts
└── src/
    ├── main.tsx
    ├── App.tsx
    └── styles.css
```

## Accuracy note

Academic projects are labeled ongoing / research / exploration. There are no invented performance metrics or unverified project repository URLs. The skill list is described as learning/exploration rather than professional mastery. Verify your own hands-on skills before using this site for applications.

## Customization

Edit the content and navigation in `src/App.tsx`, colors and breakpoints in `src/styles.css`, and SEO metadata in `index.html`. GitHub and email links are defined at the top of `src/App.tsx`.

## Accessibility & performance

Semantic section landmarks, visible mobile menu controls, external link safety attributes, `prefers-reduced-motion` support, responsive layout, and lightweight SVG icons. Fonts are loaded from Google Fonts and need an internet connection; system fallbacks are configured.
