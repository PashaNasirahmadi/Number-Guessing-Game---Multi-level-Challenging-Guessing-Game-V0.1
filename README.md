# Number-Guessing-Game---Multi-level-Challenging-Guessing-Game-V0.1
A Python GUI number guessing game using tkinter, featuring 5 stages with increasing difficulty and dynamic scoring. Each round challenges the player with larger number ranges and fewer points. Clean interface, replay options, and simple logic make it great for both fun and beginner learning.



# 🔢 Guess the Number Game — Python GUI Edition

A simple but progressively challenging number guessing game built with Python. Users must guess a randomly selected number in a given range within limited attempts. Each round increases in difficulty, while the interface remains clean and intuitive thanks to the GUI built with `tkinter`.

---

## 📦 Features

- 🧠 **Multiple Rounds:** 5 rounds with increasing difficulty and decreasing point value.
- 🔁 **Replay System:** Option to continue after each failed round.
- 🎯 **Randomized Ranges:** Each stage expands the range (1–10 → 1–20 → 1–100).
- 🖥 **Graphical Interface:** Clean GUI using `tkinter` for better user experience.
- 🏆 **Scoring System:** Track your score per round and across the game.
- 📉 **Progressive Challenge:** Fewer points and more range as you move forward.

---
| Round | Range    | Attempts | Max Points |
| ----- | -------- | -------- | ---------- |
| 1     | 1 to 10  | 5        | 50         |
| 2     | 1 to 20  | 5        | 25         |
| 3     | 1 to 100 | 6        | 15         |
| 4     | 1 to 100 | 7        | 10         |
| 5     | 1 to 100 | 10       | 5          |

If the player fails all rounds, the final score is 0.

📫 Contact

Created by Pasha Nasirahmadi
GitHub: @PashaNasirahmadi


## 🚀 Getting Started

### 📋 Requirements

- Python 3.7 or later
- `tkinter` (comes pre-installed with standard Python distributions)




### ▶️ Run the Game

Clone this repository and run the script:

```bash
git clone https://github.com/PashaNasirahmadi/guess-the-number-game.git
cd guess-the-number-game
python game.py

