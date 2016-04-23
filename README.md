# Frederiksberg beamer theme #

Morten Larsen created a nice beamer theme for the University of Copenhagen a few years ago. Unfortunately, link-rot seems to have crept in and the [original site](http://matdat.life.ku.dk/LaTeX/Frederiksberg) is unavailable since a view weeks. Hence, I just set up this repository to preserve his work for all future to come. All credit goes to Morten.

## Installation ##
The following instructions are copied from this [pdf](http://www.latexstudio.net/wp-content/uploads/2015/06/FrederiksbergUserGuide-2-2.pdf) file, which is also included in this repository. The "archived folder" in the following is the folder Frederiksberg in this repository.

To install the theme, you first need to dump the Frederiksberg directories with all their files in your local TEX file hierarchy:

1. The directory which in the install package is named tex/latex/beamer/Frederiksberg needs to be put where LATEX will find it.
2. The directory which in the install package is named dvips/Frederiksberg needs to be put where dvips will find it.

This should be achieved if you unpack the installation archive in the top directory of your local TEX installation (e.g. /usr/local/share/texmf/ on my Linux box, C:\localtexmf on my colleague’s Windows box with MikTeX, and /usr/local/gwTeX on the Mac I have access to). Then you must do whatever you need to do to have LATEX/dvips find the new files (e.g. run texhash on a Linux box; on a Windows MikTeX installation you start “MikTeX options” from your program menu and click the “Refresh now” button).
