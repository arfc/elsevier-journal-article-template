# journal-article-template
=======

This repository contains a template for journal
articles published by Elsevier. This template
repository is largely derived from the github
repository for the paper "Synergistic Spent Nuclear
Fuel Dynamics Within the European Union" by Bae et
al., and initialized from that repository to preserve
the original git and contribution histories.

# Outline
The top-level directory should contain all TeX files for
the journal article itself.

The `graph-abs` directory holds all files for the
graphical abstract.

The `highlights` directory holds all files for the
3-5 bullet point highlights.

The `letter` directory holds all files for the cover
letter to the journal editor and reviewers.

The `revise` directory holds all files for revision
comments and the corresponding edits. Each new round
of revisions should be covered in a separate TeX
file.

# To review
The ``elsarticle`` format comes with convenient options for viewing.
To view the article in a "review" format, modify the first line of the
``main.tex`` file so that it reads

``\documentclass[review]{elsarticle}``

To view the article in a "final print" format, modify the first line of
``main.tex`` file so that it reads

``\documentclass[3p, twocolumn]{elsarticle}``

``elsarticle`` supports other formats that can be read about
[here](https://www.elsevier.com/__data/assets/pdf_file/0008/56843/elsdoc-1.pdf)

# To compile
Run `make` after making appropriate edits to the
`main.tex` file and adding content to other tex files as needed.
