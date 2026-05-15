# AGENTS.md

## Cursor Cloud specific instructions

This is a Vite + React + TypeScript SPA with no backend, database, or external service dependencies.

### Available scripts (defined in `package.json`)

| Command | Purpose |
|---|---|
| `npm run dev` | Start Vite dev server (default port 5173) |
| `npm run build` | Type-check with `tsc -b` then bundle with Vite |
| `npm run lint` | Run ESLint (flat config in `eslint.config.js`) |
| `npm run preview` | Preview the production build locally |

### Notes

- The dev server starts almost instantly (~150 ms) on `http://localhost:5173`.
- There are no automated test suites configured; validation relies on lint, type-check (via `npm run build`), and manual browser testing.
- No `.env` files or secrets are required.
