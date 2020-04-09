# ENGG1340 Project Group 90

# Group Members
3035687522 LEE Ho Yin
3035692694 Lee Cheuk Pui


## Project Title
(Pending) Farming Simulator

## Game Description
Grind, grind and grind the hell out

## Game Rules
Farm to earn currency and buy new kinds of crops, larger field and bigger warehouses
Store crops in warehouse→ more profit for selling a set of crops (like gta speciality goods)

## Game Features
### Generation of random game sets or events
Random generation of:
Thieves (stealing a portion of crops in stock)
Natural disasters (flood, typhoon, drought) → loss of different kinds of crop
Treasures/Loot boxes/Login bonus (++ money/unlock new crops)

### Data structures for storing game status
Use a struct (string playerName, int level/int exp→ then calculate level)?
2D array/vector for map

### Dynamic memory management
Use a 2D vector? Make the map be expandable when level increases (buy a larger field)

### File input/output (e.g., for loading/saving game status)
Use a text file to save current game progress and the player can either open a new save or load previous progress when launching the game.
Save function/ or even multiple saves?

### Program codes in multiple files
Implement functions separately and store with header files, then include the header files in the main program 
