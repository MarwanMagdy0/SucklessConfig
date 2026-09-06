# How to copy the font
``` shell
cp YourFont.ttf ~/.local/share/fonts/
fc-cache -fv
```

# How To add a patch
``` shell
patch -p1 < patches/st-scrollback-reflow-standalone-0.9.3.diff
```
