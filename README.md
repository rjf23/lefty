# Lefty

An AI-powered interactive portfolio — a conversational way to explore the work, thinking, and background of Ryan Flynn.

## What this is

Most portfolios are static. You scroll, you read, you leave. Lefty is different: it's an interactive surface you can talk to. Instead of reading a résumé, you ask questions and get answers grounded in real context.

It's also a working demonstration of the architecture it's built on — agents, sessions, retrieval, and generative UI — assembled deliberately from specialized, composable tools rather than an all-in-one platform. The goal was to understand how each layer connects, not to hide the connections behind a framework.

## Status

Active development. This is v1 — the foundation. The interactive chat, persistent sessions, and public deployment are being built in stages, in public.

## Tech stack

The stack was chosen to keep each layer specialized and understood, rather than bundled:

- **Next.js 15** — application framework (App Router)
- **TypeScript** — type safety across the codebase
- **Tailwind CSS** — styling
- **Vercel** — hosting and continuous deployment
- **Neon** — Postgres database (chosen over bundled platforms to keep data concerns explicit)
- **Upstash** — Redis for caching and session state
- **Anthropic Claude** — the language model behind the conversation
- **Tavily** — web search for current context

## Getting started

Clone the repository and install dependencies:

```bash
git clone https://github.com/rjf23/lefty.git
cd lefty
npm install
```

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Roadmap

- **v1** — Interactive portfolio: chat interface, grounded knowledge, public URL
- **v2** — Personalization: visitor recognition, adaptive responses
- **v3** — A closed-loop system connecting journaling, résumé, and outreach
- **Beyond** — Platform exploration

## About

Lefty is built by Ryan Flynn, a product leader exploring the intersection of product thinking and hands-on engineering.

Built in public — follow along.