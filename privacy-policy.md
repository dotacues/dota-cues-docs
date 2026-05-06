# Dota Cues — Privacy Policy

**Last updated: 2026-05-06**

Dota Cues is an audio event timer for Dota 2, distributed as an Overwolf
Native app. This privacy policy explains what data the app does and does
not handle.

## Short version

**Dota Cues does not collect, transmit, or share any data about you.**
Everything stays on your computer.

## What we collect

Nothing.

There is no analytics, no telemetry, no crash reporting, no advertising
identifiers, no fingerprinting, no external API calls. The app does not
have a server-side component. There is no account to create.

## What stays on your computer

The following data is processed locally and never leaves your machine:

- **Your settings.** Master volume, which cues are enabled or disabled,
  per-cue preferences (pre-warning offset, per-cue volume), voice pack
  selection. Stored via Overwolf's local settings storage API at
  `%LOCALAPPDATA%\Overwolf\settings\` or equivalent platform location.

- **Real-time game state.** While Dota 2 is running, the app reads game
  events from Overwolf's Game Events Provider (GEP) API — your hero
  level, current gold, buyback cost, kill / death / assist counts, the
  match state machine, the in-game clock, and a handful of similar
  fields. This data is processed in memory only and is not written to
  disk by the app.

- **Diagnostic logs.** The app writes its own console output (rule
  evaluations, audio playback events, GEP payloads) to log files at
  `%LOCALAPPDATA%\Overwolf\Log\Apps\Dota Cues\`. These logs rotate
  automatically. They are local-only and are useful for debugging if
  the app behaves unexpectedly. You can inspect or delete them at any
  time.

## Third parties

Dota Cues does not integrate with any third-party service.

The app runs inside the Overwolf platform. Overwolf has its own data
practices governed by its own privacy policy, available at
<https://www.overwolf.com/privacy/>. Your relationship with Overwolf is
separate from your relationship with Dota Cues.

The app reads voice clip MP3 files bundled with the app itself — no
streaming, no CDN, no per-clip network requests.

## Children

Dota Cues is intended for players aged 13 and over (the minimum age to
play Dota 2 per Valve's terms). The app does not knowingly handle data
from children under 13.

## Changes to this policy

If our data practices change in any way, this page will be updated with
a new "Last updated" date and a summary of what changed. Material
changes will also be reflected in app release notes.

## Contact

Questions, concerns, or vulnerability reports: open an issue at
<https://github.com/dotacues/dota-cues>.
