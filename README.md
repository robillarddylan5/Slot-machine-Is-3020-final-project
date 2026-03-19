# 🎰 Python Slot Machine

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-green)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

A fully functional slot machine game built with Python and Tkinter. Features 
animated spinning reels, weighted symbol probability, a live betting system, 
win/loss popups, and a real-time stats tracker — all built using event-driven 
GUI design.

---

## 🎮 How to Play

1. Start with **100 credits**
2. Use the **bet slider** to choose how much to wager (1–20 credits per spin)
3. Click **SPIN** and watch the reels go
4. Match symbols to win credits — the rarer the symbol, the bigger the payout
5. Reach **10,000 credits** to beat the machine, or go bust trying

---

## 📋 Paytable

| Symbol | Points | Rarity |
|---|---|---|
| 🍇 Grape | 5 | Very Common |
| 🍋 Lemon | 8 | Common |
| 🍎 Apple | 12 | Medium |
| 🍍 Pineapple | 20 | Uncommon |
| 🔔 Bell | 40 | Rare |
| 💎 Diamond | 100 | Extremely Rare |

**Payout Rules:**
- 3 of a kind → `bet × points × 3`
- 2 of a kind → `bet × points × 1.5`
- No match → 0 credits

---

## ✨ Features

- **Animated reels** — each reel spins and stops independently with a 
  tick-based animation system using staggered delays
- **Weighted probability** — rarer symbols appear less frequently, 
  keeping the game balanced and realistic
- **Live stats tracker** — tracks rounds played, total credits won, 
  and biggest single win
- **Jackpot popups** — special modal dialogs trigger on rare 3-of-a-kind 
  Bell or Diamond wins
- **Paytable viewer** — in-game popup showing all symbols, point values, 
  and rarity levels
- **Game over & win states** — the game detects when you go bust or hit 
  10,000 credits and prompts a restart

---

## 🛠️ Built With

| Tool | Purpose |
|---|---|
| Python 3 | Core programming language |
| Tkinter | GUI framework |
| random.choices() | Weighted symbol probability |

---

## 🚀 How to Run

1. **Make sure Python 3 is installed**
```bash
   python --version
```

2. **Clone the repository**
```bash
   git clone https://github.com/robillarddylan5/Slot-machine-Is-3020-final-project.git
   cd Slot-machine-Is-3020-final-project
```

3. **Run the game**
```bash
   python slot_machine.py
```

> No additional libraries needed — Tkinter comes bundled with Python 3.

---

## 🧠 What I Learned

This project was built as a final project for IS 3020. Building it gave me 
hands-on experience with:

- Designing and structuring a GUI application using object-oriented programming
- Implementing event-driven logic with Tkinter's `after()` method for animations
- Using weighted random selection to simulate realistic probability distributions
- Managing application state across multiple game events and UI components

---

## 👤 Author

**Dylan Robillard**  
[github.com/robillarddylan5](https://github.com/robillarddylan5)
```

---

Once you've added it, commit with:
```
Add project README with features, paytable, and setup instructions
