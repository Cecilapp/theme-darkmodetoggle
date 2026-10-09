---
title: Home
playground: true
---
# Dark mode toggle for Cecil

This website is the demo of the [_Dark mode toggle_ component theme](https://github.com/Cecilapp/theme-darkmodetoggle) for [Cecil](https://cecil.app).

Click the **moon** (or the **sun**) in the header, or the big button below, to switch between the light and dark color schemes:

- your choice is remembered, until it matches your system preference again;
- change the color scheme of your system: the page follows it;
- reload the page: there is no flash of the wrong color scheme.

The big button is the same partial, customized with CSS custom properties, and the buttons below use the JavaScript API (`window.colorScheme.set()`).
