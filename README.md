# Mines Demo 3 – First Tkinter GUI Version

This is **Demo 3** in the progression toward **Mines Strategy Simulator**.

Demo 3 is the first version that moves the project from a console prototype into a **graphical user interface (GUI)** using **Python + Tkinter**, with interactive buttons, betting, cash-out, and a mine-count slider.

---

## Disclaimer

**Educational / simulation only.**
- No real money  
- No gambling  
- No monetization  
- Built for learning, demonstration, and portfolio purposes

---

## Purpose of This Demo

The main goal of Demo 3 was to learn and demonstrate:
- Building a full GUI with Tkinter
- Event-driven logic (button clicks instead of input prompts)
- Game-state management across rounds (bet placed, board revealed, resets)
- Visual feedback for safe tiles, mines, multiplier, and balance

This demo is the bridge between the earlier console versions and the final strategy simulator.

---

## Key Features

- **5×5 grid** of clickable tiles
- **Random mine placement** each round
- **Bet system** with input validation
- **Multiplier updates** based on safe reveals
- **Cash Out** button to lock in winnings
- **Mine count slider (1–24)** to adjust difficulty before a round
- **Automatic reset** after win/loss
- **Visual mine reveal** on loss

---

## How to Play

1. Use the slider to choose the number of mines (before placing a bet)
2. Enter your bet amount
3. Click **Place Bet**
4. Click tiles:
   - Safe tile → multiplier increases
   - Mine → round ends and you lose your bet
5. Click **Cash Out** any time to claim winnings for that round
6. After win/loss, start a new round and optionally change mine count again

---

## How to Run

Make sure you have **Python 3.9+** installed.

```bash
python demo3.py
