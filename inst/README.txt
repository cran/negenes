
README file for the negenes package
----------------------------------------------------------------------
This explains the installation of the negenes package for R.  If you
have any problems with installation, send an email to Karl Broman
<kbroman@jhsph.edu>.
----------------------------------------------------------------------

OBTAINING R

  You can download R from the Comprehensive R Archive Network (CRAN).
  Visit http://cran.r-project.org or a local mirror (for example,
  http://cran.us.r-project.org).  Source code is available for Unix,
  and binaries are available for Windows, MacOS, and many versions of
  Linux.  


OBTAINING R/NEGENES

  You can obtain the latest version of R/negenes from 

      http://www.biostat.jhsph.edu/~kbroman/software/negenes.html

  Copies of R/negenes will also be placed on CRAN
  (cran.r-project.org), but the version at the above site will be
  updated more frequently.  Binaries are available for Windows and
  MacOS; source code is available for Unix.


INSTALLATION OF R AND R/NEGENES (Windows)

  1. The Windows version of R is distributed as a single file,
     with a name something like rw1081.exe.  Install R by executing
     this file.  We recommend installing R in "c:\R" rather than
     "c:\Program Files\R".  Why didn't Microsoft use "Programs" rather
     than "Program files"? 

  2. To install R/negenes, download the file "negenes_0.98-4.zip" (or
     the equivalent) and then do one of the following:

     a. Start R.  Select (on the menu bar) "Packages" and then
        "Install package from local zip file...".  Find the file
        "negenes_0.98-4.zip" on your hard drive, and click "Open".

     b. Unzip the "negenes_0.98-4.zip" file into the directory
        $RHOME\library (where $RHOME is something like c:\R\rw1081).
        Note that this should create a directory
        $RHOME\library\negenes containing the R source code and the
        compiled dll.

        Start R and type "link.html.help()" to get the help files for
        the negenes package added to the help indices.


INSTALLATION OF R AND R/NEGENES (MacOS version 10.2.x and above)

  1. Download the file RAqua.dmg and double-click it to mount a
     "drive" with a name something like "RAqua-1.8.1".  Follow the
     instructions in the file "ReadMe.txt".

  2. To install R/negenes:

     a. Download either the compiled version of R/negenes for Mac OSX
        or the source code.

     b. Start R by double-clicking "StartR" in your Applications
        folder. 

     c. From the menu bar, click Packages -> Install from local files
        and then either "Binary package file" or "Source package file".
        (To install from source, you may need additional compilers and
        other tools installed.)  Then find the appropriate file on
        your drive.


INSTALLATION OF R/NEGENES (Unix)

  1. We'll assume that R has already been installed. 

  2. Go into the directory containing the file "negenes_*.tar.gz".

  3. Do one of the following:

     a. To install R/negenes in the standard location
        (/usr/local/lib/R/library), type 

            R INSTALL negenes_*.tar.gz

        You'll probably need to be superuser.

     b. To install the package locally, type 

            R INSTALL --library=/home/auser/Rlibs negenes_*.tar.gz

        (where "/home/auser/Rlibs" should be replaced with the
        appropriate directory).  

        Create a file ~/.Renviron containing the line

            R_LIBS=/home/auser/Rlibs

        so that R will know to search for packages in that directory.


GETTING STARTED

  Once you start R, you'll need to type "library(negenes)" to load the
  package.  You can create a file "~/.Rprofile" (Unix or MacOS) or
  "c:\.Rprofile" (Windows) containing R code to be run whenever you
  start R.  If you use the R/negenes package regularly, you should
  place the line "library(negenes)" in such a file.

  To get started with R/negenes, you might first peruse the
  documentation that is bundled with it.  Type help.start() to start
  the html version of the R help pages.  Then click "Packages" ->
  "negenes".

  In Windows or MacOS, you may gain access to the help documents by
  clicking "Help" in the menu bar and then "R language (html)".  If
  you include "options(htmlhelp=TRUE)" in your .Rprofile file, use of
  the html version of the help pages will be automatic.


QUESTIONS/COMMENTS/CONCERNS

  If you have any questions, suggestions, problems or complaints
  regarding R/negenes, please email Karl Broman <kbroman@jhsph.edu>.
  
----------------------------------------------------------------------
end of README.txt
