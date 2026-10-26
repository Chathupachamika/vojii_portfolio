# Voji Pathirana Portfolio

A premium, responsive portfolio for competitive chess player, coach, and Physical Science undergraduate Voji Pathirana.

## Development

```bash
pnpm install
pnpm dev
```

Open `http://localhost:3000`.

## Production

```bash
pnpm build
pnpm start
```

The project is a Next.js App Router site and is ready to deploy to Vercel. The supplied CV is available at `public/documents/Voji-Pathirana-CV.pdf` and is linked from the navigation and contact area.

## EmailJS

The contact form currently provides client-side validation and a graceful success state. To connect EmailJS, add the EmailJS browser SDK and wire the submit handler in `app/page.tsx` using project environment variables for the public service/template identifiers. Never place private secrets in client-side code.

## Assets

The supplied portrait is rendered from the provided public source URL. Replace the `portrait` constant in `app/page.tsx` with the owner’s approved image URL when needed. Gallery tiles are intentionally limited to the supplied portrait; add only authentic tournament, university, coaching, or award photographs when available.
