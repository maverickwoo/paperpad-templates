# Introduction

The files in this directory define multiple types of ruled templates. Each
template is defined by the following files:

1. A main file named after the template, which defines the template parameters.

2. `printer-paper.tex`, which defines the parameters related to the production
   printer (e.g., unprintable margins) and the target paper dimensions (e.g., a4
   vs. letter, landscape vs. portrait).

3. `preamble.tex`, which sets up the document.

4. `body.tex`, which typesets the template into a one-page PDF.

The first two files contain all parameters intended for user configuration. The
remaining files are merely automation.
