# Compass OH-Buttons

by Marek Babik <contact@marekbabik.com>

## Description

(Demo at: [Github](http://mrkbbk.github.com/compass-oh-button/)

OH-Button ("OH" derived from "over-the-head" type of perspective as seen on various oldschool RPG's on NES/SNES/GBA, you know, "Zelda", "Final Fantasy" etc ;) is a pseudo-3D button, styled using pure CSS3, inspired by buttons on Firefox Add-ons site.

To ease the pain of creating one by hand, I've made simple Compass mixin to include in your project.
##How to use

Drop "_oh-button.scss" file somewhere, where Compass can find it, add:
SCSS

    @import "oh-button";

to the beginnig of your .scss file, then use it like this:
SCSS

    selector {
        @include oh-button(
            [$color]
            [,$depth]
            [,$roundness]
            [,$v-padding]
            [,$h-padding]
            [,font size]
        );
    }
	

Where:

* **selector** - a CSS selector (one which is pointing to "a" (anchor) element, in most cases)
* **$color** - yup, desired color, default: #555
* **$depth** - "depth" of a button, default: 3px
* **$roundness** - corner radius, default: 5px
* **$v-padding** - vertical padding, default: 10px
* **$h-padding** - horizontal padding, default: 10px
* **$font-size** - size of the used font, default: 1em

