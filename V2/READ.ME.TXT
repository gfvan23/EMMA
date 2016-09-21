G. Vannucci and P. Gasperini, A database of revised fault plane solutions for Italy and 
surrounding regions, Computers & Geosciences (2003).

The folder \EMMA includes the following files and folders:

EMMA2003.mde                   MS ACCESS 2003 database file
EMMA2000.mde                   MS ACCESS 2000 database file
EMMA97.mde                     MS ACCESS 97 database file
EMMA_tutorial.doc              Notes for the users (MS WORD file)
Italy.bat                      GMT (version 3.4 or later) batch file to plot
                               mechanisms
TOT_Database_SEL_CF_GMT_M.txt  Mechanism input file for GMT (ASCII file)
Italy.ps                       Mechanism plot (result of Italy.bat) (Postscript
                               file)
CMT.dek                        Harvard CMT catalog format example (ASCII file)
INGV.dek                       INGV RCMT catalog format example (ASCII file)
ETH.txt                        ETH RCMT catalog format example (ASCII file)

Folder \EMMA\bin
Convertk_cmt.exe               Program executable to convert from CMT.dek
                               to database import format
Convertk_ingv.exe              Program executable to convert from INGV.dek
                               to database import format
Convertk_eth.exe               Program executable to convert from ETH.txt to
                               database import format
                           
To install:

The folder \EMMA, in the attached CD-ROM, contains all the files needed to run 
the database application and in particular the database files for the three 
supported MS-Access versions (EMMA97.MDE, EMMA2000.MDE and EMMA2003.MDE) 
and a folder (\EMMA\bin) containing three executables 
(Convertk_cmt.exe, Convertk_eth.exe, Convertk_ingv.exe) used by the MS-Access 
application to convert, from original to import formats, 
the Harvard CMT, the ETH and the INGV RCMT catalogs.

To install the database please follow these steps: 

1)	Copy (drag-and-drop) the \EMMA folder from the CD-Rom 
        onto the hard disk.
2)	Select the folder with the right-hand mouse button, choose Properties 
        and then remove the Read-only attribute from \EMMA folder and from all 
        included files and folders.
3)	Copy the file GMTENV.BAT (usually located in the \SRC folder of GMT 
        package) to the \EMMA folder and rename it as SETPATH.BAT 
4)	Copy the Ghostscript executable (i.e. GSWIN32C.EXE) to the \EMMA folder 
        and rename it as GS.EXE 
5)	From the Start menu select Control Panels and then double click on 
        International. In the Numbers card, set decimal separator as “.” (dot), 
        thousands separator as “,” (comma) (default setting for English language
        systems) and 4 decimal digits (default is 2). Do the same settings in 
        the Currency card.
To run:

1)	Launch the database application (in \EMMA folder) by double clicking 
        the .MDE file corresponding to the MS-Access version installed on the 
        host computer (the unnecessary .MDE files can be deleted). 
2)	From the MS-Access Tools pop-up menu, select Option. In the General 
        card, set the Default Database Directory to the folder containing 
        the .MDE file (for example: C:\EMMA). 


For more information, please read the file EMMA_Tutorial.doc in the Folder \EMMA. 
Comments, suggestions, notices of malfunctioning are welcome to the authors' e-mail 
addresses:

gfranco@ibogfs.df.unibo.it
paolo@ibogfs.df.unibo.it

Disclaimer:
The software and the data are furnished freely as they are. The consequences of their use 
are completely under the responsibility of the user. Any warranty, either expressed
or implied is excluded. 
