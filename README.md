# ♟️ Chess AI with Pygame

A fun and simple chess game built with Python and [Pygame](https://www.pygame.org/). You can play against a friend — or test your skills against an AI that thinks ahead using the Negamax algorithm with alpha-beta pruning!

---

## 🧠 What's Inside?

* 🖼️ **Smooth GUI:** Clean and colorful board with clickable pieces.
* 🧍‍♂️🧍‍♂️ **2-Player Mode:** Play locally with a friend.
* 🤖 **AI Opponent:** Play against the computer — challenge it at various difficulty levels!
* ✅ **Full Chess Rules:** Includes legal move checking, castling, en passant, and pawn promotion.
* 🔁 **Undo/Reset:** Press `Z` to undo a move, `R` to reset the board.
* 🎨 **Board Themes & Sounds:** Enjoy multiple board colors and satisfying move sounds!

---

## 🎮 How to Play

### 🧰 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/RUTWIK113/Chess_AI.git
cd Chess_AI
```

2. **Install dependencies:**

```bash
pip install pygame
```

3. **Run the game:**

```bash
python main.py
```

Or use **Visual Studio Code**:

* Open the folder in VS Code
* Open Terminal and run: `python main.py`

---

## 🕹️ Controls

* **Click** a piece to select it. Valid moves are highlighted.
* Click a highlighted square to move.
* **Press `Z`** to undo the last move.
* **Press `R`** to restart the game.

> Tip: When AI is thinking, you can still click its pieces to preview its possible moves.

---

## ♟️ Advanced Rules

### En Passant

A special pawn capture when the opponent's pawn moves two squares forward:

<p align="center">
  <img src="https://github.com/anuragjain-git/chess/assets/98457054/1b92957b-1126-4771-8ffb-e3fe7a77b4ca" width="300"/>
  →
  <img src="https://github.com/anuragjain-git/chess/assets/98457054/bba26e9f-86b2-421b-99b0-a0e7c73a49d9" width="300"/>
  →
  <img src="https://github.com/anuragjain-git/chess/assets/98457054/d77b5e0c-cd11-41e2-86d1-687267586c63" width="300"/>
</p>

### Pawn Promotion

When a pawn reaches the last rank, it can be promoted to a **Queen**, **Rook**, **Bishop**, or **Knight**!

<p align="center">
  <img src="https://github.com/anuragjain-git/chess/assets/98457054/9d33967c-6d19-478c-bb23-8737e4325510" width="300"/>
  →
  <img src="https://github.com/anuragjain-git/chess/assets/98457054/42fc5e0e-f782-4d55-a454-37c13dd39ffa" width="300"/>
</p>

---

## 🛠️ Settings

### 🔁 Human vs Human

Play with a friend by editing `main.py`:

```python
SET_WHITE_AS_BOT = False
SET_BLACK_AS_BOT = False
```

Optional: Flip board in `engine.py`:

```python
self.playerWantsToPlayAsBlack = False
```

### 🤖 Human vs AI

Play as white vs AI (black):

```python
SET_WHITE_AS_BOT = False
SET_BLACK_AS_BOT = True
```

Or vice versa — just flip the booleans.

### 🧮 AI Difficulty (DEPTH)

In `chessAi.py`, change the line:

```python
DEPTH = 3
```

> 🔧 Higher depth = stronger AI but slower response. 3–4 is a good balance.

---

## 🙌 Credits

* Built with ❤️ using [Pygame](https://www.pygame.org/).
* Special thanks to the open-source community and everyone who helped make this project possible!

---

## 🤝 Contribute

Got an idea? Found a bug? Want to add more features?

Feel free to [open an issue](https://github.com/RUTWIK113/Chess_AI/issues) or [submit a pull request](https://github.com/RUTWIK113/Chess_AI/pulls). Contributions are welcome!

---

## ⭐ Final Note

This chess game is perfect for beginners learning Python, AI, or game dev — or for anyone who just wants to play a quick game of chess with a twist!

---

Let me know if you'd like me to format this as a downloadable `README.md` file or generate badges/logos for GitHub!
