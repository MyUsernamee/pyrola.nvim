This branch's goal is to add images to the terminal on the side instead of unicode low res images.
Specifically it is only going to target KGP (Kitty Graphics Protocol), with no intended support for any others.
This should be possible with KGP's [unicode place holders](https://sw.kovidgoyal.net/kitty/graphics-protocol/#unicode-placeholders).

_notes / references:_

https://sw.kovidgoyal.net/kitty/_downloads/f0a0de9ec8d9ff4456206db8e0814937/rowcolumn-diacritics.txt
https://sw.kovidgoyal.net/kitty/graphics-protocol/#unicode-placeholders

goal:

Add unique ids to every image. (done)
Unicode place holder. (done)
Multi image placement? (Might remove because having images in the out defeats the purpose lowkey)
Get image width and height in python, and place proper amount of extmarks
