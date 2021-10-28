# The cutwin package

The cutwin package enables you to create a window in a paragraph.
Facilities are provided to assist in putting text or a logo into the
space cutout.

https://github.com/latex-package-repositories/cutwin/issues

Changes in version 0.1 (2010/09/29)

* First public release

Changes in version 0.2 (2021/10/13)

* Allocate package specific registers replacing \@tempdimb and \@tempdimc

------------------------------------------------------------------
  Author: Peter Wilson (Herries Press) and Alan Hoenig  
  Copyright 2010 Peter R. Wilson
  
  Current Maintainer David Carlisle  
  Copyright 2021 Peter R. Wilson, David Carlisle

  This work may be distributed and/or modified under the
  conditions of the Latex Project Public License, either
  version 1.3 of this license or (at your option) any
  later version.
  The latest version of the license is in
    http://www.latex-project.org/lppl.txt
  and version 1.3 or later is part of all distributions of
  LaTeX version 2003/06/01 or later.

  This work has the LPPL maintenance status "maintained".

This work consists of the files:

    README (this file)  
    cutwin.dtx  
    cutwin.ins  
    cutwin.pdf  
	
and the derived file

    cutwin.sty

------------------------------------------------------------------

The distribution consists of the following files:

README (this file)  
cutwin.dtx  
cutwin.ins  
cutwin.pdf


##    To install the package:

* run: latex cutwin.ins (which will generate cutwin.sty)
*  Move cutwin.sty to a location where LaTeX will find it,
  for example /usr/TeX/texmf-local/tex/latex/cutwin/cutwin.sty
  (for more information on installation see the FAQ).

##   To generate a second copy of the manual
* run: (pdf)latex cutwin.dtx
* (for an index run: makeindex -s gind.ist cutwin.idx)
* run: (pdf)latex cutwin.dtx
* Print cutwin.dvi (or cutwin.pdf) for a hardcopy of the package manual



 
