ue-phd-thesis
=============

This a LaTeX template for a PhD thesis at the University of Edinburgh. When I was writing my thesis, I adapted it from http://www.geos.ed.ac.uk/it/FAQ/latexThesis.html and am extending it here with more documentation and examples. Also, I changed it to build with pdflatex (instead of latex).

Contents
=============
* Settings in line with university requirements (check whether your department needs anything exotic)
* UE title page with university crest
* Declaration of originality
* Typical structure (Acknowledgments, ToC, ...)
* Complete ToC with six chapters plus appendix
* Sample for list of Tables and Figures
* Sample for acronyms
* Sample for nomenclature (list of symobls)
* Samples of figure, equation, subequations and algorithms in main body
* Two separately indexed bibliographies (one for own publications, one for literature)
* PDF inclusion in appendix

Notes
=========
* I have left only text snippets. Yet, the output is already 57 pages. Imagine doing that in MS word...
* I used Kile on Ubuntu to write it. But any tool should do.
* The original README from Magnus Hagdorn is included as README.orig.
* I used JabRef to maintain my references.
* Use ed_thesis.tex to build a pdf for paper submission with 1.5 line spacing.
* Use nicepdfthesis.tex to build a pdf with hyperlinks.
* The cascaded chapter folder structure is on purpose. It enables building individual chapters standalone.

General advice
=============
* Set up your Table of Contents first. Fill each section with two lines of content summary. Grow the document from there.
* Leave minor layout fixes until the end. Then resize figures, arrange page breaks with `\vfill`, etc.
* Force yourself to get used to defining acronyms, nomenclature, urls, labels, etc the moment you mention them. It saves a lot of time later.
* Generate and store all your graphical elements as eps and pdf. This keeps you flexible with regard to a latex or pdflatex build.
* Use packages, not workarounds

Feedback
================
I hope this gets you started more quickly than me. My final compiled thesis is available as a sample output [here](http://www.holtka.mp). Contact me at h.holtkamp@gmail.com

I was made aware of an alternative Edinburgh University PhD template. Check it out at: https://www.wiki.ed.ac.uk/display/iesscicomp/Engineering+Latex+Thesis+Template
