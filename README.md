```markdown
# 🎮 Rock Paper Scissors: The Code Clash

Welcome to the ultimate showdown of logic vs luck: the **Rock Paper Scissors** console game, where you—the human—challenge the relentless randomness of the computer!

No front-end distractions. No animations. Just raw JavaScript logic, user input, and score tracking.

---

## 🛠️ Project Summary

This project is a JavaScript-only, text-based implementation of the classic Rock Paper Scissors game. The player faces the computer in a 3-round match, where each round decides a winner based on choice logic.

The objective is simple:
- First to win **2 out of 3** rounds is crowned the **Game Master**.

---

## 🧠 How It Works

### 1. `getComputerChoice()`

Generates a random move:  
- `"rock"`, `"paper"`, or `"scissors"`

### 2. `getHumanChoice()`

Prompts the player using the `prompt()` method.  
Ensures the input is valid and case-insensitive.

### 3. `humanScore` & `computerScore`

Global variables initialized at `0` to track player wins.

### 4. `playRound(humanChoice, computerChoice)`

- Compares player and computer input.
- Handles ties.
- Increments score of the round winner.
- Returns the result as a string:
  - `"It's a tie!"`
  - `"You win! [player choice] beats [computer choice]"`
  - `"You lose! [computer choice] beats [player choice]"`

### 5. `playGame()`

- Loops through 3 rounds.
- Calls `playRound()` each time.
- Declares a final winner after 3 rounds based on total score.

---

## ✅ Example Output (Console)

``

Round 1:
You chose: Rock
Computer chose: Scissors
You win! rock beats scissors

Round 2:
You chose: Paper
Computer chose: Scissors
You lose! scissors beats paper

Round 3:
You chose: Scissors
Computer chose: Paper
You win! scissors beats paper

🎉 You win the game!

``

---

## 🔍 Key Features

- 🧠 Case-insensitive user input
- ⚔️ Best-of-3 battle format
- 📈 Score tracking
- 💬 Dynamic round-by-round commentary

---

## 💡 Dev Tips

- Use browser console or browser-based JS environments (like JSFiddle or CodePen) to test.
- Comment out `prompt()` and replace with hardcoded values for easier testing/debugging.
- Expand this game by adding UI or even multiplayer!

---

## 📁 File Structure

``

rock-paper-scissors/
│
├── script.js      # Game logic
└── README.md      # You’re reading it!

``

---

## 🤖 Built With

- JavaScript (Vanilla)
- No frameworks
- No libraries
- 100% logic

---

## 🧪 Future Features (Stretch Goals)

- Best-of-5 or infinite game mode
- Custom names & scoreboard
- Browser UI with animations
- Sound effects for wins/losses
- AI difficulty modes

---

## 🚀 Run It Yourself

1. Open `script.js` in a browser environment.
2. Paste into the dev console or run in a JS sandbox.
3. Play the game through prompts.
4. Watch the score climb—or fall.

---

Happy coding—and may the odds ever be in your logic.

— *The Code Clash Team*
```
