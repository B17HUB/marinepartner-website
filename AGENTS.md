# Marine Partner — marinepartner-website

## Prosjekt
Bedriftsnettside for **Marine Partner AS** (org.nr 916 362 358), Våler i Østfold.
Maritim bransje — reparasjon/vedlikehold skip og båt + grossist maskiner/utstyr.
Kunde av **B17 Studios**.

## Stack
- **Frontend:** Next.js 15 (App Router) + TypeScript + Tailwind CSS
- **CMS:** Sanity (headless, free tier)
- **Hosting:** Vercel (B17 team: team_6ZW7i56Ad5Gasun9W1gKfv30)
- **Booking:** Cal.com embed (planlagt)
- **Domene:** marinepartner1.no (eksisterende)

## Fremtidige integrasjoner
- Finn.no — RSS-feed for båtannonser (ved eventuelt båtsalg)
- Minbot / chatbot (på sikt)

## Struktur
```
src/
  app/           — Next.js App Router pages
  components/    — React-komponenter
  lib/           — Utilities, Sanity-client
  styles/        — Global CSS
sanity/          — Sanity Studio config (legges til senere)
public/          — Statiske assets
```

## Git
- Default branch: main
- Direkte commit/push til main (ingen PR-flyt)
- Aldri commit .env, credentials, eller node_modules/

## Kontakt kunde
- **Daglig leder:** Sten Halvor Skjelbred
- **Telefon:** 900 57 599
- **E-post:** post@marinepartner1.no
- **Adresse:** Granittveien 6D, 1592 Våler i Østfold
