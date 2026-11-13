# Rainy Precursor Legacy

Weather mod for **Jak and Daxter: The Precursor Legacy** on OpenGOAL.

## Weather modes

Choose a mode under **Game Options > Rainy Weather**:

- **Endless Rain** — moderate continuous rain.
- **Dynamic Weather** — cycles through clear skies, cloud buildup, rain, storms, and clearing.
- **Endless Storm** — heavy rain and a dark, stormy atmosphere.
- **Dry Storm** — storm sky and fog, with lightning and thunder where supported, but no rainfall.

**Controller shortcuts:** Hold **L3 + R3** and press **Left** for Endless Rain, **Up** for Dynamic Weather, **Right** for Endless Storm, or **Down** for Dry Storm.

**Clear Skies Length** offers 30–60 seconds, 2–5 minutes, or 5–10 minutes before cloud buildup. Dynamic Weather uses a 70% rain probability and a 50% conditional storm probability. Cloud buildup: 30–90 seconds; rain: 60–180 seconds; storm: 60–120 seconds; clearing: 30–60 seconds. Transitions add time.

## Sentinel Beach fog

The **Beach Fog** option provides:

- **Permanent** (default) — retains the existing persistent, heavier fog presentation.
- **Dynamic** — adjusts fog density to changing weather conditions while preserving the beach's color palette.

This setting is independent of the selected weather mode and persists between sessions. Existing v1.2.0 weather preferences remain supported.

## Regions and compatibility

Geyser Rock, Sandover Village, Sentinel Beach, Forbidden Jungle, Misty Island, and Rock Village share the weather timeline. Rock Village retains its original lightning/thunder behavior and weather-aware fog. Boggy Swamp retains its native weather; Lost Precursor City remains excluded. Geyser Rock has limited storm effects, and Forbidden Jungle's temple retains time without outdoor rain. Some indoor rain particles may still appear at particular spots or camera angles.

Rainy Weather menu strings are supplied for the game's **23 configured language slots**, including 21 additional non-English locales. Not every translation has undergone native-speaker review or full in-game glyph/layout verification; corrections are welcome.

## Installation

**Windows source-and-tools release:** Extract the archive into a **new** directory. Run `extractor.exe` with your own legitimately obtained Jak 1 game image; then launch `gk.exe`. The release does **not** include copyrighted original game data, saves, or your configuration files. Preserve an existing working installation rather than overwriting it.

This community mod is not affiliated with Naughty Dog or the OpenGOAL team.
