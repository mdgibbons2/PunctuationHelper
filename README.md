# Punctuation Playground

A fun, fully self-contained web app for mastering **SAT-level punctuation**. One `index.html` file, no dependencies, no build step.

## What's inside

- **Study mode** - card-based lessons for the core SAT marks: commas, semicolons, colons, dashes, apostrophes, and end punctuation. Each rule comes with a ✅ right / ❌ wrong example pair and a memorable tip.
- **Practice mode** - relaxed multiple-choice quiz (10 per round) with instant feedback, explanations, and an end-of-quiz review of what you missed.
- **Challenge mode** - timed, gamified rounds with streaks, points, and lives.
- Progress and best scores saved locally in your browser (`localStorage`).

### Question bank

**SET 1** is a pool of **100 authentic Digital SAT-format questions**. Each presents an academic sentence with one blank, the standard stem *"Which choice completes the text so that it conforms to the conventions of standard English?"*, and four full-text A-D choices that vary the punctuation (semicolon vs. colon vs. comma vs. period vs. dash, Oxford commas, appositives, possessives, and more). Every question includes an explanation of why the correct answer is right and why each distractor is wrong. More sets (SET 2, SET 3, ...) can be added to the same bank later.

## Run it locally

Just open `index.html` in any browser. That's it.

## Deployment

Pushing to `main` automatically publishes the site to **GitHub Pages** via the workflow in [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml).

🔗 **Live site:** https://mdgibbons2.github.io/PunctuationHelper/

All quiz questions are SAT-style and were machine-generated, then fact-checked by a separate adversarial verification pass for grammatical correctness.
