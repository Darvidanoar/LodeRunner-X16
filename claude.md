### Lode Runner for the Commander X16

Ths project contains the C source code for a port of the classic arcad game Lode Runner, targeting the Commander X16.

## File structure

# assets

This folder contains
- json files for the level displays for various play options (classib, fanbook, championship etc.)
- txt files defining sprites, tiles and pallete colours

# libX16

This folder contains the C source for the libX16 library, as well as the compiled library file (libX16.lib)

# png

This folder contains png files of the runner sprite

# scripts

This folder contains python scripts used to convert the txt files from the assets folder into bin asset files for use by the game.

# src

The folder conains the C source for the game as well as the generated bin asset files and compiled lode_runner.prg file.


## Workflow

After every code change, commit with a clean, descriptive commit message and push to GitHub so there is always a saved version to revert to if needed.

## General Guidance

When editing existing code:
- Don't "improve" adjacent code, comments, or formatting.
- Don't refactor things that aren't broken.

Think before coding:
- If multiple interpretations exist, present them - don't pick silently.
- If something is unclear, stop. Name what's confusing. Ask.