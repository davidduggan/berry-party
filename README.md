# Berry Party

Berry Party is a 7×7 cluster-based slot game being developed for Stake Engine.

This repository contains the game frontend, mathematical model, assets, documentation, and development tooling.

## Technology Stack

### Frontend

- TypeScript
- Svelte
- PixiJS
- Stake Engine Web SDK where appropriate

### Game Mathematics

- Python
- Stake Engine Math SDK

### Development

- Git
- GitHub
- pnpm

## Required Versions

- Node.js: `22.16.0`
- pnpm: `10.5.0`
- Python: `3.12.10`

These versions are pinned in the repository using:

- `.nvmrc`
- `.python-version`
- `package.json`

## Repository Structure

```text
berry-party/
├── frontend/     # Svelte / TypeScript game frontend
├── math/         # Python game mathematics and simulation
├── assets/       # Shared game assets
├── docs/         # Project documentation
├── scripts/      # Development utilities
├── .github/      # GitHub configuration
└── README.md