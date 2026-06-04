# Punctuation Playground

A fun, fully self-contained web app for mastering **SAT-level punctuation**. One `index.html` file, no dependencies, no build step.

## What's inside

- **Study mode** - card-based lessons for the core SAT marks: commas, semicolons, colons, dashes, apostrophes, and end punctuation. Each rule comes with a ✅ right / ❌ wrong example pair and a memorable tip.
- **Practice mode** - relaxed multiple-choice quiz with instant feedback, explanations, and an end-of-quiz review of what you missed.
- **Challenge mode** - timed, gamified rounds with streaks, points, and lives.
- Progress and best scores saved locally in your browser (`localStorage`).

## Run it locally

Just open `index.html` in any browser. That's it.

## Deployment

Pushing to `main` automatically publishes the site to **GitHub Pages** via the workflow in [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml).

🔗 **Live site:** https://mdgibbons2.github.io/PunctuationHelper/

All quiz questions are SAT-style and were machine-generated, then fact-checked by a separate verification pass for grammatical correctness.
