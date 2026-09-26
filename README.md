# CC Study Website

Interactive study website for the **ISC2 CC (Certified in Cybersecurity)** exam.

## What's inside

- **5 domain sections** — concise notes + 25 practice questions each (125 total)
- **Flashcards** — 173 cards with 3D flip animation, shuffle, and domain filters
- **Quiz mode** — instant answer feedback with explanations, score summary
- **Glossary** — 144 terms with live search
- **Case study** — 10-part JavaSip story mapped to security concepts
- **Light/dark mode toggle** (follows device theme) with React Bits-inspired animations

## Run it

Open `index.html` in any browser — it's a single self-contained file, works offline. (The page loads DM Sans / Manrope from Google Fonts when online; without a connection it silently falls back to system fonts.)

Or enable GitHub Pages: Settings → Pages → Deploy from branch → `main` → `/ (root)`.

## Keyboard shortcuts

In flashcards view:

- **← / →** — previous / next card
- **Space** — flip the current card
- **Enter** — flip the card when it has focus

Shortcuts are ignored while typing in a text field (e.g. glossary search), so typing never flips or changes cards by accident.

## Quiz mode

Pick a domain to start a **25-question** session (questions can be shuffled).
Each answer locks in immediately and reveals the correct choice with an
explanation; when the session ends you get a score summary with your
percentage.

## Study progress

A session pill in the sidebar tracks your session live: every flipped flashcard
is counted as studied, and every answered quiz question bumps the question
count. A progress bar shows both together as a share of all 173 cards + 125
questions, so you always know how deep into a session you are.
