# jQuery Superfish Dropdown Menu Plugin

Our favourite aquatic superhero returns from his sojourn across the galaxy infused with astonishing, hitherto unseen new powers. In his modern incarnation (wearing a rather spiffy cape) Superfish is dedicated to keeping dropdown/flyout menus accessible across browsers great and small, in addition to adding support for newer touch devices (running Android, iOS, Windows, etc). All this **and** a pretty face.

## Documentation and Demos

Please use the [existing Superfish documentation](http://users.tpg.com.au/j_birch/plugins/superfish/) where you will find full explanations of the customisable features and plenty of examples to get you started.

## Download

###Important notes before you download:
- For your existing Superfish menus, you may prefer to stick with v1.5.11 unless you are prepared to alter your CSS to hide submenus using display:none rather than off-canvas (eg. top:-999em), otherwise you may lose closing animations (the submenus will be off-canvas while the animation happens).
- As of Superfish v1.5.1 if you wish to enhance your menu with Brian Cherne's hoverIntent plugin (highly recommended) you will need to use [the latest version (r7) which now supports event delegation](https://github.com/briancherne/jquery-hoverIntent).
- Follow this link if you need an [easy solution to address a hoverIntent conflict with WordPress](https://github.com/joeldbirch/superfish/issues/14#issuecomment-14554500).

### Download [Superfish zip archive](https://github.com/joeldbirch/superfish/archive/master.zip)

## Recently added features

- CSS refactor for easier customisation.
- Full support for touch devices. Touch to open submenus, touch again to follow the link. A simple solution for responsive web design: add some CSS media queries and use the same menu code-base at all screen sizes.
- IE10 has touch behaviour consistent with all other touch-enabled browsers despite its new pointer events system. Mouse events and keyboard access all work as per normal.
- Submenu closing animations. Customisable separately to opening animations.
- Uses event delegation for improved initialisation performance.