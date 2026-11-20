# Speak Easily

English conversation question decks for teenagers (A2–B1).

Twenty topics across four categories — School Life, Online Life, Family and
Feelings, and The World and the Future — 240 original open questions. Each
question carries a "go deeper" re-frame, two vocabulary items with plain
definitions, and short model answers.

Built in the Sliding In visual style: dark glass cards, a cover image per topic,
a UK/US spelling toggle and a colour theme cycler.

## Run locally

Serve the folder over HTTP (a `file://` open will not load the data):

    python3 -m http.server 8000 --bind 127.0.0.1

Then open http://127.0.0.1:8000/.

## Files

- `index.html` — the app (markup, styles, viewer logic)
- `lesson-data.js` / `lesson-data.json` — the questions
- `mapping-data.json` — cover image per topic

Cover images are free-to-use stock from Pexels.
