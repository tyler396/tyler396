# Tyler

Founder of [The Startupverse](https://thestartupverse.com). I build the software founders use to raise money, and I run the company that sells it.

## What I've built

**The Startupverse platform** (Next.js, Supabase, Stripe, Vercel)
A fundraising platform for startup founders and the organizations that support them. I designed it, built it, and ship it to production for paying customers.

- **Investor directory:** 6,300+ investor firms and 20,000+ investor profiles, each enriched with thesis, stage, sector, check size and verified contact data.
- **Investor Intelligence:** matches a founder to the investors most likely to fund them, using pgvector embeddings plus LLM-based ranking (Claude and OpenAI).
- **Multi-tenant organization product:** accelerators and economic development orgs run their own founder cohorts on the platform, with data isolated per tenant through Postgres row-level security.
- **Billing and lifecycle:** Stripe subscriptions and one-time purchases, approval gates, and background jobs on Inngest.
- **Ops:** 90+ Postgres migrations, Sentry monitoring, PostHog product analytics.

**Data pipelines**
Agent-driven research pipelines that discover, verify and enrich investor data at scale. One run on November 2, 2026 found 1,200+ investors missing from the directory, verified each one against the evidence, and added 900+ to production.

## How I work on Supabase

Supabase is my production backend: Postgres, Auth, RLS policies, storage and pgvector. I write and apply my own migrations, debug policy and schema drift in production, and design data models that keep customer data isolated without slowing the product down.

## Stack

TypeScript, Next.js, React, Postgres / Supabase, pgvector, Stripe, Inngest, Vercel, Sentry, PostHog, Anthropic and OpenAI APIs.

## Contact

[thestartupverse.com](https://thestartupverse.com) · tyler@thestartupverse.com
