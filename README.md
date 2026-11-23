# Speak Easily

English conversation question decks for teenagers (A2–B1).

Twenty topics across four categories — School Life, Online Life, Family and
Feelings, and The World and the Future — 240 original open questions. Each
question carries a "Go deeper" re-frame, two vocabulary items with part of speech,
a plain definition and an example sentence, two "Keep talking" follow-up questions,
three model answers and a creative "Make it memorable" answer.

Dark glass cards, a cover image per topic, and a colour theme cycler. Vocabulary is
taught two ways: tap an in-sentence word, or tap a chip in the "Words to use" row, to
open a tooltip with the word class, meaning and an example. A one-tap UK &#8596; US
button switches every British spelling to American English.

## Run locally

Serve the folder over HTTP (a `file://` open will not load the data):

    python3 -m http.server 8000 --bind 127.0.0.1

Then open http://127.0.0.1:8000/.

## Files

- `index.html` — the app (markup, styles, viewer logic)
- `lesson-data.js` / `lesson-data.json` — the questions
- `mapping-data.json` — cover image per topic

Cover images are free-to-use stock from Pexels.
