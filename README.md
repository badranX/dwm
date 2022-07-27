## dwm
This dwm is always true full screen unless more than one window is open in the tag. For example, monocle layout (max layout) is full screen unless two or more windows are open. This is way more convenient than reading a number on the bar and it saves more screen space than having tabs.

The gap for the monocle layout can be configured and can be controlled using the the `ru_gaps` patch shortcuts.

### This dwm adapt the following patches:
- Holdbar patch: In config.def.h, HOLDKEY should be set to the `keysym` of your key. `keysym` can be found using the `xev` tool. Configuring this to the a MOD key will give a similar behaviour to the "hide mode" in i3wm.

- `ru_gaps` from suckless.org, `dwm-ru_gaps-6.3.diff`.

- `pertag` patch from suckless.org without saving the status of the bar for each tag. So toggling the bar will toggle for all tags. 

- Finally, simple config.def.h changes: Shortcut keys change and set the `alacritty` terminal instead of `st`.
