# keyboard-window-focus

Focus desktop windows to the left or right using keyboard shortcuts

## Requires:
- wmctrl

## How to:

- Clone this repository: `git clone https://github.com/nvaytet/keyboard-window-focus.git`
- In your keyboard shortcuts, add 2 new shortcuts:
  1. Command: `/path/to/the/cloned/repository/keyboard-window-focus.sh "left"` -> pair with `Win+left`
  2. Command: `/path/to/the/cloned/repository/keyboard-window-focus.sh "right"` -> pair with `Win+right`

This should now allow you to change the focus of your desktop windows using `Win+left` and `Win+right` (these are just examples, naturally you can use any key combination you want to activate the commands).
This is useful if you are constantly switching back and forth between code editor and terminal and don't want to move the mouse every time.

## To do:

- Implement up/down focus switching.
