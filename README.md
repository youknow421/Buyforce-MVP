# Project MVP

Monorepo for the Project MVP (Web + Mobile).

Workspaces:
- `mobile` — Expo-managed React Native app (TypeScript)
- `packages/common` — shared logic (cart reducer, types)
- `packages/ui` — shared design tokens and primitives

Getting started:
1. Install [pnpm](https://pnpm.io/): `npm i -g pnpm`
2. From repo root: `pnpm install`
3. Start web dev server: `pnpm --filter project-mvp dev` or `pnpm run dev`
4. Start mobile: `pnpm --filter project-mvp-mobile start`

Notes:
- I scaffolded a minimal Expo app and a `common` package with the cart reducer to share logic.
- Next steps: wire product data into `packages/common`, add navigation and screens, and add CI assist for mobile builds.