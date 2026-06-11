# Final — MicroSaaS Template

A reusable template to ship your own GenAI MicroSaaS.

## Folders
- `frontend/` — Next.js (App Router) + Tailwind + shadcn/ui
- `backend/` — FastAPI service with auth, billing hooks, LLM endpoints
- `infra/` — Deployment notes (Vercel for frontend, Render/Fly for backend)
- `docs/` — Product, pricing, onboarding notes

## Suggested stack
- **Frontend:** Next.js + Vercel
- **Auth:** Clerk (Vercel Marketplace)
- **DB:** Neon Postgres (Vercel Marketplace)
- **LLMs:** Vercel AI Gateway (`provider/model` strings)
- **Payments:** Stripe
- **Analytics:** PostHog

## Definition of done
- [ ] Landing page
- [ ] Auth (sign-up / sign-in)
- [ ] Core AI feature working end-to-end
- [ ] Paywall / free trial
- [ ] Basic evals + logging
- [ ] Deployed on a custom domain
