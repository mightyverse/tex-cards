# Mightyverse LaTeX Card Generator

`ten-up.tex`

The printed version of the game uses the TypeKit font "Petalo Pro Bold"
To use it with this program, it needs to be copied from the [Adobe support directory](http://tex.stackexchange.com/questions/204386/adobe-typekit-fonts/280481#280481)

## How to Generate Cards

1. Download [TeXShop](http://pages.uoregon.edu/koch/texshop/)

### Print-and-Play Using Avery Business Card Templates

A. Open `ten-up.tex` and click "Typeset" button at top-right of the window,
   which generates cards that can be printed with [Avery® Business Cards][avery1].

B. To add your own phrases, modify `test-phrases.csv`


[avery1]: http://www.avery.com/avery/en_us/Products/Cards/Business-Cards/Laser-Business-Cards_05371.htm


### Print One Card Per Page

A. Open `single.tex` and click "Typeset" button at top-right of the window,
   which generates a PDF with one card per page.

B. To add your own phrases, modify `test-phrases.csv`

## FAQ

1. It looks wrong!  Why is the image offset in strange ways?  Sometimes LaTeX
needs you to execute it 2-3 times to get the layout to "settle down."  Just
try "Typeset" again a few times.
