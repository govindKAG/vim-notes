# TMUX notes

My leader = ctrl + B

## windows

- leader + w lists all windows .
- leader + c creates one.
- leader + 0-9 switches to a window .
- leader + l switches to last used window, analagous to alt-tabbing.

## panes

- leader + ctrl + up/down/left/right arrow to resize splits.
- leader + ctrl + o rotate panes counter clockwise.
- leader + q lists the pane number.
- leader + z toggles fulscreen for current pane

## command mode

- leader + : enteres tmux's command mode 
- swap-pane -s pane_no -t pane_no swaps the two panes.

## copy mode

- enter copy mode using leader + [.
- most vim controls work in copy mode including line and block visual mode.
- start text selection by hitting space.
- yank selected text using space 
- leader + ] pastes from the tmux clipboard.
