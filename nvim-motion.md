# Basic Neovim Motions and Editing Cheat Sheet

## Character Motions

- **`h`** - Move left.
- **`l`** - Move right.

- **`j`** - Move down one line.
- **`k`** - Move up one line.

## Word Motions

- **`w`** - Move to the start of the next word.
- **`e`** - Move to the end of the current/next word.
- **`b`** - Move to the start of the previous word.

## Line Motions

- **`0`** - Move to the beginning of the current line.
- **`$`** - Move to the end of the current line.
- **`^`** - Move to the first non-blank character of the current line.

## Scrolling

- **`Ctrl-e`** - Scroll down one line (without moving the cursor).

- **`Ctrl-y`** - Scroll up one line (without moving the cursor).
- **`Ctrl-d`** - Scroll down half a screen.
- **`Ctrl-u`** - Scroll up half a screen.
- **`Ctrl-f`** - Scroll forward one full screen.
- **`Ctrl-b`** - Scroll backward one full screen.
- **`zz`** - Center the cursor on the screen.

## Normal Mode to Insert Mode

- **`i`** - Insert before the cursor.
- **`a`** - Insert after the cursor.
- **`I`** - Insert at the beginning of the current line.
- **`A`** - Insert at the end of the current line.
- **`o`** - Open a new line below the current line and enter insert mode.
- **`O`** - Open a new line above the current line and enter insert mode.

## Insert Mode to Normal Mode

- **`Esc`** - Press to return to normal mode.

## Paragraph Motions

- **`{`** - Move to the beginning of the current/previous paragraph.
- **`}`** - Move to the beginning of the next paragraph.

## Screen Motions

- **`H`** - Move to the top of the screen.
- **`M`** - Move to the middle of the screen.
- **`L`** - Move to the bottom of the screen.

## Search

- **`/text`** - Search forward for `text`.
- **`?text`** - Search backward for `text`.
- **`n`** - Repeat the last search forward.
- **`N`** - Repeat the last search backward.

## Sentence Motions

- **`)`** - Move to the beginning of the next sentence.
- **`(`** - Move to the beginning of the current/previous sentence.

## Tag Motions

- **`%`** - Jump between matching pairs (e.g., `()` `{}` `[]`).

## Mark Motions

- **`'a`** - Jump to the beginning of the line containing mark `a`.
- **`` `a ``** - Jump to the exact position of mark `a`.

## Text Object Motions

These motions can be used with operators like `d`, `c`, `y`:

- **`aw`** - A word (including trailing space).
- **`iw`** - Inner word (excluding trailing space).
- **`ap`** - A paragraph.
- **`ip`** - Inner paragraph.
- **`a"`** - A quoted string (double quotes).
- **`i"`** - Inner quoted string.

## Editing Commands

### Delete

- **`d{motion}`** - Delete text covered by the motion.
  - Example: **`dw`** - Delete from the current position to the start of the next word.
  - **`diw`** - Delete the current word (excluding trailing space).
  - **`d$`** - Delete from the current position to the end of the line.
- **`dd`** - Delete the entire current line.

### Change (Delete + Insert)

- **`c{motion}`** - Delete text covered by the motion and switch to insert mode.
  - Example: **`cw`** - Change (delete and start inserting) from the current position to the start of the next word.
  - **`ciw`** - Change the current word (excluding trailing space).
  - **`c$`** - Change from the current position to the end of the line.
- **`cc`** - Change (delete and start inserting) the entire current line.

### Yank (Copy)

- **`y{motion}`** - Yank text covered by the motion.
  - Example: **`yw`** - Yank from the current position to the start of the next word.
  - **`yiw`** - Yank the current word (excluding trailing space).
- **`yy`** - Yank the entire current line.

### Paste

- **`p`** - Paste after the cursor.
- **`P`** - Paste before the cursor.

## Visual Mode

- **`v`** - Start visual mode to select text (characterwise).
- **`V`** - Start visual line mode to select entire lines.
- **`Ctrl-v`** - Start visual block mode to select a block of text.
- **`d`** - Delete the selected text (in visual mode).
- **`y`** - Yank the selected text (in visual mode).
- **`c`** - Change the selected text (delete and start inserting in visual mode).

## Modes Overview

- **Normal Mode**: Press `Esc` to return to normal mode from insert or visual mode.
- **Insert Mode**: Press `i`, `a`, `I`, `A`, `o`, or `O` to enter insert mode from normal mode.
- **Visual Mode**: Use `v` for characterwise, `V` for linewise, and `Ctrl-v` for blockwise selections.

## Tips

- Combine motions with operators for efficient editing (e.g., `d`, `c`, `y`).
  - Example: **`dw`** deletes from the current position to the start of the next word.
  - Example: **`cw`** deletes the word and switches to insert mode.
- Use **`v`** for visual mode, allowing selection with motions.
