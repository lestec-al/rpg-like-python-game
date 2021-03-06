# RPG-like Game with Python and PyGame

The project on early stage of development, but even now game (rather demo) is playable.

<img src="https://github.com/lestec-al/rpg-like-python-game/raw/main/pic_game.png" width="750" height="470"/>

Keyboard controls:
- wasd: move, f: attack, e: append item, i: inventory-looting-trade (left-click: equip(use) item, right-click: remove(sell) item)

What is ready (but could be improved):
- player/NPC with animations, battle logic, skills (spear, sword), inventory, items, health, energy
- type items: weapons, clothes, potions, coins and chests for them
- NPC enemy move (with colisions, when player in some radius) and attack the player
- NPC trader sells/buys items for 100 coins per item
- interface, sounds, simple world map with NPCs

Work in process (maybe):
- optimization (fast, stable gameplay, code organize)
- bigger world map with many NPCs, items and simple story
- bow sprite, bow logic
- enemy repopulation
- improve trade (add prices)
- rebalance items (damage, armor)

You need:
- install Python (v3.10 or higher)
- install PyGame, Pillow
- download (and extract) or clone this repo
- launch via command line "python main.py" in the project folder

The project used:
- the map was created using the level editor "Tiled" - https://www.mapeditor.org
- character sprites - https://opengameart.org/content/character-animations-clothes-armor-weapons-skeleton-enemy-combat-dummy
- world map graphics - https://opengameart.org/content/2d-lost-garden-tileset-transition-to-jetrels-wood-tileset
- some items icons - http://dycha.net
- box icons - https://opengameart.org/content/jrpg-chests-16-32-64-and-128px-squared
- some sounds - https://darkworldaudio.itch.io/sound-effects-survival-i
- forest sound - https://opengameart.org/content/forest-ambience
- beach waves sound - https://opengameart.org/content/beach-ocean-waves