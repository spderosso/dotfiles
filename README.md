Steps
-----

- `brew install vim` (because we need vim > 8)
- `brew install fzf`, `(brew --prefix)/opt/fzf/install` (
    see https://github.com/junegunn/fzf#using-homebrew-or-linuxbrew)
- `brew install the_silver_searcher` (
    see https://github.com/ggreer/the_silver_searcher)
- follow instructions in https://github.com/Valloric/YouCompleteMe#mac-os-x
    to get autocomplete working

Also:
- use Novel theme with Consolas 14pt
- `git config --global core.excludesfile ~/.gitignore_global` and add `*.swp`
  and `*~`

Docs
----

In `vim`:
- `f`: will open fzf. `Ctrl-c` to exit, `Enter` to open the selected file in the
  current buffer, `Ctrl-v` to open it in a vertical split
- `l`: toggles ALE, `ln` to go to the next error, `lp` to go to the previous one
- `F3`: go to definition. `Ctrl-o` will take you back
- trailing whitespaces are removed on save
- open the file tree with `Ctrl-n`. On the tree, `Enter` opens
the file, `Ctrl-v` opens it in a vertical split (just like with fzf)
- `%S` for search and replace that respects case variants
- `:lopen` to expand the status bar message when errors appear truncated

In the terminal:
- `Ctrl-T` will open fzf
- To search for a string in files use `ag <pattern>`
- To open in vim a set of files matching a pattern use ``vim `ag \<pattern\> -l```
- To search for patterns in filenames use `ag -g <pattern>`
- To include hidden files in the search use `ag --hidden <pattern>`

To temporarily disable all plugins invoke `vim` with the `--noplugins` flag

If you update vim, you might have to update the installed plugins. To do
so run `:PluginUpdate`


Resources
---------

[https://statico.github.io/vim3.html](https://github.com/statico/dotfiles)https://github.com/statico/dotfiles
