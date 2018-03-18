# Vortex Pok3r layout

This is a guide for configuring a keyboard layout that is great for developers
on Linux. The layout is basically featuring the following:

- Use `fn+hjkl` for navigation
- Use `l_ctrl` as `function`
- Map `caps lock`  to `l_ctrl`
- Swap the `l_win` and `l_alt` keys
- Swap the `r_alt` and `fn`, and map `fn` to `super`.

I'm using this layout actively when developing with the Pok3er on Arch Linux
with NeoVim as my weapon of choice.

The great thing is that you can pick and choose from the settings below. Treat
this guide as an example, not the Truth of a great set up.

## Basics

Only layers 2-4 are programmable, the default layer is not. So when following
this guide, make sure you are on any of layers 2-4 (`fn + ,`, `.` or `/`).

### Entering programming mode

To enter the programming mode on the keyboard, press `fn + r_ctrl`. The left LED
under the space bar will now start flashing.

Note again that this is not possible in the default layer.

## Configuration

### Use `fn+hjlk` for navigation

1. Start by entering programming mode, `fn + r_ctrl`
2. Map `fn + h` to left:
    1. `fn + h` (set target)
    2. `fn + j` (set source)
    3. `pn`/`menu` (save)
3. Map `fn + j` to down:
    1. `fn + j` (set target)
    2. `fn + k` (set source)
    3. `pn`/`menu` (save)
4. Map `fn + k` to up:
    1. `fn + k` (set target)
    2. `fn + i` (set source)
    3. `pn`/`menu` (save)
5. Exit programming mode: `fn + r_ctrl`

### Map `caps lock` to `l_ctrl`

1. Start by entering programming mode, `fn + r_ctrl`
2. Map `caps lock` to `l_ctrl`:
    1. `caps lock` (set target)
    2. `l_ctrl` (set source)
    3. `pn`/`menu` (save)
3. Exit programming mode: `fn + r_ctrl`

### Swap left `alt` and `super` (`win`)

    R_CMD: R_Alt then: R_FN (Win) then: PN
    R_Option: R_FN (Win) then: R_Alt then: PN

1. Start by entering programming mode, `fn + r_ctrl`
2. Map `l_alt` to `l_win`:
    1. `l_alt` (set target)
    2. `l_win` (set source)
    3. `pn`/`menu` (save)
3. Map `l_win` to `l_alt`:
    1. `l_win` (set target)
    2. `l_alt` (set source)
    3. `pn`/`menu` (save)
4. Exit programming mode: `fn + r_ctrl`

### Swap right `alt` and `fn`

1. Start by entering programming mode, `fn + r_ctrl`
2. Map `r_alt` to `r_fn`:
    1. `r_alt` (set target)
    2. `r_fn` (set source)
    3. `pn`/`menu` (save)
3. Map `r_fn` to `r_alt`:
    1. `r_fn` (set target)
    2. `r_alt` (set source)
    3. `pn`/`menu` (save)
4. Exit programming mode: `fn + r_ctrl`

### Map `l_ctrl` to `fn`

1. Unplug the keyboard
2. Switch DIP switch 4 (the hardware switches on the back of the keyboard to ON)
3. Plug the keyboard back in again
4. Press `fn` then `l_ctrl`, then `pn` and then `pn`
5. Switch DIP switch 4 back to OFF
