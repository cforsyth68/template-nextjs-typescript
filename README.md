# Example Next.js TypeScript Setup

## Whats Added?

- ESLint
- Prettier
- Husky (pre-commit hooks)
- Lint Staged

# Before your first commit

## Initialize Husky locally

```bash
yarn husky install
```

This package will enable pre-commit checks that is already configured to run lint-staged package which only lints items you have 'added' to git (staged).

To add all files updated to the staged area:

```bash
git add .
```

## First, run the development server:

```bash
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

Shut it down with CTRL/CMD+C
