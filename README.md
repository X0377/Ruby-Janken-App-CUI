# ✊ Ruby Rock-Paper-Scissors Game (with Acchi Muite Hoi)
A simple command-line game where players compete in Rock-Paper-Scissors and Acchi Muite Hoi. The game continues until a final winner is determined.

## 🚀 Features
- Interactive Rock-Paper-Scissors game with user input.
- Randomized opponent moves.
- Winner of Rock-Paper-Scissors plays Acchi Muite Hoi to decide the final outcome.
- Friendly prompts and emoji-enhanced UI for better user experience.
- Input validation to prevent invalid selections.

## 🛠 Installation & Usage
### **1️⃣ Clone this repository**
```sh
git clone https://github.com/X0377/Ruby-Janken-App-CUI.git
cd Ruby-Janken-App-CUI
```

### **2️⃣ Run the game**
```sh
ruby janken.rb
```

## 🎮 How to Play
1. Choose your move in Rock-Paper-Scissors: `r` (Rock) / `s` (Scissors) / `p` (Paper) / `q` (Quit).
2. If you win, choose a direction for Acchi Muite Hoi: `u` (Up) / `d` (Down) / `l` (Left) / `r` (Right).
3. If you lose, react to the opponent's direction.
4. The game loops until a final winner is determined.

### **📌 Menu Options**
#### Rock-Paper-Scissors
| Option | Action |
|--------|--------|
| `r` | Choose Rock ✊ |
| `s` | Choose Scissors ✌️ |
| `p` | Choose Paper 🖐️ |
| `q` | Quit the game |

#### Acchi Muite Hoi
| Option | Action |
|--------|--------|
| `u` | Look Up 👆 |
| `d` | Look Down 👇 |
| `l` | Look Left 👈 |
| `r` | Look Right 👉 |
| `q` | Quit the game |

## 🏗️ Implementation Details
- Uses **arrays and hash mappings** for move selections.
- Implements **looping game logic** to ensure fair play.
- Provides **emoji-based UI feedback** for an engaging experience.
- Includes **error handling for invalid inputs**.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
