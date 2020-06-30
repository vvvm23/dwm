# My build of DWM
---

A work-in-progress build for dynamic window manager. Mostly default bindings except modifier key is SUPER and not ALT (ew)

## Patches Applied
---

- vanitygaps, for the pointless aesthetics
- scratchpad, for a nice pop up terminal (useful for quick notes, compiling station, etc.)
- nofocusclick, for replacing the terrible default
- alpha, for alpha support in the tag bar (likely to be removed when I get a proper bar)
- notitle, does what it says on the tin
- swallow, prevents that annoying linux-y thing of leaving useless terminals when launching GUI applications from them
- noborder, turns off borders when there is only one window

## Additional Layouts
---
- bottomstack & bottomstackhorz 

## Additional Features
---
- More obvious highlighting of focussed windows (conversely, toning down of unfocussed windows)
- Screenshot bindings provided by flameshot
- Audio control bindings using default X11 media keys
- Getting rid of annoying version number in bar

## Todo(s):
---
- Generic gaps support for any additional layouts. Currently only the default work with gaps.
- A fancier status bar, either dwmblocks or polybar
- Status bar widgets like in my i3blocks repo
- Define rules for swallowing (for example, walter eats the debug terminal. not great)
- Define rules for floating (for example, walter (again) eats the screen space when it should float)
