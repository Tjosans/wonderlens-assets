# CLAUDE.md — wonderlens-assets

## What this is

A brand asset repository for the WonderLens app (`Tjosans/WonderLens`). Fifteen image files and
a README. There is no code, no build step, no dependencies and nothing to run.

If you are looking for the app itself, it is in `Tjosans/WonderLens` — a Next.js visual answer
engine for children aged 4–12. This repo only holds its identity assets.

See [`ROADMAP.md`](ROADMAP.md) for asset coverage and what is missing.

## Inventory

**Marks and lockups** — all SVG:

- `wonderlens_app_icon.svg`
- `wonderlens_mark_violet.svg`
- `wonderlens_mark_white.svg`
- `wonderlens_lockup_horizontal.svg`
- `wonderlens_lockup_stacked.svg`
- `wonderlens_mark_white_400px.svg` plus a `.png` raster of the same

**Category icons** — all PNG, one per app subject category:

`animals`, `body`, `food`, `machines`, `nature`, `space`, `tech`, `weather`

These eight map directly onto the WonderLens content taxonomy. Adding a subject category to the
app means adding an icon here.

## The two things to know before using these

**The category icons are PNG only.** The marks are SVG and scale and recolour freely; the eight
category icons do not. There are no vector sources in the repo, so they cannot be resized
cleanly or restyled for dark mode. If you need either, the source files have to come from
wherever they were originally drawn — they are not here.

**Nothing links this repo to the app.** WonderLens does not reference it, and there is no
submodule, package or copy step. Assets get moved by hand. If you update an asset here, nothing
downstream notices.

## Conventions

Filenames are `wonderlens_<type>_<variant>.<ext>`, lowercase with underscores. Keep that pattern
— it is the only structure the repo has.

Commits so far are GitHub web uploads ("Add files via upload"). That is fine for a file drop,
but it means there is no history explaining why an asset changed.

## What to pick up next

`ROADMAP.md` Phase 3 — the repository is currently unusable by anyone who did not create it. The
README is a single line, there is no licence, and there is no guidance on which mark to use
where or how much clear space it needs. The most valuable single item is SVG sources for the
category icons, since that is a gap nothing else can work around.
