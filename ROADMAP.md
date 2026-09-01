# Roadmap — wonderlens-assets

## Status
Current phase: Phase 3 — Make the repository usable
Last updated: 2026-09-01

This is a brand asset repository, not a software project — 15 image files and a one-line README,
added across four commits in March 2026. It holds the identity for the WonderLens app
(`Tjosans/WonderLens`).

The phases below track asset coverage rather than code. Phases 1 and 2 are complete: the marks
and the category icon set both exist. Phase 3 is about the repository itself, which is currently
a bare file drop with no README content, no licence and no usage guidance.

## Phase 1 — Core brand marks
- [x] App icon (`wonderlens_app_icon.svg`)
- [x] Primary mark in violet (`wonderlens_mark_violet.svg`)
- [x] Primary mark in white (`wonderlens_mark_white.svg`)
- [x] Horizontal lockup (`wonderlens_lockup_horizontal.svg`)
- [x] Stacked lockup (`wonderlens_lockup_stacked.svg`)
- [x] 400px raster export of the white mark (`wonderlens_mark_white_400px.png` and `.svg`)

## Phase 2 — Category icon set
- [x] Animals
- [x] Body
- [x] Food
- [x] Machines
- [x] Nature
- [x] Space
- [x] Tech
- [x] Weather

## Phase 3 — Make the repository usable
- [ ] Write a real README — it currently contains only the title `# wonderlens-assets`, with no inventory, no usage rules and no indication of which mark to use where
- [ ] Add SVG sources for the eight category icons — the marks ship as SVG but the category icons are PNG only, so they cannot be recoloured or scaled cleanly
- [ ] Document the intended size and clear-space rules for each asset
- [ ] Add a licence or usage statement, so it is clear whether these may be used outside the WonderLens project
- [ ] Decide whether this stays a separate repository or moves into `Tjosans/WonderLens` — nothing currently links the two, and the app does not reference this repo

## Phase 4 — Coverage gaps
- [ ] Decide whether a dark-background variant of the violet mark is needed (only white and violet exist today)
- [ ] Decide whether the category icon set needs to grow — the eight here match the app's current subject categories, so adding a category means adding an icon
- [ ] Produce favicon and platform app-icon sizes if the app ever needs them, rather than rescaling by hand

## Blocked

## Decisions
- 2026-03-20: chose to keep brand assets in their own repository rather than inside the WonderLens app repo, which keeps the app's tree clean at the cost of nothing linking the two
- 2026-03-20: chose SVG as the source format for the marks and lockups so they scale and recolour without re-export, with a single 400px PNG for contexts that cannot take vectors
- 2026-03-25: chose one icon per app subject category (animals, body, food, machines, nature, space, tech, weather), tying the icon set directly to the app's content taxonomy
