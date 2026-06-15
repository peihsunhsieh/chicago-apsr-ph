# chicago-apsr-ph

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

This repository provides a BibTeX `.bst` file for the APSA/APSR citation style. The file is adapted from [the official APSR submission template on Overleaf](https://www.overleaf.com/latex/templates/apsr-american-political-science-review-submission-template/fxffppspqczt) and modifies the template to better match APSA/APSR citation conventions.

## What this style changes

Compared with the original APSR Overleaf template, this `.bst` file makes the following changes:

1. Uses *et al.* only when there are four or more authors.
2. Uses a serial comma before *and* when there are three authors.
3. Omits publication months from reference-list entries.
4. Places the final period of article titles inside quotation marks when the title does not already end with punctuation.

For example, an article title is formatted as:

> Ostrom, Elinor. 1998. “A Behavioral Approach to the Rational Choice Theory of Collective Action: Presidential Address, American Political Science Association, 1997.” *American Political Science Review* 92 (1): 1–22.

rather than:

> Ostrom, Elinor. 1998, March. “A Behavioral Approach to the Rational Choice Theory of Collective Action: Presidential Address, American Political Science Association, 1997”. American Political Science Review 92 (1): 1–22.

## Usage

Put `chicago-apsr-ph.bst` in the same directory as your `.tex` file.

Add the following lines before `\begin{document}`:

```latex
\usepackage{natbib}
\setcitestyle{aysep={}} % Removes the comma between author and year
```

Then add the following lines where you want the reference list to appear:

```latex
\bibliographystyle{chicago-apsr-ph}
\bibliography{your-bib-file-name}
```

Replace `your-bib-file-name` with the name of your `.bib` file, without the `.bib` extension.

## Source

This style is adapted from the [*APSR: American Political Science Review Submission Template*](https://www.overleaf.com/latex/templates/apsr-american-political-science-review-submission-template/fxffppspqczt) and revised to better align with APSA’s [*Style Manual for Political Science*](https://spu.libguides.com/ld.php?content_id=47605571).


## License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
