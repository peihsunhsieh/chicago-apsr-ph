# chicago-apsr-ph

This is the BibTex .bst file for the APSR citation style. The .bst file is adapted from [the official APSR template on Overleaf](https://www.overleaf.com/latex/templates/apsr-american-political-science-review-submission-template/fxffppspqczt) and corrected two inconsistencies regarding in-text citations between the templates and the official guidelines.

1. Using *et al.* only when there are four or more authors.
2. Adding a comma between *and* and the third author when there are third authors.

To use this citation style, put this .bst in the same directory with the .tex file, and insert the following code before `\begin{document}`
```
\usepackage{natbib}
\setcitestyle{aysep={}} %No comma between authors and years
```

Also insert the following code where you want to put references
```
\bibliographystyle{chicago-apsr-ph}
\bibliography{} # your .bib file name in the curly brackets

```
<br/>
<br/>
<br/>

* *APSR - American Political Science Review Submission Template* [https://www.overleaf.com/latex/templates/apsr-american-political-science-review-submission-template/fxffppspqczt](https://www.overleaf.com/latex/templates/apsr-american-political-science-review-submission-template/fxffppspqczt)
<br/>
<br/>  
<br/>
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>
