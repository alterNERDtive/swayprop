# swayprop

Xprop for Sway. Inspired by https://github.com/vilari-mickopf/hyprprop, but 
shares almost no code with it anymore.

## Dependencies

- Sway
- jq for parsing `swaymsg` output
- slurp for window selection

## Installation

### Basher

[![basher-install](https://www.basher.it/assets/logo/basher_install.svg)](https://www.basher.it/package/)

```bash
basher install git.alternerd.tv/alterNERDtive/swayprop
```

(Github mirror: `basher install alterNERDtive/swayprop`)

### Manual

Clone the repository
(`git clone https://git.alternerd.tv/alterNERDtive/swayprop.git`) or download 
and extract a repository archive, then link / copy `swayprop` into your `PATH`.

## Usage

Just run
```bash
swayprop
```
and select desired window.

The tool will print the selected Window’s JSON output from `swaymsg -t 
get_tree`, or nothing on error/cancel.

If you cancel the selection it will `exit 1`, in case slurp errors out it relays 
the exit code.
