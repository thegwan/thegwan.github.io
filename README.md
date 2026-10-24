# thegwan.github.io

Personal site, built with [Astro](https://astro.build) and deployed to GitHub Pages by `.github/workflows/deploy.yml` on every push to `main`.

```sh
npm install
npm run dev      # local preview at http://localhost:4321
npm run build    # static output in dist/
```

- Homepage: `src/pages/index.astro`
- Shared head, colors and fonts: `src/layouts/Base.astro`
- Static files served as-is (CV, paper PDFs): `public/`
