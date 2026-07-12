# Project Conventions

## Stack
- MERN: MongoDB, Express, React, Node
- TypeScript throughout
- TanStack Query for data fetching (useQuery/useMutation)
- Session-based auth (not JWT)
- react-hook-form for forms
- Shared axios instance with withCredentials

## Conventions
- Commits: Conventional Commits format (feat:, fix:, chore:, docs:)
- Components: functional, hooks-based
- API routes: RESTful, plural nouns
- Error handling: centralized middleware, no silent catches

## Commands
- `npm run dev` — start dev server
- `npm test` — run tests
- `npm run build` — production build