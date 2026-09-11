# LodeRunner for the Commander X16

Picking up where Chris Love (https://github.com/CJLove/) left off on this Commander X16 Port of one of my all time favourite games.

## Goals

- Address a few issues with the sound
- Address some issues with the game losing track of the gold count and levels being unpalyable
- scale the playfield up to utilise more screen area 


## Game Play
From the splash screen the following keys to select game options:
* Cursor up/down select the world
* Cursor left/right toggle sound
* `<` and `>` adjust the game speed
* `-` and `+` adjust the starting level

Use `ENTER` to begin play.

Use cursor arrow keys to move the runner, `z` to dig left and `x` to dig right.  Use `ENTER` to kill the runner if trapped.

## Building and Running
Building requires the CC65 toolchain with r37 support or later. 
Python3 scripts are used to build binary files from various assets. 
After cloning the repo, do the following:
```bash
git submodule update --init
cd libX16/src
make
cd ../../src
make all
/path/to/x16emu -prg lode_runner.prg
```

