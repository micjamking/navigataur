#Navigataur.css
*A pure CSS responsive navigation menu*

`navigataur.css` is a pure css plugin for sexy, responsive navigation menus. 


##Demo
Live Demo: http://micjamking.github.com/Navigataur/demo



##Usage
To use `navigataur.css`, reference the stylesheet in the `<head>` of your document (or you can place within your own stylesheet).

To work out of the box, you will need the following adjustments to your markup:
* A top `<div>` with a class of `header` (can be changed in the stylesheet if you use something different)
* An `input[type=checkbox]` with a class of `toggle` just above your list menu. 
* A list menu (either ul or ol) with a class of `menu`

```
<input type='checkbox' class='toggle' />
<ul class="menu">
  <li><a href="#">Google</a></li>
  <li><a href="#">Facebook</a></li>		
  <li><a href="#">Youtube</a></li>	
  <li><a href="#">Twitter</a></li>	
</ul>
```

That's it! Everything will works out of the box with this setup. However, like any CSS plugin/snippet, you will probably want to stylize it to match your sites theme. I've separated all functional CSS from the presentational CSS so you can jump write in and change everything you need without breaking the plugin. Just edit to your hearts desire below the following comment in the CSS

```
/*--------------------------------
 Presentation Styles (Editable)
---------------------------------*/
```

##Details
* This plugin was created in response to [Menutron](https://github.com/micjamking/Menutron), a jquery plugin I created for responsive navigation menus. While I menutron is more functional as it provides access to native navigation controls on mobile devices, `<select>` controls are not very attractive. Navigataur.css is for those that want the same responsive capabilities, but with a more control over the styling.
* If you have any suggestions, comments, or creative insults for my code, [add an issue](https://github.com/micjamking/Navigataur/issues/new) or [fork the repo](https://github.com/micjamking/Navigataur/fork_select).


##Copyright
Copyright (c) 2012 Mike King (@micjamking)