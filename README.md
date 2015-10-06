WL CSS HELPER LIB
=================
A tiny LESS file with commonly used CSS instructions, which will
help you building the layout and structure of any project. It works
great in combination with Bootstrap.

Simply include the minified CSS version in your proyect:

<link rel="stylesheet" href="wl-helpers.min.css" />

NOTES and USE GUIDE
-------------------
- All WL classes are prefixed with "wl-".
- There are 5 different sizes, which can be configured individually using
"@wl-base-" variables: xs, sm, md, lg and xl, or by default, setting a
base gutter with "@wl-base-gutter" variable, which automatically gets sized
proportionally.

{SIZES} = xs, sm, md, lg, xl

CLEARFIXES:          wl-cfix-{{SIZES}}
BORDER-RADIUS:       wl-br-{{SIZES}}
DISPLAY:             wl-ds-{block, inline, inline-block, none}
FLOATS:              wl-fl-{none, left, right}
MARGINS:             wl-ma-auto, wl-ma-{all, bottom, left, right, top}-{no, {SIZES}}
PADDINGS:            wl-pa-{all, bottom, left, right, top}-{SIZES}
POSITION:            wl-ps-{absolute, fixed, relative, static}
TEXT ALIGNMENTS:     wl-ta-{center, left, right, justify}
TEXT TRANSFORMS:     wl-tt-{uppercase, lowercase, capitalize}
VISIBILITY:          wl-vs-{visible, hidden}

Other useful helpers

CENTERDIV:           wl-centerdiv
FULLWIDTH:           wl-fullwidth

CHANGELOG
---------

05-07-2014
- First release

06-10-2015
- Created some new utility classes: text transforms, centerdiv, text alignments
- Removed fluid boxes for the moment, this is not a grid framework, just utilities
- Updated readme.md file
