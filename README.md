# Pick A Letter! 🎮
A two-team, host-controlled townhall game. Players join with a game code, choose a team, and collaborate verbally. The host reveals A–Z challenges; every successful challenge is worth 5 points.

## GitHub Pages
Enable Pages from **Settings → Pages → Deploy from branch → main → /(root)**.

## Multiplayer
This version uses Supabase Realtime Broadcast only; it does not create or modify any database tables. It uses the same Supabase project as the existing Unscramble game but a different channel namespace (pick-a-letter-*), so it does not touch the Unscramble game's data.
