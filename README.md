# Sticky Notes

These are the files I use to make sticky notes on bspwm/alacritty.

## Video

https://youtu.be/-cKtas8kI7w

## zshrc excerpt

```bash
if [[ $STICKY_NOTE ]]; then
  PS1=
  cat "$HOME/temp/sticky-note"
  return
fi
```

## bspwm config excerpt

```
bspc rule -a sticky-note state=floating sticky=on border=off

```
