AutoScroll without text deselection
==========

_Become The Master of your middle button and forget about Firefox bugs!_

This extension adds Autoscroll function to Mozilla Firefox.

Wait... Mozilla Firefox has Autoscroll function already built-in, right? Yes, but...
Firefox 89 introduced bug where middle button down event deselects selected text: https://bugzilla.mozilla.org/show_bug.cgi?id=1714810

This extension is to workaround existing buggy behaviour and keep selection forever during autoscrolling with middle button. You can now mark text, scroll to another section and then go back to your selected text.

This project was forked from https://github.com/Pauan/AutoScroll

Known limitations
==========

* For the best experience built-in autoscroll setting in firefox should be enabled, because this extension does not work on some pages e.g. addons.mozilla.org. Unfortunaly on these pages autoscroll will still deselect selected text. But middle button will deselect selection on these pages anyway.
* Also scrollbars are not handled by this extension, but since scrollbars are not bugged and does not deselect selection it is not a problem at all.
