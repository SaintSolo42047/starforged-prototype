# Starforged Video Game Prototype

A visual single-player prototype of Ironsworn: Starforged rules built in Pygame.  

It demonstrates the exact solo TTRPG mechanics:
- Action roll (1d6 + stat vs 2d10)
- Meters, momentum, and progress tracks
- State-based situations (travel, combat, conversation, obstacle)
- Oracles that generate automatic reactions
- Physical ship movement with arrow keys

## How to run
1. `pip install -r requirements.txt`
2. `python starforged_prototype.py`

Controls  
- Arrow keys = move ship  
- R = roll action  
- T = travel state  
- C = combat state  
- V = conversation state  
- O = obstacle state  

This is a fan prototype for learning and testing Starforged rules in a video game format. All core mechanics come directly from the Starforged rulebook.

Built with Pygame. Inspired by Shawn Tomkin's Ironsworn: Starforged (CC licensed content used with attribution).
