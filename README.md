# Lunar Lander — Side-Scrolling Thruster Game (Python)

A fast, arcade-style **Lunar Lander**: burn fuel to fight gravity, drift through debris fields,
collect **orbs** for points, grab **fuel canisters** to stay alive, touch down on **landing pads**
for multipliers, and get **tractor-beamed** into the mother ship at the end of the level.
Nail **5 orbs in a row** without touching fuel for a bonus chain.

> 🎮 Tight controls • 🧪 Pure arcade loops • 🌫️ Debris & pads • 🛸 End-level tractor beam

---

## Features
- Gravity + inertia with thruster-based control
- Fuel system (consumption + pickups)
- Orbs & combo scoring (5-orb streak bonus)
- Debris hazards & terrain pads (scoring multipliers on safe landing)
- End-of-level tractor beam to extract the lander
- (Optional) parallax backgrounds, ambient music, and SFX

---

## Requirements
- Python 3.10+
- Pygame (see `requirements.txt`)

### Setup
```bash
python3 -m venv .venv
source .venv/bin/activate              # Windows: .venv\Scripts\activate
python -m pip install --upgrade pip
pip install -r requirements.txt
