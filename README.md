# Kolory App

A single-page interpersonal style questionnaire (in Polish), built as one
self-contained `index.html` file — no build step, no backend, no dependencies.

## What it does

- Presents 16 questions, each with 4 boxes of descriptive words.
- For each question, the user ranks the four boxes 4 (most like me) down to
  1 (least like me); the app enforces that each rank is used exactly once
  per question.
- Once all 16 questions are answered, it computes a score for each of four
  style categories — Działanie (D), Ekspresja (E), Harmonia (H), Porządkowanie (P)
  — and renders a bar chart with an interpretation for each score.
- Progress and answers are saved to `localStorage` so a partially completed
  questionnaire survives a page reload. Nothing is sent over the network.

## Running it

Open `index.html` directly in a browser — there is nothing to install or build.

## Note

This README, and the app itself, were generated fully by Claude.
