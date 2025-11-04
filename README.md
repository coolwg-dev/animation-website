# Animation Website (placeholder)

This is a minimal Astro scaffold created as a placeholder for the animation website.

Quick start (Windows PowerShell):

```powershell
cd 'c:\Users\yuman\Documents\GitHub\animation-website'
npm install
npm run dev
```

Open http://localhost:3000 after the dev server starts.

Files added:
- `package.json` — scripts and dependency on Astro
- `astro.config.mjs` — minimal config
- `src/pages/index.astro` — homepage
- `src/layouts/BaseLayout.astro` — simple layout
- `src/pages/404.astro` — 404 page
- `public/favicon.svg` — small favicon

Next steps:
- Replace placeholder content with your animations.
- Add components under `src/components` and styles as needed.

Adding videos
---------------
Place video files in the `public/videos/<category>/` folder (for example `public/videos/fourier_square_wave/`).
Files placed under `public/` are served statically, so a file at `public/videos/fourier_square_wave/example.mp4` will be reachable at `/videos/fourier_square_wave/example.mp4`.

The site includes four default category pages:
- `fourier_square_wave`
- `power_curves`
- `riemann_sum_manim`
- `secant_to_tangent`

Create additional categories by adding a page under `src/pages/` and linking to it from `src/layouts/BaseLayout.astro` or the homepage.
