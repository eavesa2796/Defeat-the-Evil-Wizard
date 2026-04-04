# 🧙‍♂️ Defeat the Wizard

A turn-based combat RPG game where you choose a character class and battle against the Evil Wizard to save the realm!

## 📖 Overview

Defeat the Wizard is a text-based Python game featuring multiple character classes, each with unique abilities and stats. Choose your hero, strategize your moves, and defeat the Dark Wizard before he defeats you!

## 🎮 How to Play

1. **Run the game:**

   ```bash
   python battlefield.py
   ```

2. **Choose your character class** from 5 available options

3. **Battle the Evil Wizard** using these actions:
   - **Attack** ⚔️ - Deal basic damage to the wizard
   - **Use Special Ability** ✨ - Use your class-specific powers
   - **Heal** ❤️‍🩹 - Restore 50 HP (limited uses)
   - **View Stats** 📊 - Check your current health and attack power

4. **Win Condition:** Reduce the Evil Wizard's health to 0 before he defeats you!

## 🛡️ Character Classes

### Warrior

- **Health:** 140 HP
- **Attack Power:** 25
- **Heal Uses:** 2
- **Special Abilities:**
  - **Power Attack** 🦵💥 - Jump kick dealing +10 damage
  - **Spit Fire** 🔥 - Flame attack dealing +15 damage

### Mage

- **Health:** 100 HP
- **Attack Power:** 35
- **Heal Uses:** 3
- **Special Abilities:**
  - **Cast Spell** 🪄 - Magic attack dealing +5 damage
  - **Invisible Cloak** 👻 - Become invisible and dodge the next attack

### Archer

- **Health:** 135 HP
- **Attack Power:** 30
- **Heal Uses:** 3
- **Special Abilities:**
  - **Quick Shot** 🏹 - Fire 2 arrows dealing +10 damage
  - **Evade** 🏃‍♂️‍➡️ - Dodge the next enemy attack

### Paladin

- **Health:** 145 HP
- **Attack Power:** 20
- **Heal Uses:** 1
- **Special Abilities:**
  - **Holy Strike** ✨ - Divine attack dealing +5 damage
  - **Divine Shield** 🛡️ - Block the next enemy attack

### Rogue

- **Health:** 135 HP
- **Attack Power:** 20
- **Heal Uses:** 3
- **Special Abilities:**
  - **Backstab** 🗡️ - 20% chance to deal critical damage (2x)
  - **Shadow Step** 🌀 - Disappear into shadows and avoid the next attack

## 👹 The Enemy

### Evil Wizard (The Dark Wizard)

- **Health:** 150 HP
- **Attack Power:** 15
- **Heal Uses:** 5
- **Special Ability:** Regenerates 5 HP every turn

## 🎯 Game Mechanics

- **Damage Variance:** Attacks deal base damage ±5 (random)
- **Healing:** Restores 50 HP per use, cannot exceed max health
- **Avoid System:** Dodge abilities set an `avoid` flag that negates the wizard's next attack
- **Turn-Based:** Player acts first, then the wizard attacks and regenerates

## 📁 Project Structure

```
Defeat the Wizard/
│
├── battlefield.py    # Main game loop and battle system
├── characters.py     # Character classes and abilities
└── README.md        # This file
```

## 🔧 Requirements

- Python 3.x
- A Python virtual environment (`.venv`) is required
- No external libraries required (uses only `random` module)

## 🧪 Virtual Environment Setup (Required)

Create and activate a virtual environment before running the game.

### Windows (PowerShell)

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python battlefield.py
```

### Windows (Command Prompt)

```bat
python -m venv .venv
.venv\Scripts\activate.bat
python battlefield.py
```

## 💡 Strategy Tips

1. **Balance offense and defense** - Don't forget to heal!
2. **Use dodge abilities wisely** - Save them for when your health is low
3. **The wizard regenerates** - Try to deal more damage than he can heal
4. **Each class has strengths** - High attack classes can overwhelm quickly, tanky classes can outlast

## 🎓 Learning Concepts

This project demonstrates:

- Object-Oriented Programming (OOP)
- Class inheritance
- Method overriding
- User input handling
- Game state management
- Turn-based combat systems

## 📝 Future Enhancements

Potential improvements:

- Multiple difficulty levels
- Save/load game progress
- More character classes
- Equipment and inventory system
- Multiple enemies or boss battles
- GUI interface

## 👨‍💻 Author

Created as a Python learning project for practicing OOP concepts and game development fundamentals.

---

**Good luck, hero! May you defeat the Dark Wizard and bring peace to the realm!** ⚔️✨
