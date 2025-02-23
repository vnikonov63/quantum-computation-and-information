To convert a `.tex` file into `.html` file so it is easier to view the latex in the browser use `pandoc` with the `pandoc main.tex --mathjax -s -o index.html` command.

To convert a `.tex` file into `.pdf` use `pdflatex -output-directory=build main.tex` using s separate build directory, so auxilarry files do not clutter the main directory, the output file is in that directory as well.
