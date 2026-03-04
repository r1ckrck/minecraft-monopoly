# Repository Guidelines

## Project Structure & Module Organization

This repository is documentation-first (no application code yet).

- `README.md`: entry point for new contributors and players.
- `docs/`: canonical game specs and rules.
  - `core-terms.md`: naming and terminology.
  - `economy-values.md`: currency, costs, tribute.
  - `board-layout.md`: 32-space board definition.
  - `properties.md`: properties, utilities, and depots.
  - `adventure-cards.md`: fixed deck list and duplicates.
  - `build-guides.md`: visual/build direction.
  - `rules-reference.md`: gameplay flow and edge rules.

Add new gameplay docs under `docs/` and link them from `README.md`.

## Coding Style & Naming Conventions

- Use Markdown headings with clear hierarchy (`#`, `##`, `###`).
- Keep sections short, scannable, and rule-focused.
- Prefer kebab-case file names in `docs/` (example: `rules-reference.md`).
- Use backticks for game terms and values (example: `2 Outposts -> 1 Stronghold`).
- Keep terminology consistent across files (`Claim Tokens (CT)`, `Adventure Cards`, `Tribute`).

## Testing Guidelines

- Check numeric consistency (for example deck duplicate totals).
- Confirm rule consistency across docs (economy, upgrades, cards).

## Commit & Pull Request Guidelines

Git history currently starts with `initial commit`; use short, imperative commit messages.

always push and track to roigin main, no branches.

- Good examples: `docs: update adventure card effects`, `docs: clarify utility tribute rule`.
- Keep each PR focused on one rules area when possible.
- PRs should include:
  - what changed,
  - why it changed,
  - affected files,
  - any rule/value migrations contributors must apply elsewhere.
