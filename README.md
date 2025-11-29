# Rock Paper Scissors

Simple browser Rock-Paper-Scissors game.

## Files
- [index.html](index.html) — main HTML UI
- [style.css](style.css) — styles for layout and visuals
- [app.js](app.js) — game logic and DOM interactions
- [images/](images/) — image assets (rock, paper, scissors)

## How to run
1. Open [index.html](index.html) in a web browser (double-click or serve the folder).
2. Click any of the three circular choices (rock, paper, scissors) to play.

## Gameplay
- Click a choice to play against the computer.
- Scores update at the top (`#user-score`, `#comp-score`) and a message is shown in `#msg`.

## Code overview
- Computer choice generator: [`genCompChoice`](app.js)
- Draw handler: [`drawGame`](app.js)
- Win/Lose display and scoring: [`showWinner`](app.js)
- Main game flow: [`playGame`](app.js)
- Choice click handling: event listeners on `.choice` elements (defined in [index.html](index.html) and wired in [app.js](app.js))

## Styling
Layout and visuals are in [style.css](style.css). Choices are circular images inside `.choice` and `.choices` centers them.

## Notes
- No build step required — plain HTML/CSS/JS.
- To reset scores, refresh the page.

## License
MIT
