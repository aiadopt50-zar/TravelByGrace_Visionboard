# Website Current State

_Last checked: 2026-09-02_

## Website repository
`aiadopt50-zar/travel-by-grace-website`

## Relevant branches

### `main`
Current baseline website. This is the branch to use for the next approved edit.

### `replacement-v2-weekend-experiences`
Newer experimental replacement concept emphasizing Cape Town entertainment weekends, trip-as-a-whole marketing, motion, supplied photography and event content.

This branch is valuable as a design/reference experiment, but it is **not automatically the source for changes to main**.

## Current change-control instruction
The next website update must start from `main` and should be narrow:

1. Replace/update the self-portrait image or portrait treatment using the newly approved portrait.
2. Move the colour system to purple as the dominant brand colour.
3. Introduce a few stronger high-impact accent colours to make the site feel more exciting.
4. Do not import unrelated structural/layout changes from `replacement-v2-weekend-experiences` unless separately approved.
5. Preserve current content and functionality unless a colour/portrait change requires a small supporting adjustment.

## Replacement branch learnings worth retaining
These are references, not automatic requirements for main:
- Cape Town entertainment weekends are a strong conversion theme.
- Sell travel + accommodation ideas + itinerary items as one coordinated trip.
- Motion can create excitement when restrained and mobile-safe.
- Real supplied photographs are preferable to generic imagery.
- Mobile motion should be simpler than desktop motion.
- Events should link to credible official sources and be date-checked regularly.

## Deployment notes
The replacement branch has cPanel preview deployment configuration targeting a preview folder. A future deployment decision should be made separately from design edits.

## Do not confuse these layers
- **Brand layer:** permanent direction stored in this Brain repo.
- **Main website:** current baseline implementation.
- **Replacement branch:** experiment / alternative implementation.

Future AI work must identify which layer it is changing before editing code.
