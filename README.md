# TFT Meta Helper

A free companion app for **Teamfight Tactics**, built on Overwolf. *Status: in development.*

Website: see `index.html` (served with GitHub Pages).

## Features
- **Meta comps:** a list of current team compositions with units, items and positioning, aggregated from public high-elo ranked matches. The player browses several comps and picks one.
- **In-game overlay:** shows only the comp the player selected before the match, which of its units the player already owns (board and bench), and highlights units of that comp when they appear in the player's own shop.

## Data
- Meta statistics come from a backend that uses the Riot Games API (TFT-LEAGUE-V1, TFT-SUMMONER-V1, ACCOUNT-V1, TFT-MATCH-V1). Only aggregated, anonymous data is published. The API key never leaves the server.
- In-game state comes from the Overwolf Game Events API.

## What it does NOT do
- It does not track or show opponents' boards, plays or stats.
- It does not show lobby or player aggregate stats or augment win rates.
- It does not give real-time "do this now" instructions or automate any input.
- It has no ads in the game client.

## Legal
TFT Meta Helper isn't endorsed by Riot Games and doesn't reflect the views or opinions of Riot Games or anyone officially involved in producing or managing Riot Games properties. Riot Games, and all associated properties are trademarks or registered trademarks of Riot Games, Inc.
