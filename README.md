# Escape from the Haunted Mansion 🏚️🔑

A text-based Python adventure game created for Ironhack’s DS/AI Engineering boot-camp (Week 6 Project).  
Explore a creepy mansion, examine objects, collect keys, unlock doors, and escape before time runs out!

---

## Table of Contents
1. [Gameplay Overview](#gameplay-overview)  
2. [How to Run](#how-to-run)  
3. [Core Features](#core-features)  
4. [Code Structure](#code-structure)  
5. [Project Timeline & Lessons](#project-timeline--lessons)  
6. [Future Work](#future-work)

---

## Gameplay Overview
- **Start:** You wake up in the dimly lit Main Room.  
- **Commands:**  
  - `look` – describe the current room  
  - `examine <object>` – inspect an object (find hidden keys)  
  - `take <item>` – add a visible item to inventory  
  - `use <item>` – unlock a door that requires that key  
  - `move <room>` – walk to a connected room (if door unlocked)  
  - `help` – list commands  
  - `exit` – quit game  
- **Win:** Reach the **Outside** room after unlocking all required doors.

---

## How to Run
```bash
# clone repo
git clone https://github.com/<your-username>/escape-haunted-mansion.git
cd escape-haunted-mansion

# (optional) create a venv
python -m venv .venv
source .venv/bin/activate   # Linux/macOS
# .venv\Scripts\activate    # Windows

# run the game
python main.py
