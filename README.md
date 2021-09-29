# Bibtex2html

Reads a BibTeX file and converts it to a list of references in HTML format.

## File description

* `bibtex2html.py`: the bibtex2html program
* `example.bib`: example of BibTeX file
* `template.html`: example of template file

## Usage

To run the program, execute the following command in a terminal:

    python bibtex2html.py example.bib template.html output.html

Here, `bibtex.bib` is the BibTeX file that you want to convert and `template.html` is any template file containing the following placeholders:

    <!--NUMBER_OF_REFERENCES-->
    <!--NEWER-->
    <!--OLDER-->
    <!--DATE-->
    <!--LIST_OF_REFERENCES-->

These placeholders will be replaced by the program, and the result will be written to the file `output.html`.

Alternatively, the following command prints the resulting HTML code to the standard output:

    python bibtex2html.py example.bib template.html

## License

Copyright (C) 2009-2021 Gustavo de Oliveira. Licensed under the [GNU GPLv2](LICENSE).
