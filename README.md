WL CSS HELPER LIB
=================
Author: Aritz Olabarrieta
Version: 1.0

A tiny LESS file with commonly used CSS instructions, which will
help you building the layout and structure of any project. It works
great in combination with Bootstrap.

Simply include the minified CSS version in your proyect:

<link rel="stylesheet" href="wl-helpers.min.css" />

NOTES and USE GUIDE
-------------------

- All WL classes are prefixed with "wl-".
- There are 5 different sizes, which can be configured with "@wl-base-" variables: xs, sm, md, lg and xl.
- Fluid boxes are prepared to fit in 100%, so if you want, for example, a 3 column row, you can use the wl-box-33 class, which is a 33.33% div with display set to inline-block.

{SIZES} = xs, sm, md, lg OR xl
{BOXSIZES} = 75, 60, 50, 40, 33, 25, 20, 16, 15, 14, 12, 11, 10, 5

- CLEARFIXES:          wl-cfix-{{SIZES}}
- DISPLAY:             wl-ds-{block, inline, inline-block, none}
- FLOATS:              wl-fl-{none, left, right}
- POSITION:            wl-ps-{absolute, fixed, relative, static}
- MARGINS:             wl-ma-auto, wl-ma-{all, bottom, left, right, top}-{no, {SIZES}}
- PADDINGS:            wl-pa-{all, bottom, left, right, top}-{SIZES}
- FLUID BOXES:         wl-box-{{BOXSIZES}}
- FULLWIDTH:           wl-fullwidth

CHANGELOG
---------

05-07-2014
- First release
