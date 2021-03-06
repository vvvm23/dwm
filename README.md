# My build of DWM

A work-in-progress build for dynamic window manager. Mostly default bindings except modifier key is SUPER and not ALT (ew)

## Patches Applied

- vanitygaps, for the pointless aesthetics
- scratchpad, for a nice pop up terminal (useful for quick notes, compiling station, etc.)
- nofocusclick, for replacing the terrible default
- alpha, for alpha support in the tag bar (likely to be removed when I get a proper bar)
- notitle, does what it says on the tin
- swallow, prevents that annoying linux-y thing of leaving useless terminals when launching GUI applications from them
- noborder, turns off borders when there is only one window
- statusallmons, update status bar across all monitors

## Additional Layouts
- bottomstack (bottomstackhorz in code but disabled)
- centeredmaster (centeredfloatingmaster, also disabled)

## Additional Features
- More obvious highlighting of focussed windows (conversely, toning down of unfocussed windows)
- Screenshot bindings provided by flameshot
- Audio control bindings using default X11 media keys
- Getting rid of annoying version number in bar
- Fixing issues with dual screen, 21:9 on duplicated status bars (by quite literally painting over the problem)
- Toggle bar and status bar independently with META+SHIFT+b
- Gaps for some additional layouts

## Todo(s):
- Define rules for swallowing 
- Define rules for floating 
- Deadlines in position where win title used to be.
