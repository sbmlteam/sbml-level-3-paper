SBML Level 3 Paper submitted 2020<img width="14%" align="right" src=".graphics/sbml-badge.svg">
=================================

Source files for the paper on SBML Level&nbsp;3 submitted to _Molecular Systems Biology_ in 2020.


Table of contents
-----------------

* [Introduction](#introduction)
* [Installation](#installation)
* [Getting help](#getting-help)
* [License](#license)
* [Acknowledgments](#authors-and-acknowledgments)


Introduction
------------

This repository contains (as submodules) components of a paper on SBML Level&nbsp;3 submitted to _Molecular Systems Biology_ in 2020.  The paper was developed by the authors on Overleaf, and once submitted, a copy of the git repository from Overleaf was put on GitHub (in [sbml-level-3-overleaf](https://github.com/sbmlteam/sbml-level-3-paper-overleaf)).  The response to the reviewer comments was made a separate document in [sbml-level-3-paper-response-letter](https://github.com/sbmlteam/sbml-level-3-paper-response-letter) and our response to reviewers included `latexdiff` output comparing the version that reviewers saw and the revised version, in [sbml-level-3-paper-diff](https://github.com/sbmlteam/sbml-level-3-paper-diff).  Note that these repositories are installed here as git submodules.  To download everything, you need to use the `--recursive` option to the `git clone` command.

The subdirectory [submitted-files](submitted-files) contains copies of the files uploaded as part of the journal submission.  The source files (`.tex`, `.cls`, etc.) are copies of the files created from the sources in the repositories mentioned above.  Sometimes the files were renamed to make their purpose more clear in the collection of files uploaded via the journal website.  For example, [submitted-files/draft-style.cls](submitted-files/draft-style.cls) is identical to [sbml-paper.cls](https://github.com/sbmlteam/sbml-level-3-paper-overleaf/blob/master/sbml-paper.cls) in the original manuscript repository, but renamed during submission because it made the role of the file more clear in the journal upload web interface.


Installation
------------

 To download everything, you need to use the `--recursive` option to the `git clone` command.


Getting help
------------

If you find an issue, please submit it in [the GitHub issue tracker](https://github.com/sbmlteam/sbml-level-3-paper/issues) for this repository.  Alternatively, you are welcome to contact the author or the SBML Team [via email](mailto:sbml-team@googlegroups.com) with questions about this repository.


License
-------

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img align="right" alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a>

The [LaTeX](https://www.latex-project.org) code and associated support files in this repository are freely available under the [Creative Commons Attribution License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/), the same terms as for papers published in Molecular Systems Biology.  A copy of the license is available in the file named [LICENSE](LICENSE).


Acknowledgments
---------------

Funding for this and other SBML work has come from the [National Institute of General Medical Sciences](https://www.nigms.nih.gov) via grant NIH R01&nbsp;GM070923 (Principal Investigator: Michael Hucka).

<br>
<div align="center">
  <a href="https://www.nigms.nih.gov">
    <img valign="middle"  height="100" src=".graphics/US-NIH-NIGMS-Logo.svg">
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.caltech.edu">
    <img valign="middle" height="130" src=".graphics/caltech-round.png">
  </a>
</div>
