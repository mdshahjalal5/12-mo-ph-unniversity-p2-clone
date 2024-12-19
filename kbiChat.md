# Tmux Tutorial: Terminal Multiplexer

## Tmux Overview

- **Session**: A session can hold multiple windows, and each window can have multiple panes.
- **Window**: A window is a single workspace within a session where you can run commands or applications.
- **Pane**: A pane is a split section of a window where you can run separate commands in parallel.

---

## Managing Tmux Sessions

1. **View Existing Sessions**:

   - Press **prefix** (`;` in your setup) and then press `s` to see all available sessions.

2. **Switch to Last Used Session**:

   - Press **prefix** and then `i` to switch to the last used session.

3. **Switch to a Specific Session**:

   - Press **prefix** and then `b` to switch to the session named `cfg`.

4. **Create a New Session**:

   - Type the following to create a new session:
     ```bash
     sess sessionName
     ```

5. **Create a New Window**:

   - Press **prefix** and then `c` to create a new window in the current session.

6. **Switch Between Windows**:
   - Press **prefix** and then `0`, `1`, `2`, `3`, `4`, or `5` to switch to the respective window.
   - Press **prefix** and then `f` to switch to the last used window.

---

## Managing Tmux Panes

1. **Create a New Vertical Pane**:

   - Press **prefix** and then `a` to create a new vertical pane (a pane below the current one).

2. **Create a New Horizontal Pane**:
   - Press **prefix** and then `v` to create a new horizontal pane (a pane to the right of the current one).

---

## Summary

- **Prefix** key: `;`
- **Session**: Can contain multiple windows.
- **Window**: A workspace within a session, containing panes.
- **Pane**: A split section of a window for running commands.
