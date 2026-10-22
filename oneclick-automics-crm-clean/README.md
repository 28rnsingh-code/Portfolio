# OneClick Automics CRM — Isolated Workspace

This folder contains the independent OneClick Automics CRM preview. It is intentionally separate from the account's other websites and database projects.

## Build and run

```bash
npm install
npm run typecheck
npm run build
npm run dev
```

## Current verification boundary

This repository initially contains a front-end preview only. Lead and task changes are saved to the current browser's local storage. Authentication, API/backend enforcement, durable multi-user database storage, background jobs, AI provider calls, and WhatsApp/email integrations are not implemented and must not be represented as live.

## Deployment

The Vite app can be hosted as a static Vercel project with this folder configured as the Root Directory. Do not bind a custom domain until the owner identifies the unused domain and smoke tests pass.