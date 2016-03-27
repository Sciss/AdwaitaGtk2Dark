This repository contains a patched version of the Gnome 3.14 Adwaita theme's window decoration.
In order to make Gtk-2 applications use the dark look-and-feel, the patch hard-codes the dark
colors into the metacity file.

I am uncertain about the license of this design, but I suppose it is the same as
[adwaita-icon-theme](https://github.com/GNOME/adwaita-icon-theme), i.e. a dual license
for LGPL or CCBYSA3. Please let me know if this assertion is incorrect.

To install, make a copy of the full adwaita theme:

    cp -R /usr/share/themes/Adwaita ~/.local/share/themes/Adwaita-copy

Then replace the file `metacity-1/metacity-theme-3.xml` in the copy with the one from this repository.

Then in the Tweak tool, open the 'Appearance' tab and in the 'Window' row, select 'Adwaita-copy'.
