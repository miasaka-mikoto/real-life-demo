# REAL.LIFE Public Demo Beta ? Known Issues

Version: `0.3.0-beta.1`

## Open-beta acceptance

- The first-ten-minute, 60?120-minute and physical-controller sheets are bundled so independent players can report evidence; they are not pre-signed by the developer.
- Physical XInput detection and controller routing pass technically, but controller comfort varies by device and player.
- WASAPI initialization, procedural stream playback, mute and safe volume headroom pass technically; speaker/headphone mix preference remains feedback-driven.

## Localization

- English is complete across the authored demo.
- Simplified Chinese covers the public entry, first-day guide, settings, phone app grid, Life Plan, common HUD/career vocabulary and core release text.
- A small number of deep career-detail descriptions may still fall back to English. Please report the exact screen and text.
- CJK text uses installed system-font fallback. Extremely minimal Windows installations without a Chinese-capable font may render fallback glyphs.

## Product limitations

- One compact district, five careers and a curated life slice are included. This is not the complete long-term sandbox vision.
- Reality data constrains ratios and affordability; it is not city-specific cost-of-living or personal-income advice.
- The game is single-player and offline. Multiplayer is not implemented.
- Pre-release saves may not migrate into a future commercial version.

## Repository / CI limits

- The private source repository cannot enable GitHub branch protection on the current plan.
- GitHub-hosted Actions capacity was unavailable during Stage 3A; exact Stage 3B validation was performed on the authorized physical Windows machine and committed as evidence.

## Reporting a problem

Use the public download repository issue tracker and include:

1. exact version and commit from `RELEASE_MANIFEST.json`;
2. operating system, GPU and input device;
3. selected language;
4. fresh or continued save;
5. the first unexpected result;
6. screenshot, video or deterministic reproduction steps.

Severity:

- **P0:** crash, data loss, cannot start or continue;
- **P1:** normal route blocked, major input/UI failure, severe exploit;
- **P2:** polish, unclear copy, minor visual/audio issue.
