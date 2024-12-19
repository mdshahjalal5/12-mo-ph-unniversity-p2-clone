--w: 19/12/2024 04:59 PM Thu GMT+6 Sharifpur, Gazipur, Dhaka

## keyboard remapping by keyd application

```
n = enter
. = n
capslock = esc,
enter = .
; = f3
f3 = ;
a hold f = ctrl+ f,
; hold f = ctrl + f,
s hold f = super + f,
f hold f = alt + f,
l hold f = shift + f ( that menas capital f),

```

## Arrow key

```
capslock + h = left arrow,
caps + l = right arrow,
caps + j = down arrow,
caps + k = up arrow,

```

# Hyprland tutorial:

## Shutdown, Suspend, Restart

```
s+t = Shutdown the pc
s+r = restart the pc,
s+y = suspend or sleep the pc,
s+q = quit from Hyprland
```

## cursor focus

```
s+h = focus left,
s+l = focus right,
s+j = focus down,
s+k = focus up,
s+f = maximize/minimize

```

## volume control

```
s+f+u = increasing volume,
s+f+i = decrease volume,
```

## swapping windows

```
s+f+h = swap with left,
s+f+l = swap with right,
s+f+j = swap with down,
s+f+k = swap with up,
```

## workspace tutorial

```
s+1/s+u = go workspace 1,
s+2/s+i = go workspace 2,
s+3 = go workspace 3,
s+4 = go workspace 4,
s+5 = go workspace 5, (in this way you can use upto 9 workspace)
```

## Resizing windows

```
s+a+h = resize  left,
s+a+l = resize  right,
s+a+j = resize  down,
s+a+k = resize  up,

```

## Moving windows

```
s+shift+h = move  left,
s+shift+l = move  right,
s+shift+j = move  down,
s+shift+k = move  up,

```

# Keyd and Hyprland Configuration Guide

This document provides an overview of **keyboard remapping** using Keyd and **window management** in Hyprland. It explains key functionalities, shortcuts, and operations to enhance your productivity.

---

## Keyboard Remapping with Keyd

### Basic Key Remapping

- `n` → Acts as `Enter`.
- `.` → Acts as `n`.
- `Caps Lock` → Acts as `Esc`.
- `Enter` → Acts as `.`.
- `;` → Acts as `F3`.
- `F3` → Acts as `;`.

---

### Advanced Key Remapping (Hold to Trigger Modifiers)

- **`a` hold `f`** → `Ctrl + f`
- **`;` hold `f`** → `Ctrl + f`
- **`s` hold `f`** → `Super + f`
- **`f` hold `f`** → `Alt + f`
- **`l` hold `f`** → `Shift + f` (i.e., `F`)

---

### Arrow Key Remapping

- **`Caps Lock + h`** → Left Arrow.
- **`Caps Lock + l`** → Right Arrow.
- **`Caps Lock + j`** → Down Arrow.
- **`Caps Lock + k`** → Up Arrow.

---

## Hyprland Tutorial

### Power Management

- **Shutdown**: `s + t`
- **Restart**: `s + r`
- **Suspend/Sleep**: `s + y`
- **Quit Hyprland**: `s + q`

---

### Cursor Focus Management

- **Focus Left**: `s + h`
- **Focus Right**: `s + l`
- **Focus Down**: `s + j`
- **Focus Up**: `s + k`
- **Maximize/Minimize Window**: `s + f`

---

### Volume Control

- **Increase Volume**: `s + f + u`
- **Decrease Volume**: `s + f + i`

---

### Window Swapping

- **Swap with Left Window**: `s + f + h`
- **Swap with Right Window**: `s + f + l`
- **Swap with Window Below**: `s + f + j`
- **Swap with Window Above**: `s + f + k`

---

### Workspace Management

- **Go to Workspace 1**: `s + 1` or `s + u`
- **Go to Workspace 2**: `s + 2` or `s + i`
- **Go to Workspace 3**: `s + 3`
- **Go to Workspace 4**: `s + 4`
- **Go to Workspace 5**: `s + 5`  
  _(Continue in the same pattern up to Workspace 9.)_

---

### Resizing Windows

- **Resize Left**: `s + a + h`
- **Resize Right**: `s + a + l`
- **Resize Down**: `s + a + j`
- **Resize Up**: `s + a + k`

---

### Moving Windows

- **Move Left**: `s + Shift + h`
- **Move Right**: `s + Shift + l`
- **Move Down**: `s + Shift + j`
- **Move Up**: `s + Shift + k`

---

## Conclusion

This guide provides clear and concise instructions for configuring Keyd and managing Hyprland. These shortcuts are designed to boost productivity and simplify navigation, whether you're working with windows, resizing, or managing workspaces.

--w: 19/12/2024 04:59 PM Thu GMT+6 Sharifpur, Gazipur, Dhaka

# Tmux = terminal multiplexer tutorial

```
** seop = session, window, pane,
1. sesssion can hold multiple windows, each window can hold multiple panes,

```

## Tmux Sessions and windows tutorial

( in our pc prefix is f3 and f3 is remapped with semicolon ; \*\* that means you have to press ; )

### see all the keybindings( keyboard shortcuts ) = prefix ?

```
1. see  the existing sessions: prefix  press s
** prefix i = switch(go ) to the last used session
** prefix b = switch to the cfg session
2. create a new session, type  "sess sessionName"
```

### window tutorial

```
3. prefix c = create a new window,
4. prefix 0/1/2/3/4/5 = switch(go) to the 0/1/2/3/4/5th window
5. prefix f = switch to the last used window,
6. prefix p = switch to previous window
7. prefix n = switch to next window
8. prefix , = rename the current  window
9. prefix , = rename the current  window




```

## Tmux pane tutorial

```
1. prefix a = create a new vertical pane( create a new pane below the current pane )
2. prefix v = create a new horizontal  pane( create a new pane right side of  the current pane )
3. ctrl + h, j, k, l = change cursor focus left, down, up, right,
4. prefix x = kill the current pane

```

## Tmux resizing panes

```

1. increase or decrease size
prefix hjkl = resize right, down, up, right (you have to fast type hjkl )
```

# Tmux Tutorial: Terminal Multiplexer

Tmux is a terminal multiplexer that allows you to manage multiple terminal sessions efficiently. It supports **sessions**, **windows**, and **panes**, making multitasking in the terminal seamless.

## Key Concepts

1. **Session**: A collection of windows.
2. **Window**: A collection of panes within a session.
3. **Pane**: A split view within a window.

> **Note**: In this guide, the prefix key is remapped to `;`. Press `;` before any keybinding mentioned below.

---

## General Keybindings

- **See all keybindings**: `prefix ?`

---

## Sessions Tutorial

### Manage Sessions

1. **See all sessions**: `prefix s`
2. **Switch to the last-used session**: `prefix i`
3. **Switch to a specific session (e.g., `cfg`)**: `prefix b`
4. **Create a new session**:  
   Type `sess sessionName` in the terminal.

---

## Windows Tutorial

### Manage Windows

1. **Create a new window**: `prefix c`
2. **Switch to a specific window (0/1/2/3/4/5)**: `prefix 0`, `prefix 1`, etc.
3. **Switch to the last-used window**: `prefix f`
4. **Switch to the previous window**: `prefix p`
5. **Switch to the next window**: `prefix n`
6. **Rename the current window**: `prefix ,`

---

## Panes Tutorial

### Manage Panes

1. **Create a vertical pane (below current)**: `prefix a`
2. **Create a horizontal pane (right of current)**: `prefix v`
3. **Change focus between panes**:  
   Use `Ctrl + h` (left), `Ctrl + j` (down), `Ctrl + k` (up), `Ctrl + l` (right).
4. **Kill the current pane**: `prefix x`

---

## Resizing Panes

### Resize Panes

1. Use `prefix hjkl` to resize panes:
   - `h`: Resize left
   - `j`: Resize down
   - `k`: Resize up
   - `l`: Resize right  
     **Note**: Type `hjkl` quickly after pressing the prefix key.

---

This guide covers essential Tmux operations for managing sessions, windows, and panes. Use these shortcuts to enhance your terminal productivity.
