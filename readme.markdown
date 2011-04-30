This is custom theme switcher that I've basically forked from jQuery UI's [Theme Switcher Widget](http://jqueryui.com/docs/Theming/ThemeSwitcher)

What I've done that makes my widget unique is a couple of things.

1. I've changed the urls for the images, so that they will work on sites outside of the jquery domain.  This was something that 
   I noticed was happening not only for me but also the community at large.
   
2. I've added the ability to add your own jQuery UI themes to the mix.  I've also included an example of how to do this using
   [Wijmo's Themes](http://wijmo.com/widgets/theming/). I'm just using Wijmo as an example because I, myself, am not a designer,
   and I needed a reference for how to do this.  As such, I'm not afiliated with Wijmo in any way.

The Examples
----------------

- If you want to use the drop down with it's default behavior, please refer to index.htm.

- However, if you would like to add additional themes, other than the ones provided by jQuery UI,
  you can very easily add them, and a good example would be found in the addingcustomthemes.htm file.
  
Dependencies
----------------

- [jQuery UI](http://jqueryui.com)

- [jQuery Templates](http://api.jquery.com/category/plugins/templates/)