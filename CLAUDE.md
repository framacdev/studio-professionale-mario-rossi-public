# studio-professionale-mario-rossi — Tipo Progetto

## AI Runtime
Usa llama-server:8001 (qwen3-coder-30b) per tutto il codice cliente sensibile.
NON usare Claude Code o OpenCode Zen in questa cartella — dati cliente privati.

## Stack
- Next.js 14 App Router + TypeScript strict + Tailwind + shadcn/ui
- WordPress 6.5 headless + WPGraphQL + ACF
- Deploy: Vercel Hobby (frontend) + hosting cliente (WordPress)

## Convenzioni
- Server Components by default — 'use client' solo se necessario
- Custom hooks per tutta la logica stateful
- No useEffect per derived state — usa useMemo o calcola in render
- TypeScript strict — no any, usa unknown + type guard
- Conventional commits obbligatori

## Skills attive
nextjs-app-router, react-patterns, typescript-strict, tailwind-shadcn,
accessibility-wcag-aa, performance-web-vitals, code-review-frontend,
commit-conventional, seo-technical, ui-ux-pro-max

## Vincoli cliente
- Lingua sito: italiano (it-IT)
- GDPR: cookie banner iubenda
- SEO target: [inserire keyword]
- Colori brand: [inserire hex]

## Note didattiche
Aggiungi commento // WHY: a ogni scelta architettuale non ovvia.
Spiega in italiano il ragionamento, non solo cosa fa il codice.
