# hermes-core

A learning surface for **[Hermes Agent](https://github.com/NousResearch/hermes-agent)** (NousResearch) — community-built, MIT, deployed to GitHub Pages.

Sibling project of [claude-core](https://github.com/cfpperche/claude-core) (same Astro + Tailwind + bun stack, same poster/cheatsheet sensibility, different brand identity).

## Surfaces

1. **Cheatsheet** — every `hermes` CLI command, global flags, slash commands, 15 hook events, memory limits, paths, env vars. One-page dense reference.
2. **Master Class** — the mental model: session flow, `SOUL.md` / `MEMORY.md` / `USER.md`, hooks lifecycle, peers (Honcho), profiles.
3. **Foundation Release** — v0.14.0 (May 16, 2026) capability digest: PyPI install, lazy-install debloat, xAI Grok 1M, OpenAI-compatible proxy, Microsoft Teams stack, LSP semantic diagnostics per write.

Built against Hermes Agent **v0.14.0** (`v2026.5.16`).

## Stack

- [Astro 5](https://astro.build/) static site, no SSR
- [Tailwind 4](https://tailwindcss.com/) via `@tailwindcss/vite`
- [bun](https://bun.sh/) as package manager + runtime
- Deploys via [withastro/action@v3](https://github.com/withastro/action) to GitHub Pages
- Single locale (EN) — Portuguese / Spanish translations possible later

## Run locally

```bash
bun install
bun run dev      # http://localhost:4321/hermes-core/
bun run build
bun run preview
```

## Brand

The visual identity tracks NousResearch / Hermes Agent: dark navy backgrounds (`#0d0d1a`), cornsilk text (`#FFF8DC`), gold / amber / bronze accents (`#FFD700` / `#FFBF00` / `#CD7F32`), Playfair Display for headings, JetBrains Mono for code. Caduceus (`☤`) as recurring motif. All color tokens are sourced from Hermes's own `hermes_cli/banner.py`.

## License

MIT. This is a community/fan project — Hermes Agent itself, the NousResearch trademark, and all assets at nousresearch.com belong to NousResearch.
