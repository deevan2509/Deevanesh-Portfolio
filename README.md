# Deevanesh Nagarajan — Portfolio

Professional portfolio website for Deevanesh Nagarajan, Software Engineering graduate based in Kulai, Johor, Malaysia.

Built with [Astro](https://astro.build) and [Tailwind CSS](https://tailwindcss.com), deployed on [Vercel](https://vercel.com).

## Sections

- About
- Experience
- Projects
- Technical Skills
- Leadership & Activities
- Education & Certifications
- Contact & References

## Local Development

```bash
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321) in your browser.

## Build

```bash
npm run build
npm run preview
```

## Deploy to Vercel

1. Push this repository to GitHub
2. Import the repo in [Vercel](https://vercel.com/new)
3. Vercel will auto-detect Astro — no extra configuration needed
4. Update `siteMeta.url` in `src/data/portfolio.ts` and `site` in `astro.config.mjs` with your live domain after deployment

## Content Updates

All portfolio content lives in a single file: `src/data/portfolio.ts`. Edit that file to update text across the site.

Profile photo: `public/images/profile.png`
