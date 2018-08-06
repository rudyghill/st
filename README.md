# Rudy Hill's build of st - the simple (suckless) terminal

Forked from [https://github.com/shiva/st](https://github.com/shiva/st) for simplicity's sake, which is the [suckless terminal (st)](https://st.suckless.org/) with some patches added:

+ transparency
+ copy to clipboard
+ vertcenter
+ scrollback with keyboard
+ scrollback with mouse

## My own additions

+ Default font is system "Inconsolata" at 22pt
+ Fixed transparency patch (see below for installation)
+ Alt-k and Alt-j scroll back/foward in history one line at a time
+ Alt-u and Alt-d scroll back/foward in history a page at a time
+ Ctrl++ to increase font
+ Ctrl+- to decrease font
+ Ctrl+Alt+c to copy
+ Ctrl+Alt+v to paste


## Terminal-specific mappings

(Additions before me.)

+ Scroll through history -- Shift+PageUp/PageDown or Shift+Mouse wheel
+ Increase/decrease font size -- Shift+Alt+PageUp/PageDown
+ Return to default font size -- Shift+Alt+Home
+ Paste -- Shift+Insert

## Installation for newbs

```
make
sudo make install
```

