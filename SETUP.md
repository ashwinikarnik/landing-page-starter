# Setup Guide

This guide helps you initialize and run the project locally.

## 1. Prerequisites

- Git
- Node.js (LTS recommended)
- Nuxt 3, TypeScript
- Package manager: Yarn

> Update this section with exact version requirements once finalized.

## 2. Clone Repository

```bash
git clone <repo-url>
cd loan-estimator-lp-test
```

## 3. Install Dependencies

```bash
yarn install
```

## 4. Configure Environment

1. Copy local environment template.
2. Populate required values.

Example (if using `.env` files):

```bash
cp .env.example .env.local
```

See [ENVIRONMENT.md](./ENVIRONMENT.md) for required keys.

## 5. Run Development Server

TBD (framework-specific):

```bash
yarn dev
```

## 6. Build for Production

```bash
yarn build
```

## 7. Run Tests

```bash
yarn test
```

## Troubleshooting

- If install fails, verify Node.js version compatibility.
- If env validation fails, confirm all required keys are set.
- If port conflicts occur, change app port in local config.
