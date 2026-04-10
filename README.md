# HNG Stage 0 Todo Card

A responsive, accessible, and testable Todo Card built with HTML, CSS, and JavaScript for the HNG Frontend Stage 0 task.

## Live URL

[Add your deployed link here]

## GitHub Repository

[Add your GitHub repo link here]

## How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/hng-stage0-todo.git
```

2. Open the project folder:

```bash
cd hng-stage0-todo
```

3. Open `index.html` in your browser.

You can either:
- double-click `index.html`
- or right-click and open with your browser

## Decisions Made

- Used plain HTML, CSS, and JavaScript to match the task requirement of no framework.
- Used semantic HTML elements such as `article`, `h2`, `p`, `time`, `ul`, `li`, and `button`.
- Added all required `data-testid` attributes exactly as specified for automated testing.
- Used a real checkbox input for accessibility and keyboard navigation.
- Added a live time-remaining display that updates periodically.
- Styled the card to be responsive across mobile and desktop screen sizes.

## Trade-offs

- Used hardcoded task content instead of dynamic data since the task only requires one testable Todo card.
- Kept the Edit and Delete actions simple with placeholder behavior.
- Used inline CSS and JavaScript in a single file for simplicity and easy review.
- Did not add a full testing setup since tests were listed as optional.

## Features

- Accessible checkbox toggle
- Friendly due-date and time-remaining display
- Responsive layout
- Semantic HTML structure
- Keyboard-focusable controls
- Exact required `data-testid` values
