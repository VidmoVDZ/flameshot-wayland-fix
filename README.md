# flameshot-wayland-fix
The fix trick for some wayland compositors like Hyprland etc. It will make you be able to use flameshot without doubt!

# fish-shell
The best option for that fix is FISH! So the only thing you need is to find your fish config and do like this:
```fish
set XDG_CURRENT_DESKTOP "Sway"
```
If you try to run `flameshot gui` or `flameshot` in terminal in fish shell, it will be okay but as app not really sometimes.
So the thing is you must execute flameshot through the fish shell, it executes fish env and the command that uses that env vars!
So do like this
```fish -c "flameshot"```, the fix will be even better if you have fish installed and you use other shell in ex. nushell or zsh. So you have no need to be sick of some env vars.

