========================================================================
questiontex --- write multiple-choice tests in LaTeX
E-mail: echo@math.ethz.ch
Released under the LaTeX Project Public License v1.3c or later
See http://www.latex-project.org/lppl.txt
========================================================================

I. OVERVIEW

The questiontex package contains a collection of LaTeX macros for writing
multiple choice tests. The LaTeX sources can be processed by 'latex' in
order to produce a printer's copy and standard solution.
Interactive versions are obtained through import into the Moodle Learning
Management System via a dedicated plugin or through in-house software
for classroom assessment tests developed at ETH Zurich.

========================================================================

II. INSTALLATION REQUIREMENTS

A LaTeX distribution supporting the 'pdftex' and 'pdflatex' commands.

========================================================================

III. INSTALLATION AND GETTING STARTED

 A) Produce questiontex.sty
      pdftex questiontex.dtx

 B) Typeset documentation
      pdflatex questiontex.dtx

 C) Typeset example test
      pdflatex example.tex

 D) Add questiontex package to your TeX distribution (optional)
    by copying the questiontex folder into
      <tex-root-directory>/texmf/tex/latex

========================================================================

IV. CONTACT

This software was written in the projects LEMUREN and nemesis at the
department of mathematics of ETH Zurich. For further information, please
contact echo@ethz.ch.

