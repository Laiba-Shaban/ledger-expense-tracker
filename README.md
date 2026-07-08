# ledger-expense-tracker

A personal expense tracker built with vanilla HTML, CSS, and JavaScript — no frameworks, no backend. Add, edit, and track your spending with a live budget overview, category breakdown, and CSV export.

**Live demo:** [add your GitHub Pages link here once deployed]

## Features

- **Add, edit, and delete expenses** — each with a name, amount, and category
- **Monthly budget tracking** — set a budget and see a live progress bar, with a warning if you go over
- **Category breakdown** — visual bars showing how much you've spent per category (Food, Transport, Bills, Other)
- **Sort and filter** — view by category, or sort by newest, oldest, highest, or lowest amount
- **CSV export** — download all your expenses as a spreadsheet file
- **Dark/light mode toggle**
- **Persistent storage** — your data is saved automatically using the browser's `localStorage`, so it's still there when you reopen the page

## Tech Stack

- HTML
- CSS
- JavaScript (vanilla — no frameworks or libraries)

## What I learned

Building this helped me practice:
- Managing application state with plain JavaScript (arrays and objects) instead of a framework
- Working with `localStorage` to persist data across sessions
- Building derived UI (budget progress bar, category breakdown) that updates reactively as data changes
- Generating and downloading a file (CSV export) directly from the browser using the Blob API

## Author

**Laiba Shaban**
