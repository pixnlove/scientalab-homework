# Scienta Lab Homework

Live demo 👉 <https://scientalab-homework.vercel.app/>

This repository contains the homework project for **Scienta Lab**. It is built with Next.js, TypeScript and the Vercel AI SDK, and demonstrates how to combine AI tooling, MCP research tools and custom UI components.

## Getting Started Locally

```bash
# Install dependencies
pnpm install

# Copy env template and add your secrets
cp .env.example .env.local

# Run the development server
pnpm dev

# Open http://localhost:3000
```

## Project Structure

- `app/` – Next .js App Router pages and APIs
- `components/` – React components used throughout the UI
- `lib/` – Utility, database and AI helper functions
- `tests/` – Playwright end-to-end tests

## License

MIT © Scienta Lab
