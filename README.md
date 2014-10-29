Stallings' Folding Process is Inherently Sequential
===================================================

This file was last updated on 29 October 2014.

Downloading
-----------

This paper can be found at https://github.com/jfinkels/stallings.

To download the paper using [Git][1], run

    git clone git@github.com:jfinkels/stallings.git

A somewhat recent version of this work should be available at
https://cs-people.bu.edu/jeffreyf#stallings, but I can't guarantee that it will
always be up to date, since I compile and upload it manually.

[1]: http://git-scm.com

Compilation dependencies
------------------------

This document requires `pdflatex` to compile and `biber` for bibliography
management. The complete list of LaTeX packages required to compile this
document can be found at the head of the file `stallings.tex`.

To install the necessary packages on Ubuntu, run

    sudo apt-get install texlive-base texlive-latex-base texlive-latex-extra \
      texlive-science biber

Unfortunately, the LaTeX package [`tkz-graph`][2] must be installed manually.
The simplest solution to this problem is to download the file and place it in
the same directory as the document to compile.

[2]: http://www.ctan.org/pkg/tkz-graph

Compiling
---------

To compile the document, run

    pdflatex stallings
    biber stallings
    pdflatex stallings

The output is `stallings.pdf`, and can be viewed with any PDF reader.

Copyright
---------

Copyright 2012, 2013, 2014 Jeffrey Finkelstein.

Both the LaTeX markup and the compiled document are made available under the
terms of the Creative Commons Attribution-ShareAlike 4.0 International License,
https://creativecommons.org/licenses/by-sa/4.0/.

Contact
-------

Jeffrey Finkelstein <jeffrey.finkelstein@gmail.com>
