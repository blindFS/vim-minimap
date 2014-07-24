A Sublime-like code minimap for Vim
===================================

Sublime can display an useful overview of the code as a  *minimap* sidebar.

We can implement the same thing in Vim, relying on the [Drawille
library](https://github.com/asciimoo/drawille) to 'draw' in text mode.

![Code minimap in Vim](minimap.png)

**Attention**: this extension is not yet ready for general use! It simply
displays the map when calling `ShowMinimap()`, but does not do anything useful
yet, like highlight the visible part of the buffer or synchronizing scrolling.
