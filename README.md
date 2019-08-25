# equations

## Usage

1. Edit the template `eq.tex` so that it contains the equation you want to render. The part to be changed is between `\pagestyle{empty}` and `\end{document}`.

2. Call `mkeq` with a name for the equation as an argument, e.g.:

    `./mkeq distributivvgesetz`

3. Use the rendered equation with the respective name in either the `PDF`or the `SVG` subdirectory.

## Requirements

+ `pdflatex`
+ `pdfcrop`
+ `pdf2svg`
