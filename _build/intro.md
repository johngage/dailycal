---
title: 'Home'
prev_page:
  url: 
  title: ''
next_page:
  url: https://github.com/jupyter/jupyter-book
  title: 'GitHub repository'
comment: "***PROGRAMMATICALLY GENERATED, DO NOT EDIT. SEE ORIGINAL FILES IN /content***"
---
# Books with Jupyter and Jekyll

<img src="https://circleci.com/gh/jupyter/jupyter-book.svg?style=svg" class="left">

Jupyter Books lets you build an online book using a collection of Jupyter Notebooks
and Markdown files, adding extra functionality for people running a Jupyter stack.

Key innovations from University of California, Berkeley are transforming scientific research, data analysis, and publishing.

Jupyter Notebooks were created by Fernando Pérez, UCB Statistics and Berkeley Institite of Data Science.
Here is a 2019 video of Pérez explaining the origins of repeatable data analysis, using a Berkeley-developed geophysics example, Pangeo.

The famous Berkeley course, [Data Science 8]() was created three years ago in a remarkable collaboration among several Berkeley departments, including Computer Science, Statistics, Public Policy, Physics, Astronomy, City Planning, and others.

This week, the new [Data Science Division](https://campustechnology.com/articles/2018/11/29/berkeley-setting-up-division-to-build-on-data-sciences-momentum.aspx) found its [new permanent Dean, Jennifer Chayes](https://bsa.berkeley.edu/news/announcement-associate-provost-division-data-science-and-information-and-dean-school) who also assumes the new Associate Provost for the Division of Data Science position: 

In Spring, 2019, over two thousand students took Data Science 8, and over one thousand took the sequential course, Data Science 100.

For an example of a book built with Jupyter Books, see the [textbook for Data 100](https://www.textbook.ds100.org/) at UC Berkeley.

Here are a few features of Jupyter Books

* All course content is written in markdown and Jupyter Notebooks, stored in `notebooks/`
* The Jupyter Book repo comes packaged with helper scripts to convert these into Jekyll pages (in `scripts/`) that can be hosted for free on GitHub
* Pages can have [Binder](https://mybinder.org) or JupyterHub links automatically added for interactivity.
* The website itself is based on Jekyll, and is highly extensible and can be freely-hosted on GitHub.
* There are lots of nifty HTML features under-the-hood, such as Turbolinks fast-navigation and
  click-to-copy in code cells.

## Getting started

To get started, you may be interested in the following links.
Here are a few links of interest:

* **[Quickstart](features/features)** is a quick demo and overview of Jupyter Books.

* **[The Jupyter Book Guide](guide/01_overview)**
  will step you through the process of configuring and building your own Jupyter Book.

* **[The Jupyter Book template repo](https://github.com/jupyter/jupyter-book)** is the template
  repository you'll use as a start for your Jupyter Book.

* **A demo of the Jupyter Book** can be browsed via the sidebar to the left.

## Installation

Here's a brief rundown of how to create your own Jupyter Book using this site. For a more
complete guide, see [the Jupyter Book guide](guide/01_overview).

* Fork the Jupyter Book template repo
* Replace the demo notebooks in `content/` with your own notebooks and markdown files.
* Create a Table of Contents yaml file by editing `_data/toc.yaml`.
* Generate the Jekyll markdown for your notebooks by running `scripts/generate_book.py`
* Push your changes to GitHub (or wherever you host your site)!

## Acknowledgements

Jupyter Books was originally created by [Sam Lau][sam] and [Chris Holdgraf][chris]
with support of the **UC Berkeley Data Science Education Program and the Berkeley
Institute for Data Science**.

[sam]: http://www.samlau.me/
[chris]: https://predictablynoisy.com
