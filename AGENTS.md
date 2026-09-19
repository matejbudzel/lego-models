# AGENTS.md

## Repository purpose

This repository contains LEGO/LDraw model experiments. Models should remain editable in BrickLink Studio or other LDraw-compatible tools.

## General rules

- Keep model-specific files inside their own folder.
- Prefer plain-text LDraw (`.ldr` / `.mpd`) for generated or agent-edited models.
- Do not replace a working model with a radically different design without preserving the previous version.
- Name meaningful iterations explicitly (for example `v1`, `v2`, `v3`) until a design stabilizes.
- Keep LDraw headers and short section comments readable.
- Prefer real LEGO part IDs and legal connection geometry.
- When optimizing a draft, use larger bricks (1×2, 1×3, 1×4, etc.) where they preserve the intended geometry and improve the construction.
- Avoid introducing unavailable/custom parts unless the model specifically calls for them.
- Comments in generated code/scripts must be in English.

## kockaren

The `kockaren` model is a brick-built wordmark spelling **KOCKÁREŇ**.

Design intent:

- Each letter has one dominant color.
- The word must remain immediately readable from the front.
- Prefer a LEGO-constructed/sculptural look over a strict pixel font.
- K, R, A, and N should eventually use convincing diagonals or stepped structural approximations rather than looking accidental.
- The acute accent over Á and caron over Ň should be visually separated from the letter body.
- Preserve the color sequence: red, yellow, blue, green, red, blue, yellow, green.
- Early drafts use `3005.dat` (1×1 brick) as a safe baseline; later iterations may consolidate pieces.
- Before changing geometry substantially, keep the previous `.ldr` version intact and create a new version.
