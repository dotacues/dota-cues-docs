# Dota Cues: Privacy Policy

**Last updated: 2026-05-17**

Dota Cues is an audio event timer for Dota 2, distributed as an Overwolf
Native app. This privacy policy explains what data the app does and does
not handle.

## Short version

Dota Cues itself runs no servers, no account system, and no analytics or
telemetry of its own. Your settings and logs stay on your computer. The
app is free and ad-supported, and offers an optional subscription; the
advertising and subscription are operated by Overwolf, and that involves
data handled by Overwolf and its advertising partners under their own
privacy policies (see Third parties below).

## What Dota Cues itself collects

Nothing of its own. The app has no analytics, no telemetry of its own,
no crash-reporting service, no fingerprinting, and no Dota Cues server
or account. It does not build a profile of you.

## Advertising and subscription

The app is free because it is ad-supported. Ads are delivered through
Overwolf's advertising system, shown inside the Dota Cues app window
only (never as an in-game overlay and never interrupting the audio
cues). To serve and measure ads, Overwolf and its advertising partners
process data such as advertising identifiers and usage signals, governed
by Overwolf's privacy policy and its partners' policies, not by Dota
Cues.

An optional subscription removes ads and unlocks extras. If you
subscribe, the purchase and entitlement are processed through Overwolf's
payment and subscription system under Overwolf's terms and privacy
policy. Dota Cues does not see or store your payment details.

## What stays on your computer

The following is processed locally and is not sent anywhere by Dota
Cues itself:

- **Your settings.** Master volume, which cues are enabled or disabled,
  per-cue preferences (pre-warning offset, per-cue volume), voice pack
  and subscription state. Stored via Overwolf's local settings storage
  at `%LOCALAPPDATA%\Overwolf\settings\` or the platform equivalent.

- **Real-time game state.** While Dota 2 is running, the app reads game
  events from Overwolf's Game Events Provider (GEP) API: hero level,
  gold, buyback cost, kill / death / assist counts, the match state
  machine, the in-game clock, and similar fields. Processed in memory
  only; not written to disk by the app.

- **Diagnostic logs.** The app writes its own console output (rule
  evaluations, audio playback, GEP payloads) to local log files at
  `%LOCALAPPDATA%\Overwolf\Log\Apps\Dota Cues\`. Local-only, rotate
  automatically, and you can inspect or delete them at any time.

## Third parties

Dota Cues runs inside the Overwolf platform and relies on Overwolf for
game data, for the advertising that funds the free tier, and for the
optional subscription. Overwolf has its own data practices governed by
its privacy policy at <https://www.overwolf.com/privacy/>. Overwolf's
advertising partners may process advertising data under their own
policies. Your relationship with Overwolf and those partners is separate
from your relationship with Dota Cues.

Voice clip audio files are bundled with the app. No streaming, no CDN,
no per-clip network requests by Dota Cues.

## Children

Dota Cues is intended for players aged 13 and over (the minimum age to
play Dota 2 per Valve's terms). The app does not knowingly handle data
from children under 13.

## Changes to this policy

If data practices change, this page is updated with a new "Last updated"
date and a summary of what changed. Material changes are also reflected
in app release notes.

## Contact

Questions, concerns, or vulnerability reports: open an issue at
<https://github.com/dotacues/dota-cues>.
