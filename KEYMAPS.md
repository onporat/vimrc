#### \<C-{a-z}\> keymaps:

- Buffers:
  - `<C-h>` goes to the previous buffer.
  - `<C-l>` goes to the next buffer.

- Text edition:
  - `<C-j>` moves lines down.
  - `<C-k>` moves lines up.

- Plugins related:
  - `<C-p>` previews the current GitGutter hunk.
  - `<C-n>` opens, focuses or closes NERDTree.
  - `<C-s>` expands neosnippet from 'Insert Mode'.
  - `<C-z>` goes to the `:VimShell`.
  - `<C-d>` expands Jedi completions.

- Misc:
  - `<C-s>` shows syntax highlighting groups.

- 'Insert Mode' and 'Command Mode':
  - `<C-a>` moves the cursor to the line start.
  - `<C-e>` moves the cursor to the line end.
  - `<C-b>` moves the cursor back one character.
  - `<C-f>` moves the cursor forward one character.

#### \<A-{a-z}\> keymaps:

- Windows:
  - `<A-h>` goes to the window: left.
  - `<A-j>` goes to the window: down.
  - `<A-k>` goes to the window: up.
  - `<A-l>` goes to the window: right.

#### \<F{1..12}\> and \<S-F{1-12}\> keymaps:
- `<F1>` it's the default help.
- `<F2>` renames the current buffer.
- `<F3>` toggles line numbers.
- `<S-F3>` toggles relative numbers.
- `<F4>` toggles Tagbar (plugin).
- `<F5>` reloads all open buffers.
- `<F6>` toggles list.
- `<F7>` toggles 'Paste Mode'.
- `<F8>` toggles spell checking.
- `<S-F8>` toggles spell dictionaries.
- `<F9>` toggles colorcolumn.
- `<F10>` toggles maximize/minimize the current window.
- `<F11>` empty: desktops use it to toggle fullscreen.
- `<F12>` reloads your Vim/Neovim configuration.
- `<S-F12>` reloads the current colorscheme.

#### \<Leader\> keymaps:

- Buffers:
  - `<Leader>s` updates the buffer (saves if it has changes).
  - `<Leader>S` updates all the buffers.
  - `<Leader>bd` closes the current buffer.
  - `<Leader>ba` closes all the buffers.
  - `<Leader>bb` opens the `:edit` command.
  - `<Leader>bg` opens a list of all the buffers.
  - `<Leader><Del>y` deletes the current buffer. Careful!

- Filepath:
  - `<Leader>bw` switches CWD to the current filepath.
  - `<Leader>by` copies the filepath to the clipboard.

- Tabs:
  - `<Leader>td` closes the current tab.
  - `<Leader>to` closes all the tabs except the current.
  - `<Leader>tt` opens the `:tabedit` command.
  - `<Leader>tr` moves the tab position to the left.
  - `<Leader>ty` moves the tab position to the right.

- Windows:
  - `<Leader>.` it is `wincmd` to easily manage windows.
  - `<Leader>.-` splits window horizontally.
  - `<Leader>..` splits window vertically.
  - `<Leader>.<CR>` closes the current window.
  - `<Leader>.x` closes the current window forcing it.
  - `<Leader>.,` restores the proportional size of windows.
  - `<Leader>.l` returns to the last window.
  - `<Leader>.p` goes to the previous window.
  - `<Leader>.n` goes to the next window.
  - `<Leader>.o` closes all windows excepting the current.

- About lines:
  - `<Leader>m` removes the Windows ^M.
  - `<Leader>ds` duplicates a line up.
  - `<Leader>df` duplicates a line down.
  - `<Leader>o` isolates the current line.
  - `<Leader>f` enters a new line down from 'Normal Mode'.
  - `<Leader>F` enters a new line up from 'Normal Mode'.

- Search:
  - `<Leader><CR>` searches the word under the cursor.
  - `<Leader><CR>` also, searches the current selection!
  - `<Leader><BS>` disables highlight.

- Vimgrep:
  - `<Leader>v` vimgreps the highlight in the current file.
  - `<Leader>V` vimgreps the highlight in the current directory.
  - `<Leader>n` goes to the next vimgrep result.
  - `<Leader>N` goes to the previous vimgrep result.

- Replace:
  - `<Leader>r` replaces the current highlight.
  - `<Leader>a` opens all the files of the current directory.
  - `<Leader>A` opens all the files of the subdirectories, as well.
  - `<Leader>do` replaces the highlight to all the buffers.

- Text edition:
  - `<Leader><` toggles the case of a character.
  - `<leader><` toggles the case of a selection, as well.
  - `<Leader>wn` moves to the next misspelled word.
  - `<Leader>wp` moves to the previous misspelled word.
  - `<Leader>wa` adds the word under the cursor into the dictionary.
  - `<Leader>wx` marks the word under the cursor as wrong.
  - `<Leader>w?` suggests correctly spelled words.
  - `<Leader>tf` retabs the current selection.

- Clipboard:
  - `<Leader>y` copies text into the clipboard.
  - `<Leader>p` pastes text from the clipboard.

- Plugins related:
  - `<Leader><TAB>` runs the code of the current buffer.
  - `<Leader>j` goes to the next GitGutter hunk.
  - `<Leader>k` goes to the previous GitGutter hunk.
  - `<Leader>c` toggles the commented code..
  - `<Leader>h` goes to the previous warning/error.
  - `<Leader>l` goes to the next warning/error.
  - `<Leader>q` toggles the quickfix window.
  - `<Leader>e` toggles the location list window.
  - `<Leader>z` toggles the plugin FZF (:Files).
  - `<Leader>x` toggles the plugin FZF (:Buffers).
  - `<Leader>C` toggles the plugin FZF (:Commits).
  - `<Leader>u` toggles the plugin Gundo.
  - `<Leader>ga` inits easy align plugin.
  - `<Leader>ta` inits tabularize plugin.
  - `<Leader>t1` inits tabularize plugin (only the first match).
  - `<Leader>W` inits ArgWrap plugin.
  - `<Leader>M` inits Markdown preview plugin.

#### \<Win-{a-z}\> keymaps:

- 'Insert Mode' and 'Command Mode':
  - `<Win-h>` moves the cursor back one character.
  - `<Win-j>` moves the cursor down one line.
  - `<Win-k>` moves the cursor up one line.
  - `<Win-l>` moves the cursor forward one character.

It's a generic explanation of the main commands. Some are only for a specific mode and most of them are usable from all the modes, so if you need more precise information, check the code.