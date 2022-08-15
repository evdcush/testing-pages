################
GH Pages Sandbox
################
Playing around with GH pages and SSGs 

.. contents::
.. section-numbering::


Jupyter Book
############

=====
Setup
=====
Reference: https://jupyterbook.org/en/stable/start/overview.html

Initialize
==========
Run ``jupyter-book jupybook``.

It will now create a dir ``jupybook``, with the following contents::

    $ tree jupybook
    jupybook
    ├── _config.yml
    ├── intro.md
    ├── logo.png
    ├── markdown.md
    ├── markdown-notebooks.md
    ├── notebooks.ipynb
    ├── references.bib
    ├── requirements.txt
    └── _toc.yml

**The essential/required pieces are:** ``_toc.yml`` and ``_config.yml``.
