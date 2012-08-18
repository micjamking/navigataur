#Navigataur.css
*A pure CSS responsive navigation menu*


##Demo
Live Demo: http://micjamking.github.com/Navigataur/demo


##Usage
To use `navigataur.css`, reference the stylesheet in the `<head>` of your document (or you can place within your own stylesheet).

To work out of the box, you will need to make the following adjustments to your markup (classes can be changed in the stylesheet if you use something different):
* An outer `<div>` with a class of `header` 
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

That's it! Everything works out of the box with this setup. However, like any CSS plugin/snippet, you will probably want to stylize it to match your sites theme. I've separated all functional CSS from the presentational CSS so you can jump right in and change everything you need without breaking the plugin. Edit to your hearts desire below the following comment in the CSS:

```
/*--------------------------------
 Presentation Styles (Editable)
---------------------------------*/
```

##Support
This plugin is currently supported in the following browsers; however, there are some inconsistencies between the default rendering of `input[type=checkbox]` controls and the ability to apply custom styles to it.

* Google Chrome (any)
* Safari (3.0+)
* Firefox (any; however, `input[type=checkbox]` still renders native control and can't be fully styled )
* Opera (12; no support for :after pseudo element, `input[type=checkbox]` renders native control for `:checked` state)
* *IE 6+  (just kidding; this plugin fails horribly below IE 10)

*Something to note; WebKit rendering engine makes up the vast majority of mobile browsers (iOS, Android, Nokia), so you can expect the same level of support for mobile browsing as you see in Chrome/Safari

##Details
* This plugin was created in response to [Menutron](https://github.com/micjamking/Menutron), a jquery plugin I created for responsive navigation menus. While I menutron is more functional as it provides access to native navigation controls on mobile devices, `<select>` controls are not very attractive. Navigataur.css is for those that want the same responsive capabilities, but with a more control over the styling.
* If you have any suggestions, comments, or creative insults for my code, [add an issue](https://github.com/micjamking/Navigataur/issues/new) or [fork the repo](https://github.com/micjamking/Navigataur/fork_select).


##Copyright
Copyright (c) 2012 Mike King (@micjamking)