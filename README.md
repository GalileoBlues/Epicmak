# Epicmak
A keyboard layout designed to be Slow and uncomfortable to type on, Based on Vitrimak.
This keyboard layout was created because of speed claims about more efficient layouts than QWERTY
such as Colemak and Dvorak, Anecdotally people agree that Colemak and Dvorak are more comfortable than QWERTY
to type with but the fastest typists (on 10fastfingers.com) self reportedly use the QWERTY
layout we are all familar with.

This is where Epicmak comes in, it's a layout made with the express purpose of making the top 200 words
(and hopefully more) as slow and uncomfortable as possible.
```
e p i c m d w n b o
 . h / f x g ' , q z
r u v s k l j a y t
```
it does this by making most of the homerow less used characters and placing the most used characters apart from
eachother either split between lesser used characters or split between the homerow with the intention of making rolls either awkward or slower in general. Epicmak also tries to account for finger dexterity puting most commonly used two character combinations in the corners to be used by the pinky fingers, Admittingly this isn't as bad if the user is someone with good pinky dexerity but this is to account for what i believe to be the average typer.

# Install:
If demand permits i may provide instructions for other OS' but for now here are linux instructions:
Place the "epicmak" C file in your ``/usr/share/X11/xkb/symbols`` directory 
then set Epicmak as your layout with ``setxkbmap epicmak``

multiple layouts and hotkeys: ``setxkbmap -layout "us, epicmak" -option "grp:ctrl_alt_k"``
for more advanced customisation please refer to xkb documentation on xorg's website
[here](https://www.x.org/releases/X11R7.6/doc/xorg-docs/input/XKB-Config.html#id2521360)
