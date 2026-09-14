# Tariq Kanaan, PhD — Professional Portfolio

A responsive, dark-mode academic and engineering portfolio for Eng. Tariq Kanaan. It presents applied electronics, AI, telecommunications, research, teaching, project work, and academic service in a maintainable React application.

## Stack
React, Vite, TypeScript, Tailwind CSS, Framer Motion, and Lucide React.

## Install and run
```bash
npm install
npm run dev
```

## Production build
```bash
npm run build
npm run preview
```

## Deployment
Deploy the generated `dist/` directory to Netlify, Vercel, GitHub Pages, or any static hosting platform. Set the canonical URL in `index.html` before launch.

## Content and assets
- Update personal profile information and verified professional URLs in `src/data/profile.ts`.
- Update publication titles, venues, and status in `src/data/publications.ts`.
- Update selected work in `src/data/projects.ts`.
- Add a profile photo in `public/images/` and replace the Hero placeholder.
- Add certificate scans in `public/certificates/`; extend `src/data/certificates.ts` with their verified metadata.
- Add project imagery in `public/projects/`.
- Add the actual downloadable CV as `public/Tariq-Kanaan-CV.pdf`. The project deliberately does not include a placeholder PDF.

The contact form is intentionally frontend-only. Configure Formspree, Netlify Forms, or a dedicated backend before accepting submissions.
