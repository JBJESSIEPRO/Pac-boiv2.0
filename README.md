🎮 **[Play Now →](https://jbjessiepro.github.io/Pac-boiv2.0/)**

---

## About

Pac-Boi is a browser-based arcade game built entirely from scratch using vanilla HTML, CSS, and JavaScript — no game engines, no frameworks, no tutorials. Just code.

The game features original mechanics inspired by classic arcade gameplay, with a custom twist: collect dots, freeze enemies, and survive as long as you can.

---

## Features

- 🎮 **Dual input support** — fully playable on both mobile (touch D-pad) and desktop (keyboard arrows)
- 🤖 **Adaptive enemy AI** — enemies evolve in behavior and intelligence as your score increases
- 🏆 **Leaderboard** — tracks and displays top scores across sessions
- 🎨 **Character customization** — personalize your player before you play
- ⏸️ **Pause/resume** — pause mid-game without losing progress
- ⏱️ **Score & timer tracking** — live score and time displayed during gameplay
- 📱 **Mobile responsive** — designed to work on any screen size
- 🚀 **Deployed live** — hosted on GitHub Pages, no installation needed

---

## Difficulty Progression

One of the core design challenges of Pac-Boi is a score-based difficulty system where the game actively evolves the longer you survive. Each threshold introduces a new mechanic that changes how you have to play.

| Score | Event |
|---|---|
| 0 | Single enemy chases the player around the arena |
| 200 | Second enemy spawns — managing multiple threats begins |
| 400 | Enemies receive a speed boost — reaction time becomes critical |
| 600 | Player unlocks freeze ability — collecting the pellet freezes all enemies for 5 seconds |
| 800 | **Enemies activate cooperative AI** — they communicate to coordinate trapping the player or guarding the pellet |
| 1000 | Third enemy spawns — the arena becomes increasingly difficult to survive |

### The Cooperative AI (800 points)
The most complex feature in the game. At 800 points, enemies stop acting independently and begin working as a team — one enemy moves to guard the pellet while another herds the player toward it. This required writing logic where each enemy is aware of the other's position and adjusts its own behavior accordingly. The result is a difficulty spike that feels genuinely intelligent rather than just faster.

---

## Built With

| Technology | Purpose |
|---|---|
| HTML5 | Game structure & canvas layout |
| CSS3 | Styling, animations, responsive design |
| JavaScript (Vanilla) | Game logic, input handling, state management |
| GitHub Pages | Free live deployment |

---

## How to Play

1. Visit the [live game](https://jbjessiepro.github.io/Pac-boiv2.0/)
2. Hit **Customize** to change the colors (optional)
3. Hit **Play** to start
4. **Mobile:** Use the on-screen D-pad to move
5. **Desktop:** Use arrow keys to move
6. Collect dots, avoid or freeze enemies, survive as long as possible
7. Check the **Leaderboard** to see top scores

---

## What I Learned Building This

- Managing game state in vanilla JavaScript without a framework
- Handling multiple input types (touch events vs keyboard events) with a single unified control system
- Designing and implementing a score-based progressive difficulty system
- Writing cooperative enemy AI where multiple entities share awareness and coordinate behavior
- Using AI tools effectively — providing targeted code context to solve specific problems, then integrating the solution into an existing codebase
- Building a responsive layout that works across mobile and desktop
- Deploying a project live using GitHub Pages
- Designing a complete user experience — from the menu screen to gameplay to leaderboard

---

## Developer

**Jessie Jennings** — Self-taught developer & designer.

- 🌐 Portfolio: [jbjessiepro.github.io](https://jbjessiepro.github.io/Portfolio)
- 📧 Email: jbjessiepro@gmail.com
- 🐙 GitHub: [@JBJESSIEPRO](https://github.com/JBJESSIEPRO)

---

*Built from scratch. No engine. No framework. Just code.*
