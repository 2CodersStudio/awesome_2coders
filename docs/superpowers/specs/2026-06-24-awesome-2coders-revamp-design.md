# Awesome 2Coders — Revamp Design

**Date:** 2026-06-24
**Author:** Dailos Medina (with Claude Code)
**Status:** Approved direction, content-first revamp

## Goal

Revamp the `Awesome 2Coders` curated resource list (currently a single `README.md`
with ~30 links) into a substantially expanded, modernized, and opinionated list that
mirrors the tools and stack 2Coders Studio actually uses across its departments —
while remaining a credible, public-friendly "awesome list."

## Decisions

- **Format:** Single `README.md`. No website, no build step, no CI in this pass.
- **Voice:** Opinionated — surface what 2Coders standardizes on, alongside neutral great resources.
- **Structure:** Hybrid — cross-cutting sections first (apply to everyone), then by discipline, then utilities.
- **Stack marker:** A `🔹` marker flags tools/tech that are part of the 2Coders stack.
  A short legend near the top explains it. Approved for public visibility (standard
  industry tooling, not sensitive).
- **New section:** Add **QA & Testing** (the studio has a QA team; the old list had none).

## Structure

**Cross-cutting (everyone):**
- AI & Developer Productivity
- Editors & IDEs
- Source Control & Collaboration
- Project Management & Docs
- Design & UI (incl. inspiration)

**By discipline:**
- Web Frontend
- Backend
- WordPress
- iOS
- Android
- QA & Testing  *(new)*
- DevOps & Ops

**Utilities:**
- Image Placeholders & Assets
- Learning & Inspiration
- Contributing (updated to git-flow + Conventional Commits)
- License

## Constraints / Guardrails

- Quality over quantity — only credible, well-known resources.
- One concise descriptive line per entry.
- Real, working URLs only.
- No client names, no confidential/internal business info.
- `🔹` only on genuine stack tools, not aspirationally.

## Preserved

- Awesome badge, Table of Contents, MIT license reference.
- Friendly contributing tone, "Made with ❤️ by 2Coders" footer, ⭐ call-to-action.

## Out of scope (future passes)

- Link-checking CI / awesome-lint compliance.
- Contribution templates (PR/issue).
- Converting to a searchable website.
