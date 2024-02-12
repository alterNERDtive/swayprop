# swayprop

xprop for Sway


## Dependencies

FIXXME

- `hyprland` obviously
- [hyprevents](https://github.com/vilari-mickopf/hyprevents) capture window changed events to rerun slurp
- `socat` to connect hyprevents with hyprprop events
- `slurp` to select an area on the screen
- `jq` to parse hyprctl output

## Install
```bash
yay -S hyprprop-git
```
or
```bash
sudo make install
```

## Usage
Just run
```bash
swayprop
```
and select desired window
