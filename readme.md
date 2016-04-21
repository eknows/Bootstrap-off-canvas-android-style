#Bootstrap Android style off canvas menu

## Description
Bootstrap navigation hack for Android style off canvas menu.

1. jQuery is required
2. jQuery mobile is required for touch events, build it here: http://jquerymobile.com/download-builder/ (Select Events / Touch)
3. bootstrap is required
4. Hack your Bootstrap navigation:

Add directly after the body tag
```<div class="overlay"></div>```

Change data-toggle to offcanvas
```<button type="button" class="navbar-toggle collapsed" data-toggle="offcanvas" aria-controls="navbar">```

Add class pull-left to navbar Button
```<button type="button" class="navbar-toggle collapsed pull-left" data-toggle="offcanvas" aria-controls="navbar">```

## Demo Time
http://jsfiddle.net/do05ptj2/9/
