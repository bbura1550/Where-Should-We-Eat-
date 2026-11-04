# AGENTS.md

## Repository layout

- This directory (`Where-Should-We-Eat-`) is the actual git repository (remote: `bbura1550/Where-Should-We-Eat-`). The workspace root `E:\old\where to eat -test` is not a git repo.
- The entire app is the single file `index.html` — HTML, CSS, and JavaScript are inline. There is no package manager, build step, test suite, or CI.

## Working here

- Open `index.html` directly, or serve this directory for a local preview. GitHub Pages serves it as-is from the repo root.
- The editable default restaurant list is `STARTER_RESTAURANTS` near the top of the `<script>` block in `index.html`.
- Saved lists live in `localStorage` under `mbDinnerDecider.restaurants.v1`. After changing `STARTER_RESTAURANTS`, use the Back Room's "Reset starter list" (or clear localStorage) to see the new defaults on an existing device.
- Sounds are generated with the Web Audio API; there are no audio files. Fonts come from Google Fonts with serif fallbacks.
- Keep the app as one self-contained file. When verifying, check both spin triggers, reels stopping left-to-right on the same middle-row winner, Back Room add/edit/delete/favorite/reset/import/export, and phone-width layout.
