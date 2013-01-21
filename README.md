# Bibtex2html

This program reads a bibtex file and convert it to a list of references
(articles, books etc.) in html format. To run it one needs a template file
containing the following fields:

    <!--NUMBER_OF_REFERENCES-->
    <!--NEWER-->
    <!--OLDER-->
    <!--DATE-->
    <!--LIST_OF_REFERENCES-->

These fields will be replaced by the program, and the result will be printed
out to the standard output.

To run this program type:

    python bibtex2html.py bibtex.bib template.html

or

    python bibtex2html.py bibtex.bib template.html > output.html

## License

Author: Copyright (C) 2009 Gustavo de Oliveira

License: GPL
