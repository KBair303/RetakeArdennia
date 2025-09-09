# Retake Ardennia

#Created by Krista B, Lauren K, Briar A, and Rory D.

**Retake Ardennia** is a 2D, event-driven adventure game built in **MATLAB** using the `simpleGameEngine`.  
Players create a character, select a background, and navigate a series of events—combat, riddles, traps, healing, and puzzles—on their quest to reclaim Ardennia from Dr. Cliff Rat and his generals.

---

## Features
- **Character creation** with multiple class backgrounds (Merchant, Warrior, Scholar, Hunter, Explorer).
- **Turn-based combat** with creatures and bosses using dice rolls + player stats.
- **Healing events** via items or rest spots, scaling with Intelligence.
- **Exploration encounters**: hidden treasures, random stat boosts, and traps.
- **Puzzle challenges**: sphinx riddles, Monty Python homage, trivia questions, and a memorization game.
- **Boss battles**: unique mechanics per general (word scrambles, combat, memory challenges).
- **Progression system**: defeat all four generals to unlock the final boss.

---

## Technology
- **Language:** MATLAB  
- **Graphics:** `simpleGameEngine` with `retro_pack.png` sprite sheet  
- **Core mechanics:** random number generation (`randi`), struct-based stat tracking, and branching events  

---

## Getting Started
1. Clone or download this repository.  
2. Place all `.m` files and the sprite sheet (`retro_pack.png`) in the same folder.  
3. Open the folder in MATLAB.  
4. Run the game from the start screen:
   ```matlab
   IntroCutscene
