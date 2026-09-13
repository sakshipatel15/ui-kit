# Sakshi UI Kit

Accessible **React + TypeScript** UI kit customized and published by **Sakshi Patel**.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
[![GitHub](https://img.shields.io/badge/GitHub-sakshipatel15%2Fui--kit-black)](https://github.com/sakshipatel15/ui-kit)

## What this is
A reusable component library for product UIs — buttons, forms, layout primitives, widgets, and Storybook docs.

Built for:
- Clean TypeScript APIs
- Accessible interaction patterns
- Themeable styling
- Real product UI experimentation

## Stack
- React
- TypeScript
- Emotion
- Storybook
- pnpm + Turbo (monorepo)

## Attribution
This project is based on [SSA UI Kit](https://github.com/ssagroup/ui-kit) (MIT License) by SSA Group.

I customized it for my open-source portfolio:
- Rebranded package metadata and docs under my GitHub
- Added portfolio-facing documentation
- Prepared the repo for public use and learning

See `NOTICE.md` and `LICENSE` for full license + attribution details.

## Author
**Sakshi Patel**  
GitHub: https://github.com/sakshipatel15  
Email: sakshipatel150905@gmail.com

## Getting started (usable demo)

```bash
# one-time setup (install + build required packages)
pnpm setup

# run Storybook UI preview
pnpm --filter ./packages/core sb:dev
```

Then open: **http://localhost:6006/**

### Important
This is a monorepo. You must build `utils` and `hooks` before Storybook works:

```bash
pnpm build:utils
pnpm build:hooks
```

If Storybook was already running, restart it after building.


## License
MIT — original copyright retained for upstream SSA UI Kit; modifications © 2026 Sakshi Patel.
