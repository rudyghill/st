# Rudy's Suckless Terminal (st)

Rudy Hill's fork of the [suckless terminal (st)](https://st.suckless.org/) with some patches added.

## Patches Applied
+ transparency
+ copy to clipboard
+ vertcenter
+ scrollback with keyboard
+ scrollback with mouse
+ external pipe

## Keybindings and Features

### Aesthetics
+ Default font is system monospace at 22pt
+ Default color theme is gruvbox

### Clipboard
+ Shift+Alt+c to copy
+ Shift+Alt+v to paste
+ Shift+Insert to paste

### Scrollback
+ Alt-k and Alt-j scroll back/forward in history one line at a time
+ Alt-u and Alt-d scroll back/forward in history a page at a time
+ Shift+PageUp/PageDown
+ Shift+Mouse wheel

### Increase/Decrease font
+ Ctrl++/- to increase/decrease font size
+ Ctrl+0 to reset font size
+ Shift+Alt+PageUp/PageDown to increase/decrease font size
+ Shift+Alt+Home to reset font size

### Pipe URLs to dmenu
+ Alt+l for link export

# Installation

## Dependencies

st is an Xorg based application so obviously Xorg is required.  Further, you need a C compiler for the installation.  I have not tried other compilers but `gcc` works fine for me.  For link export to work, `dmenu` is required as well as a script named `linkgrabber` found [here](https://github.com/rudyghill/dotfiles/blob/master/scripts/.scripts/linkgrabber) .

## Compilation

Like other suckless programs, compilation and installation are done by entering:

```
make
sudo make install
```
