# Track Demo Docs

Documentation powered by [Thally](https://github.com/thallylabs/thally).

## Local development

```bash
npm install
npm run dev
```

The server starts at [http://localhost:3040](http://localhost:3040), or the next
available port when 3040 is already in use.

## Write your docs

- Add MDX pages in `src/content/`.
- Organize navigation and product features in `docs.json`.
- Update the site name, links, and brand defaults in `src/data/site.ts`.
- Copy `.env.example` to `.env.local` for local secrets.

The starter includes a home hero, icon-grouped navigation, English and Spanish
examples, a guided quickstart, component showcase, changelog, OpenAPI reference,
and `AGENTS.md` writing instructions for coding agents.

## Publishing changes

Push changes to the default branch to trigger your connected deployment. If the
site is not connected yet, add the repository in
[Thally Cloud](https://app.thally.io) or deploy it to any Next.js host.

Run `npx create-thally-docs check --ci .` before publishing. Deploy the site
anywhere Next.js is supported, or connect the repository to
[Thally Cloud](https://app.thally.io) for managed hosting and services.
