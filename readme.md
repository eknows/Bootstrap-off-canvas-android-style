#Bootstrap Android sytle off canvas menu

## Description
Bootstrap navigation hack for Android style off canvas menu.
1. only works with "navbar-static-top"
2. jquery is required
3. jquery mobile is required for touch events, build it here:
http://jquerymobile.com/download-builder/
4. bootstrap ist required
5. Hack your Bootstrap navigation:

Add "<div class="overlay"></div>" directly after the body tag

Change navbar button data-toggle
data-toggle="collapse"  --->  data-toggle="offcanvas"

Add class "navbar-static-top" to <nav class="navbar navbar-default">

Add class "pull-left" to navbar Button

6. Demo Time
http://jsfiddle.net/do05ptj2/