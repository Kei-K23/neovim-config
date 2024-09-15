# Neovim Configuration repo with NvChad

This repo contain my Neovim configuration files with NvChad.

## Neovim and NvChad tips


### Basic Movement:
- `h`, `j`, `k`, `l`: Move left, down, up, right (alternative to arrow keys).
- `gg`: Go to the top of the file.
- `G`: Go to the bottom of the file.
- `Ctrl + u`: Scroll half a page up.
- `Ctrl + d`: Scroll half a page down.
- `w`, `b`: Move forward/backward by a word.
- `0`: Move to the beginning of the line.
- `$`: Move to the end of the line.
- `%`: Jump to the matching parenthesis, bracket, or tag.

### File Management:
- `:w`: Save the file.
- `:q`: Quit.
- `:wq`: Save and quit.
- `:q!`: Quit without saving.
- `:e filename`: Open a new file.
- `:bnext` / `:bprev`: Switch between open buffers.

### Editing Shortcuts:
- `i`: Enter insert mode at the current position.
- `I`: Enter insert mode at the beginning of the line.
- `a`: Enter insert mode after the current character.
- `A`: Enter insert mode at the end of the line.
- `o`: Insert a new line below and enter insert mode.
- `O`: Insert a new line above and enter insert mode.
- `d`: Delete (use with movement, e.g., `dw` to delete a word).
- `dd`: Delete the entire line.
- `c`: Change (similar to `d` but enters insert mode after).
- `cc`: Change the entire line.
- `y`: Yank (copy).
- `yy`: Yank the entire line.
- `p`: Paste.
- `u`: Undo.
- `Ctrl + r`: Redo.

### Visual Mode:
- `v`: Enter visual mode to select text.
- `V`: Enter visual line mode to select entire lines.
- `Ctrl + v`: Enter visual block mode (column-wise selection).
- `d`: Delete the selected text in visual mode.
- `y`: Copy (yank) the selected text.
- `p`: Paste the copied text.

### Window Management:
- `Ctrl + w, s`: Split the window horizontally.
- `Ctrl + w, v`: Split the window vertically.
- `Ctrl + w, h`: Move to the window on the left.
- `Ctrl + w, l`: Move to the window on the right.
- `Ctrl + w, j`: Move to the window below.
- `Ctrl + w, k`: Move to the window above.
- `Ctrl + w, q`: Close the current window.

### Buffer Management (NvChad specific):
- `Ctrl + n`: Toggle the file explorer (NvimTree).
- `Space + x`: Close the current buffer.
- `Space + l`: Open the NvChad custom buffer list.
- `Space + c`: Close all buffers except the current one.
- `Alt + j/k`: Move to the next/previous buffer.

### Search and Replace:
- `/text`: Search for "text" in the file.
- `n`: Go to the next search result.
- `N`: Go to the previous search result.
- `:%s/old/new/g`: Replace "old" with "new" throughout the file.
- `:noh`: Clear search highlighting.

### Plugins and Shortcuts (NvChad Specific):
- `Space + f`: Open Telescope to search for files.
- `Space + F`: Find text inside files with Telescope.
- `Space + p`: Open Telescope’s project list.
- `Space + e`: Toggle the file explorer (NvimTree).
- `Space + g`: Open lazygit or a terminal for git commands.
- `Space + t`: Toggle terminal within Neovim.
- `Space + /`: Toggle comments on the current line or selection (with `nvim-comment` plugin).

### Code Navigation (LSP-related):
- `gd`: Go to the definition of the symbol under the cursor.
- `gr`: Show references of the symbol.
- `K`: Show documentation for the symbol.
- `Space + r`: Rename symbol.
- `Space + a`: Show code actions (quick fixes).
- `Space + e`: Show diagnostics for the current line.
- `Space + D`: Show diagnostics for the whole project.

### Git Integration (NvChad):
- `Space + g`: Open Git menu (fugitive or lazygit depending on config).
- `:Gstatus`: Check git status.
- `:Gcommit`: Commit staged changes.
- `:Gpush`: Push to the repository.

### Additional Tips:
- **Leader Key**: In NvChad, the leader key is `Space`, which gives you access to many shortcuts (e.g., `Space + f` to find files with Telescope).
