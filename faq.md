# Dota Cues: FAQ and Roadmap

## FAQ

**Is there a video or a screenshot of it in action?**

Not really, and that is the point. Dota Cues is an audio product. There
is no overlay, no on-screen anything during a match, nothing to watch.
The only screen is a small settings window where every cue is a simple
toggle. The honest way to evaluate it is to install it, play one game,
and listen. One match tells you more than any screenshot could. It takes
under a minute to set up and you can tweak it to your liking as you go.

**What does it actually do?**

It plays a short spoken cue about ten seconds before things like bounty
runes, power runes, lotus, wisdom shrines, creep upgrades, neutral item
tiers, Tormentor, and your buyback. You keep your eyes on the map and
hear what is coming.

**Is it free? Ads? Accounts?**

Free to use, no account needed. It is ad-supported: ads appear only
inside the Dota Cues app window, never as an in-game overlay and never
interrupting the audio cues during a match. An optional subscription
removes ads and unlocks extras. Ads are served through Overwolf's
standard ad system; the app itself does not sell your data.

**Is this allowed by Valve? Can I get banned?**

It reads only Dota's official Game Events API through Overwolf, the same
sanctioned data path stats apps use. No game memory reading, no input
automation, nothing injected into the game. It is the kind of tool Valve
permits.

**Why Overwolf?**

Because it is the only sanctioned way to read Dota's official game
events. The app uses minimal permissions and has no in-game overlay.
Overwolf also handles the ad system that keeps the app free and the
optional subscription that removes ads. If Overwolf is not for you, that
is completely fair.

**Is the voice AI?**

Honest answer: I recorded the lines myself, then used an open-source
voice model to clean them up and make the delivery more consistent and
upbeat than my raw takes. I am being upfront about that rather than
pretending.

**Who made this?**

A Dota player, not a studio. I am not a professional developer. I built
this with AI coding tools because I wanted it to exist for my own games,
and figured other people drowning in the same mid-game cognitive
overload might want it too.

**How do I change which cues I hear?**

Open the settings window. Every cue is individually toggleable and
volume tunable, and the pre-warning lead time is adjustable per cue.
Turn off everything except, say, runes and buyback if that is all you
want. There are test buttons so you can preview each cue without
launching a match.

**Does it work when Dota is not running?**

It just idles quietly until a Dota match starts. Nothing pops up.

**What about other languages?**

The first version is English. I want this in more languages and I have
friends who can help record cues. If there is real demand for yours,
ask, and it moves up the list.

**How do I request a feature or report a bug?**

Tell me. The whole project is feedback driven. If a request is
worthwhile I will build it. Contact details are on the Overwolf listing.

**Is it free? How is it funded?**

The full cue experience is free to play. The app is supported by ads
shown inside the Dota Cues window, which is what keeps it free for
everyone. The ads are never an in-game overlay and never interrupt the
audio cues during a match.

If you would rather not see ads, an optional subscription removes them
and adds two things: extra voice packs and extra languages.

What stays true either way: every cue the app plays is available on the
free, ad-supported tier. The subscription is for removing ads and adding
extras, not for unlocking the core timing cues. No in-game overlay, ever.

## Roadmap

This is a living project. Priorities shift based on what players
actually ask for.

**Shipped (v1.0)**

- 23 voice cues across runes, lotus, shrines, creep upgrades, neutral
  tiers, Tormentor, buyback, and match start
- Per-cue enable, volume, and pre-warning controls
- Last-call announcement toggle for the final bounty and lotus spawns
- Selectable voice pack
- Global hotkeys (open settings, mute master, silence next alert)

**Being considered, demand driven**

- More languages (friends can help record once there is demand)
- Additional and higher-quality voice packs
- A demo mode to preview cues outside a live match
- Roshan, Aegis, and Tormentor respawn timers. These are deferred for a
  real technical reason: Overwolf's game events do not currently expose
  a reliable signal for them. If that changes, they go in.

**Ongoing**

- Updated promptly when a Dota patch changes the timing tables. The app
  shows which patch it is calibrated for in the footer.

**Subscription (planned, optional)**

The app is free and ad-supported. An optional subscription is planned
for players who want to support development and get more:

- No ads
- Extra voice packs
- Extra languages

What will not change: every timing cue stays available on the free,
ad-supported tier, the subscription is for removing ads and adding
voices and languages, and there is never an in-game overlay.

If something you want is not here, that is exactly the kind of message I
want. The roadmap is shaped by feedback, not set in stone.
