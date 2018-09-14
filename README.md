# DuraChain White Paper
**Abstract:** Using an adapted version of the Matrix Spec, we present electronic health event environment implemented using distributed ledger technology. Such an environment will allow providers of durable medical equipment to more efficiently provide care to their patients and reduce delivery times for equipment. We also provide details about how electronic health events can be further developed so as to allow for use of our technology in all areas of healthcare delivery. With the right tool and proper deployment, electronic health events have the potential to radically transform the management of healthcare data.

**Keywords:** healthcare technology, durable medical equipment, distributed ledger technology, electronic health event, Matrix

This document was prepared using the LaTeX2e typesetting environment, produced by Leslie Lamport and the LaTeX3 team. It is free software based on the TeX system developed by Donald Knuth.

It relies on the `pdflatex` engine and `bibtex` for bibliopgraphy management. `.gitignore` excludes ancillary files like `.aux`, `.bbl`, `.log`, and others.

Additionally, a number of other packages were required to set the document you see here. The packages we used are all included in the 2018 release of TeXLive, which is distributed by the TeX Users Group. Please consult `wp.sty`, the file that provides the `whitepaper` document class, for more information on the packages we used.

## Installation Instructions
The DuraChain white paper is a living document and will be updated continuously as we continue to design, develop, and deploy our electronic health event environment.

This being the case, this repository is meant to serve up a hot, fresh PDF version of the white paper as it is modified.

There are several reasons why someone may choose to download the contents of this repository and/or compile the paper on their own. For those so inclined, the documentation that follows presents one of many paths that can be taken to realize this goal.

### TeXLive2018
TeXLive2018 is a library that contains all of the macros and packages used to compile this document. It may be possible to compile this document with previous TeXLive distributions, but we make no warranty to that.

If you have not already, download the TeXLive2018 distribution appropriate for your system and install it:
- macOS
- Linux
- Windows

It may be necessary to set the `PATH` for TeXLive.
- macOS
- Linux
- Windows

### Text Editor or LaTeX Client
You will also need a LaTeX client or a multipurpose text editor to interact with the contents of this repository.

If you're a bitch, you could also upload the contents of this repository to an online TeX editor like Overleaf v2.

#### Atom
We recommned Atom, a text editor made available by GitHub that can be configured and customized for a variety of purposes, including working with LaTeX files.

It is available for:
- macOS
- Linux
- Windows

#### Other clients and editors

### Configure Atom
A variety of packages are available for Atom that can enhance functionality and workflow.

Of particular note are:
- `language-text`, an Atom core package that supports plaintext and
- `atom-latex`, which makes it possible to run LaTeX engines and bibliography software without the use of the command line.

A number of other packages can improve the LaTeX experience when using Atom. These include:
- `language-latex`, which supports syntax highlighting;
- `latex-autocomplete`, which provides autofill options for LaTeX; and
- `latex-worcount`, which does a decent job at estiamting document word counts.
