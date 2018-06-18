# elm Color


This package is a compilation of these two packges, adapted to elm 0.19:

- Color, from [elm-lang/core](https://github.com/elm-lang/core/blob/5.1.1/src/Color.elm)
- [eskimoblood/elm-color-extra](https://github.com/eskimoblood/elm-color-extra)

It also includes some code from [fredcy/elm-parseint](https://github.com/fredcy/elm-parseint)

## Content

Library for working with colors. Includes [RGB](https://en.wikipedia.org/wiki/RGB_color_model) and [HSL](http://en.wikipedia.org/wiki/HSL_and_HSV) creation, gradients, and built-in names.

## Colors

Color


## Creation

rgb, rgba, hsl, hsla, greyscale, grayscale, complement


## Gradients

Gradient, linear, radial


## Extracting Colors

toRgb, toHsl


## Built-in Colors

These colors come from the [Tango palette](http://tango.freedesktop.org/Tango_Icon_Theme_Guidelines) which provides aesthetically reasonable defaults for colors. Each color also comes with a light and dark version.


### Standard

red, orange, yellow, green, blue, purple, brown


### Light

lightRed, lightOrange, lightYellow, lightGreen, lightBlue, lightPurple, lightBrown


### Dark

darkRed, darkOrange, darkYellow, darkGreen, darkBlue, darkPurple, darkBrown


### Eight Shades of Grey

These colors are a compatible series of shades of grey, fitting nicely with the Tango palette. white, lightGrey, grey, darkGrey, lightCharcoal, charcoal, darkCharcoal, black

These are identical to the *grey* versions. It seems the spelling is regional, but that has never helped me remember which one I should be writing. lightGray, gray, darkGray
