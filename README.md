# Bibtex2html

Bibtex2html reads a BibTeX file and converts it to a list of references in HTML format.

## File description

* `bibtex2html.py`: the bibtex2html program
* `example.bib`: example of BibTeX file
* `template.html`: example of template file

## Usage

To run the program, execute the following command:

    python bibtex2html.py example.bib template.html output.html

Here, `bibtex.bib` is the BibTeX file that you want to convert and `template.html` is any template file containing the following placeholders:

    <!--NUMBER_OF_REFERENCES-->
    <!--NEWER-->
    <!--OLDER-->
    <!--DATE-->
    <!--LIST_OF_REFERENCES-->

The placeholders will be replaced by the program, and the result will be written to the file `output.html`.

Alternatively, the following command prints the resulting HTML code to the standard output:

    python bibtex2html.py example.bib template.html

## References

* https://www.bibtex.com/g/bibtex-format/

## Todo

* Add support to plain numbers not inclosed in { } or " ".

## Changelog

* Add support to case insensitive field names.
* Add support to field names inclosed in " " in addition to { } (thanks to Ümit Sözbilir).

## License

Copyright (C) 2009-2022 Gustavo de Oliveira. Licensed under the [GNU GPLv2](LICENSE).
