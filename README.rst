pandoc-talk
===========

A cookiecutter_ template for giving talks with pandoc and XeTeX.

.. _cookiecutter: https://github.com/audreyr/cookiecutter

Features
--------

- Nice Ubuntu fonts
- Useful Makefile
- Sensible .gitignore

Requirements
------------

The document is built using the Ubuntu_ and Inconsolata_ font families, and the Metropolis_ Beamer theme. You need to install it, or to remove it from header.tex and Makefile.

.. _Ubuntu: https://design.ubuntu.com/font
.. _Inconsolata: https://fonts.google.com/specimen/Inconsolata
.. _Metropolis: https://ctan.org/pkg/beamertheme-metropolis

Using this template
-------------------
::

    $ pip install cookiecutter
    $ cookiecutter https://github.com/arn-all/pandoc-talk.git

You will be asked about your basic info (name, title, etc.). This info will be used in your new talk. To specify multiple authors, directly modify the slides.md file header. Once you've made your template, you can build your talk with::

    $ make

You can generate a printable plain paper version of the slides using ::

    $ make report.pdf


License
-------
BSD licensed.

