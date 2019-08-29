# ErgoDox Infinity: rcjpisani

- This layout aims to balance muscle memory from a typical QWERTY layout
  using the [MDErgo1 Default](https://input.club/configurator-ergodox/)
  preset as a base with slight modifications for touch typists. Switch S37
  is unbound due to a manufacturing error with my board.

- Symbols match regular QWERTY.

- Layer functions are placed (almost) along the center edges, with the
  exceptions of switch S1 (Top-right, left hand) which is set to = and F11
  as a continuation of the symbols to the left of the backspace on the
  number row, and switch S8 (right hand), which is set to [ also as a
  continuation of the symbols on that row.

- The space bars can be found symmetrically on the closest thumb area keys to
  be more familiar with touch typists who use both thumbs for the space bar.


## Keymap 0: Basic layer

```

,--------------------------------------------------.           ,--------------------------------------------------.
|  Esc   |   1  |   2  |   3  |   4  |   5  |   +  |           | TG(2)|   6  |   7  |   8  |   9  |   0  |   -    |
|--------+------+------+------+------+-------------|           |------+------+------+------+------+------+--------|
| Tab    |   Q  |   W  |   E  |   R  |   T  | TG(1)|           |   [  |   Y  |   U  |   I  |   O  |   P  |   ]    |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|   \    |   A  |   S  |   D  |   F  |   G  |------|           |------|   H  |   J  |   K  |   L  |   ;  |   '    |
|--------+------+------+------+------+------| MO(1)|           | MO(1)|------+------+------+------+------+--------|
| LShift |   Z  |   X  |   C  |   V  |   B  |      |           |      |   N  |   M  |   ,  |   .  |   /  | RShift |
`--------+------+------+------+------+-------------'           `-------------+------+------+------+------+--------'
  | LGUI |   `  |Insert| Left | Right|                                       | Down |  Up  |  Del |      | RGUI |
  `----------------------------------'                                       `----------------------------------'
                                       ,-------------.       ,-------------.
                                       | LCtrl| LAlt |       | RAlt | RCtrl  |
                                ,------|------|------|       |------+--------+------.
                                |      |      | Home |       | PgUp |        |      |
                                | Space|Backsp|------|       |------| Enter  |Space |
                                |      |ace   | End  |       | PgDn |        |      |
                                `--------------------'       `----------------------'
```

## Keymap 1: Gaming / Media layer

Notes:

- The LGUI key is now RCTL for gaming, and as a temporary workaround for
  an existing issue in Overwatch (WINE) that causes LCTL to be unbindable.
- The LGUI and LALT keys are using the more traditional QWERTY placements.
- Function keys are placed in the number row.

```
,---------------------------------------------------.           ,--------------------------------------------------.
|         |  F1  |  F2  |  F3  |  F4  |  F5  |  F11 |           |  F12 |  F6  |  F7  |  F8  |  F9  |  F10 |        |
|---------+------+------+------+------+------+------|           |------+------+------+------+------+------+--------|
|         |      |      |      |      |      |      |           |      |      |      |      |      | PSCR |        |
|---------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|         |      |      |      |      |      |------|           |------|      |      |      |      |      |        |
|---------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|         |      |      |      |      |      |      |           |      |      | Mute | MPRV | MNXT |      |        |
`---------+------+------+------+------+-------------'           `-------------+------+------+------+------+--------'
  | RCTL  | LGUI | LALT |      |      |                                       | VOL- | VOL+ |      |      |      |
  `-----------------------------------'                                       `----------------------------------'
                                       ,-------------.       ,-------------.
                                       |      |   `  |       |      |      |
                                ,------|------|------|       |------+------+------.
                                |      |      |      |       |      |      |      |
                                |      |      |------|       |------|      |      |
                                |      |      |      |       |      |      |      |
                                `--------------------'       `--------------------'

```

## Keymap 2: Mouse / Keypad

```
,--------------------------------------------------.           ,--------------------------------------------------.
|        |      |      |      |      |      |      |           |      |      |NMLCK |  /   |  *   |  -   |        |
|--------+------+------+------+------+-------------|           |------+------+------+------+------+------+--------|
|        |      | MsUp |      |      |      |      |           |      |      |  7   |  8   |  9   |  +   |        |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|        |MsLeft|MsDown|MsRght|      |      |------|           |------|      |  4   |  5   |  6   |  +   |        |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|        |      |      |      |      |      |      |           |      |      |  1   |  2   |  3   |Enter |        |
`--------+------+------+------+------+-------------'           `-------------+------+------+------+------+--------'
  |      |      |      |      |      |                                       |      |      |  .   |      |      |
  `----------------------------------'                                       `----------------------------------'
                                       ,-------------.       ,-------------.
                                       |      |      |       |      |      |
                                ,------|------|------|       |------+------+------.
                                |      |      |      |       |      |      |      |
                                | Lclk | Rclk |------|       |------|      |  0   |
                                |      |      |      |       |      |      |      |
                                `--------------------'       `--------------------'
```

## Changelog

- 2019/08/29
  Initial setup (work in progress)
