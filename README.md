# Young Sheldon Progressive Quiz Adventure

Test your knowledge of the TV series *Young Sheldon* with this fun, browser-based quiz game!

## Overview

This is a season-by-season quiz for fans who have watched all 7 seasons of *Young Sheldon*. Players unlock quizzes one season at a time, track their progress, and try for a perfect score. The whole game lives in a single HTML file (`index.html`). Everything runs in the browser, and there is no server-side component.

It is a sibling of the [Geronimo Stilton Quiz](https://github.com/anshulkhare7/geronimo-quiz) and uses the same game engine.

## Features

*   **7 Season Quizzes:** 10 questions for each season of the show, 70 in total.
*   **Progressive Unlocking:** You need a perfect score on a season to unlock the next one.
*   **Scoring:** +1 for each correct question, -0.5 for each incorrect question, and -0.25 for each unattempted question when the timer runs out.
*   **Timed Quizzes:** Each quiz has a 5-minute timer.
*   **Multiple Correct Answers:** Some questions have more than one right answer. You must pick all of them.
*   **Cheat Codes:** A perfect score reveals a cheat code that unlocks that season later.
*   **Dark Mode:** Use the 🌓 toggle at the top-left.
*   **Saved Progress:** Progress is saved in the browser with `localStorage`.

## How to Play

1.  Open `index.html` in a browser.
2.  Pick an unlocked season and click **Play**. Read the instructions, then click **Start Quiz**.
3.  Tick the answer(s) for every question and click **Submit Answers** before the 5 minutes run out.
4.  Get all 10 right to unlock the next season and reveal its cheat code.
5.  If a season is locked, click **Unlock** and enter its cheat code.

## Seasons Included

1.  Season 1: A Boy Genius in High School
2.  Season 2: A Rival Prodigy
3.  Season 3: Pasadena Dreams
4.  Season 4: Off to College
5.  Season 5: Big Changes for the Coopers
6.  Season 6: Welcome, CeCe!
7.  Season 7: Goodbye, Medford

## Technical Details

*   **Single file:** HTML, CSS and vanilla JavaScript all live in `index.html`, with no frameworks or libraries.
*   **Quiz data:** All questions are stored in the `booksQuizData` array near the top of the `<script>` block. Each entry has `options`, `correctAnswers` (zero-based option indexes) and an `explanation`.
*   **Client-side only:** No server, database or build step is needed. Any static host works.

## Acknowledgements

- Built with the help of AI ([Claude Code](https://claude.com/claude-code)), based on the Geronimo Stilton quiz.
- Questions were written from the episode transcripts of all 141 episodes of *Young Sheldon*. This is an unofficial fan project and is not affiliated with Warner Bros., CBS or Netflix.
