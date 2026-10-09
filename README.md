# REAL.LIFE ? Public Demo Beta

[????](README.zh-CN.md)

[![Download](https://img.shields.io/badge/Download-Windows_Beta-5b8f86?style=for-the-badge)](https://github.com/miasaka-mikoto/real-life-demo/releases/latest)
[![Version](https://img.shields.io/badge/version-0.3.0--beta.1-e0b96b?style=for-the-badge)](https://github.com/miasaka-mikoto/real-life-demo/releases/tag/v0.3.0-beta.1)

A small, dense, modern pixel career-life sandbox RPG. Walk through Maple Quarter, work five mechanically different careers, improve a real home, use vehicles and appliances, build relationships, and save a persistent life.

![REAL.LIFE welcome](media/welcome.png)

## Download

Open the [latest release](https://github.com/miasaka-mikoto/real-life-demo/releases/latest), download the Windows ZIP, extract it, and run `REAL.LIFE.exe`.

The package contains SHA-256 checksums, release metadata, privacy information, known issues, the demo license and player feedback sheets.

## Included

- five careers and fifteen routes;
- persistent compact city and enterable home;
- reality-constrained demo economy;
- functional vehicles, appliances, furniture and career assets;
- place-bound relationships and durable memories;
- day/night, weather, pixel animation and offline procedural audio;
- keyboard/mouse and controller navigation;
- English / Simplified Chinese switching;
- offline save and continue flow.

| Phone | Life Plan |
|---|---|
| ![Phone](media/phone.png) | ![Life Plan](media/life-plan.png) |

## Controls

| Action | Keyboard | Controller |
|---|---|---|
| Move | WASD / arrows | Left stick / D-pad |
| Interact / work / confirm | E / Enter | A |
| Back | Esc | B |
| Phone | F11 | X |
| Life Plan | F3 | Y |
| Settings & language | F4 | Start |
| First-day guide | F1 | Back / Select |

## Open beta status

The technical release gates pass on the validated Windows build:

- Godot 4.7.2 static/import and 33 canonical test entrypoints;
- bilingual rendered captures on NVIDIA GeForce RTX 4060 Ti;
- physical XInput device detection and controller route wiring;
- WASAPI stream, mute and volume-headroom checks;
- Windows x86_64 export plus native headless and visible startup.

Human comfort, fun, long-session balance and audio-mix preference are collected through open-beta feedback, not pre-labelled as PASS. Reproducible P0/P1 reports block promotion to a later stable demo.

## Feedback and bugs

Use [Issues](https://github.com/miasaka-mikoto/real-life-demo/issues) and include:

1. version from `RELEASE_MANIFEST.json`;
2. Windows version, GPU and input device;
3. selected language;
4. fresh or continued save;
5. the first unexpected result;
6. screenshots/video or deterministic reproduction steps.

- **P0:** crash, data loss, cannot start or continue
- **P1:** normal route blocked, major input/UI failure, severe exploit
- **P2:** polish, unclear copy, minor visual/audio issue

## Requirements

Provisional beta target:

- Windows 10/11 64-bit;
- OpenGL 3.3 / Godot Compatibility-capable GPU;
- approximately 500 MB free storage.

Validated environment: Windows 11, NVIDIA GeForce RTX 4060 Ti, OpenGL Compatibility, WASAPI, XInput controller.

## Privacy

Offline by default. No account, ads, telemetry, paid API or LLM service is required. See [Privacy and Offline Behavior](PRIVACY_AND_OFFLINE.md).

## Repository boundary

This public repository contains **downloads, screenshots and feedback tracking only**. The development source repository remains private.

The demo is distributed under [REAL.LIFE Public Demo License](DEMO_LICENSE.txt). Gameplay videos, screenshots, reviews and non-commercial commentary are allowed.
