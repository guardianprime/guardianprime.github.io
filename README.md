# guardianprime.github.io

Personal developer portfolio for Gordian Okon — backend engineer.
Built with [Astro](https://astro.build) and Tailwind CSS, deployed to
GitHub Pages.

**Live site:** https://guardianprime.github.io

## Structure

```
src/
├── components/     # Nav, Hero, Skills, Projects, Contact, Footer
├── layouts/        # Base HTML layout (meta tags, fonts, JSON-LD)
├── pages/          # Route pages, including /projects/[slug] case studies
└── styles/         # Tailwind theme + design tokens
```

## Commands

| Command         | Action                                      |
| --------------- | -------------------------------------------- |
| `pnpm install`  | Install dependencies                         |
| `pnpm dev`      | Start local dev server at `localhost:4321`   |
| `pnpm build`    | Build the static site to `./dist/`           |
| `pnpm preview`  | Preview the production build locally         |
| `pnpm lint`     | Lint the codebase                            |
