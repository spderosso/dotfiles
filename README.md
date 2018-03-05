Steps
-----

(because we need vim > 8)
```
brew install vim
```

follow instructions in 
https://github.com/Valloric/YouCompleteMe#mac-os-x

Useful things to know:

In `vim`:
- `f`: will open fzf. `Ctrl-c` to exit, `Enter` to open the selected file in the
  current buffer, `Ctrl-v` to open it in a vertical split
- `l`: toggles ALE, `ln` to go to the next error, `lp` to go to the previous one
- `F3`: go to definition. `Ctrl-o` will take you back

In the terminal:
- `Ctrl-T` will open fzf

Also:
- use Novel theme with Consolas 14pt
- `git config --global core.excludesfile ~/.gitignore_global` and add `*.swp`
  and `*~`

Resources
---------

https://statico.github.io/vim3.html
