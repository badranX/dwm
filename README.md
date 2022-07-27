## dwm with the following:

- Holdbar patch: In config.def.h, HOLDKEY should be set to the keysym of your key. Can be found using "xev". This will give a similar behaviour to "hide mode" in i3wm.

- ru_gaps from succkless dwm-ru_gaps-6.3.diff

- pertag without saving the status of the bar for each tag. So toggling the bar will toggle for all tags.

- Finally, basic config.def.h changes: Shortcut keys change and set the `alacritty` terminal instead of `st`.
