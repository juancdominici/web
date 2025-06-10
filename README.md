# Bug Tracker Monorepo

This monorepo contains a bug tracking application with the following structure:

- `apps/bug-tracker/ui/`: SvelteKit frontend
- `apps/bug-tracker/server/`: Go Lambda backend (Serverless Framework)
- `packages/shared/`: Shared code (types, utils, etc.)

## Getting Started

- Frontend: SvelteKit app in `apps/bug-tracker/ui/`
- Backend: Go Lambda in `apps/bug-tracker/server/`
- Shared code: Place common code in `packages/shared/` 