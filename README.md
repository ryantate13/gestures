# Touch Screen Gestures for Gnome 3

Enables macos-like touch gestures for Ghome 3. Tested on Dell XPS 13.

## Installation

Requires the [gestures](https://gitlab.com/cunidev/gestures) utility to be installed.

```bash
pacaur -S gestures # or AUR utility of choice
# note: python-gobject dependency not installed by default
sudo pacman -S python-gobject
sudo reboot # ymmv
```

Launch gestures utility and import [`Gestures.conf`](./Gestures.conf).


## Gestures Enabled

### Three-Finger Swipe Up

Mapped to `super`, shows activity overview

### Three-Finger Swipe Down

Mapped to `Escape`, exit activity overview (or just generally have a useful touch gesture for the escape key 😀)


### Three-Finger Swipe Right

Mapped to `Alt_l+Left`, "back" in browsers


### Three-Finger Swipe Left

Mapped to `Alt_l+Right`, "forward" in browsers

### Four-Finger Swipe Up

Mapped to `super+Page_Down`, switch to next workspace

### Four-Finger Swipe Down


Mapped to `super+Page_Up`, switch to previous workspace
