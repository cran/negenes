
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

  Binaries are available for Windows and MacOS; source code is
  available for Unix.


INSTALLATION OF R AND R/NEGENES (Windows)

  1. The Windows version of R is distributed as a single file,
     SetupR.exe.  Install R by executing this file.  We recommend
     installing R in "c:\R" rather than "c:\Program Files\R".  Why
     didn't Microsoft use "Programs" rather than "Program files"?

  2. To install the R/negenes, you may do one of the following:

     a. Start R.  Select (on the menu bar) "Packages" and then
        "Install package from local zip file...".  File the file
        "negenes.zip" on your hard drive, and click "Open."

     b. Unzip the "negenes.zip" file into the directory $RHOME\library
        (where $RHOME is something like c:\R\rw1041).  Note that this
        should create a directory $RHOME\library\negenes containing the R
        source code and the compiled dll.

        Start R and type "link.html.help()" to get the help files for
        the negenes package added to the help indices.


INSTALLATION OF R AND R/NEGENES (MacOS)

  1. We recommend downloading the "Carbon" version of R.  It may be
     somewhat slower, but it doesn't require the installation of
     X-windows.  (At CRAN, download the version that is *not*
     indicated "Darwin/X11".)

     a. Download the file rm150.sit file (or the equivalent for the
        most recent version of R).

     b. Use Stuffit Exaander to expand the file, to create a folder
        "rm150". 

     c. Copy the folder that is created to your Applications folder.

     d. Execute R by double clicking on the R icon within the "rm150"
        folder. 

  2. To install R/negenes:

     a. Download the file negenes_*.sit

     b. Expand the file using Stuffit Expander, creating a folder
       "negenes". 

     c. Copy the "negenes" folder to "rm150/library".

     d. Open R and update the links to the help files by either:

         i. Click (on the menu bar) Help -> Link Packages Help

        ii. Type link.html.help()


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
        appropriate director).  

        Create a file ~/.Renviron containing the line

            R_LIBS=/home/auser/Rlibs

        so that R will know to search for packages in that directory.


GETTING STARTED

  Once you start R, you'll need to type "library(negenes)" to load the
  package.  You can create a file "~/.Rprofile" or "c:\.Rprofile"
  containing R code to be run whenever you start R.  If you use the
  R/negenes package regularly, you should place the line
  "library(negenes)" in such a file.

  Efficient use of the R/negenes package requires considerable
  knowledge of the R language.  Learning R may require a formidable
  investment of time, but it will definitely be worth the effort.
  Numerous free documents on getting started with R are available on
  CRAN (http://cran.r-project.org).  In additional, several books are
  available on S/S-PLUS, which is very similar to R.  For example, see
  WN Venables, BD Ripley (1999) Modern Applied Statistics with S-PLUS,
  3rd edition. Springer.

  To get started with R/negenes, you might first peruse the documentation
  that is bundled with it.  Type help.start() to start the html
  version of the R help pages.  Then click "Packages" -> "negenes".  

  In Windows, you may gain access to the help documents by clicking
  "Help" in the menu bar and then "R language (html)".  Windows users
  may wish to place the line "options(htmlhelp=TRUE)" in the
  file "c:\.Rprofile".  


QUESTIONS/COMMENTS/CONCERNS

  If you have any questions, suggestions, problems or complaints
  regarding R/negenes, please email Karl Broman <kbroman@jhsph.edu>.
  
----------------------------------------------------------------------
end of README.txt
