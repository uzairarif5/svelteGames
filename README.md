# SvelteGames

A website dedicated for my browser games.

## Updates

Versioning is done using "npm version [new-version] --git-tag-version false".
Minor updates always start with 1.

update 3.2:
- Added code to support spectating functionality for "jumpy Man (Online Multiplayer)".

update 3.1:
- Removed `+server.ts` in the first layout. Websockets are used instead of http requests.

update 2.5 - 2.26:
- Websocket link is now `sveltegames.onrender.com:3000`.
- Added `server.ts`.

update 2.4:
- In `svelte.config.js`, changed `adapter-auto` to `adapter-node`.

update 2.3:
- In "Jumpy Man (Online Multiplayer)", added player 2 functionality.
- Removed `/jumpyManOnline` from websocket path in "Jumpy Man (Online Multiplayer)".

update 2.2:
- In `gameData.ts`, `MultiplayerIndex` was 1. Now it's correctly changed 2.
- When connecting to websockets, `wss` is used instead of `ws`.

update 2.1:
- Added two games "Jumpy Man" and "Jumpy Man (Online Multiplayer)".

update 1.1:
- first commit