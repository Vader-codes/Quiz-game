# Quiz Game

A simple multiple-choice quiz game built with vanilla JavaScript, HTML, and CSS.

**Live demo:** [quiz-game-96v.pages.dev](https://quiz-game-96v.pages.dev/)

## Features

- 🎯 Start screen → quiz screen → results screen flow
- ❓ Multiple-choice questions with dynamically rendered answer options
- 📊 Live score tracking and question progress (`Question X of Y`)
- 📈 Visual progress bar as the quiz advances
- 🏁 Final results screen with score summary and a result message
- 🔁 Restart option to retake the quiz

## Tech Stack

- **HTML** — screen structure (start / quiz / results)
- **CSS** — styling and progress bar
- **JavaScript** — screen transitions, question rendering, score logic, state tracking

No frameworks or build tools — runs directly in the browser.

## How to Run Locally

```bash
git clone https://github.com/Vader-codes/Quiz-game.git
cd Quiz-game
```

Open `index.html` in your browser, or serve it locally:

```bash
npx serve .
```

## How It Works

- The app manages three "screens" (start, quiz, result) by toggling an `active` class via JavaScript — no page reloads or routing involved.
- On starting the quiz, questions and answer choices are rendered dynamically into the DOM from a stored question set.
- Selecting an answer updates the score, advances to the next question, and updates the progress bar.
- After the last question, the app switches to the results screen showing the final score and a summary message.
- **Restart** resets state and returns to the start screen.

## Author

**Bipin** — [@Vader-codes](https://github.com/Vader-codes)
