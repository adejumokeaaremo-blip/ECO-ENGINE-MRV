# ECO ENGINE — Nigeria's Climate-Data Rails

**ECO-ENGINE MRV SYSTEM COMPANY LTD · RC 9666441 · Abuja, Nigeria**

A digital MRV (Measurement, Reporting, Verification) platform for industrial
greenhouse-gas emissions in Nigeria — AI-assisted estimation with
human-in-the-loop verification. Built as a working demonstrator for the
National Council on Climate Change (NCCC).

&gt; The AI accelerates. The human decides.

## What this is

- 15-page demonstrator web application, 4 roles: Facility Operator, Verifier,
  Regulator (NCCC), Inventory Compiler (NIMO)
- Full Stage-1 workflow: facility onboarding → monitoring plan → One Upload
  reporting → AI emissions estimation (IPCC 2006/2019) → human verification →
  DQI scoring → IFRS S2 / GRI 305 disclosure packs → national inventory export
- Tamper-evident hash-chained audit trail
- Seeded with demonstration data (two Nigerian facilities)

**Status:** Demonstrator — demonstration data only, not yet hardened for
production use. See hardening roadmap in the IT Infrastructure document.

## Tech stack

React 19 · TypeScript · Vite · Tailwind CSS · shadcn/ui · Recharts ·
GSAP / Framer Motion

## Run locally

```bash
npm install
npm run dev
