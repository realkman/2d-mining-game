# Terra

**Dig. Build. Survive the night.**

Terra is a small 2D sandbox survival game. You start with nothing: punch a tree, craft a pickaxe, and dig down into the dark.

## Download

1. Go to the [**Releases**](../../releases) page and download the latest `terra.zip` (or `terra.exe`).
2. If you downloaded the zip, extract it. Then run `terra.exe`.
3. You can also get Terra from the **Store** tab inside Launchpad.

**Windows may warn you the first time.** Terra is a small unsigned program, so SmartScreen can say it doesn't recognise it. Click **More info**, then **Run anyway**.

Your characters and worlds are saved in a `terra_saves` folder next to the program.

## Features

- Mine dirt, stone, coal, iron and gold, and chop whole trees
- Craft a pickaxe, axe, sword, torches, bricks, metal blocks, a bed and a door
- Slimes, zombies, bats and spiders: zombies roam the surface at night and burn in sunlight, the rest lurk in caves
- Smooth lighting: caves are dark, so bring torches
- Build a shelter with doors, and set your respawn point with a bed
- Character creator with several saved characters
- Multiple worlds with a seed and five sizes (Tiny, Small, Medium, Large, Huge)
- Autosave, and options for frame rate, window scale, particles and clouds

## How to play

1. Punch a tree for **wood**. Chopping a trunk fells the whole tree.
2. Craft **planks**, then a **pickaxe**. Stone, coal and ore can't be mined bare-handed.
3. Craft an **axe** (planks + stone) to chop wood fast, and a **sword** (planks + iron) to hit monsters hard.
4. Dig down for coal, iron and gold. Make **torches** (wood + coal) for the caves.
5. Before dark, build a shelter. Craft a **door** (planks) and a **bed** (planks + wood). Right click the bed to set your spawn. A closed door blocks monsters.

You can only reach four and a half blocks from where you stand, for mining, placing and fighting alike.

## Controls

| Key | Action |
|---|---|
| `A` `D` / arrows | Walk |
| `W` / `Up` / `Space` | Jump |
| Left mouse (hold) | Mine a block / hit a monster |
| Right mouse or `E` | Place a block, open or close a door, set spawn on a bed |
| `1`-`9`, `0` or mouse wheel | Select hotbar slot |
| `Tab` or `I` | Inventory and crafting |
| `Z` | Quick-craft 4 torches (1 wood + 1 coal) |
| `X` | Quick-craft 2 planks (1 wood) |
| `Esc` or `P` | Pause menu |
| `F` | Toggle FPS counter |

In the inventory, left click picks up, drops, swaps or merges a stack, and right click takes half a stack or drops a single item. Click a recipe on the right to craft it.

## Run from source

You need Python 3.8+ and `renderer.py` (the drawing library Terra is built on) in the same folder.

```
python terra.py
```

To build your own exe on Windows, run `build_terra_exe.bat`. It installs PyInstaller and produces `dist\terra.exe`.

## Credits

Made by realKman.
