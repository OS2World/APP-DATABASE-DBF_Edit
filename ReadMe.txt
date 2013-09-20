DBF_edit edits dBASE files (.dbf) in ways that are not normally supported or are exceptionally difficult to accomplish using most database programs.  Fields (i.e. columns) may be copied, renamed, moved, deleted, and redefined.  "Magic" operations, which perform tasks defined by the programmer, are also available.  In this release these include parsing of an input field using either a string or a position and conversion of U.S.G.S. DLG attributes stored as FIPS codes to state and county names.  Programmers with access to VisProRexx can add more such Magic routines.  .DBF files may also be exported in a form that is readily edited by a REXX program.  The same format may also be imported to create a .DBF file.

Installation: 

The program is written in REXX, therefore you must have a REXX interpreter on your system.  There are several .DLLs used by DBF_edit.  I suggest you place them in the OS2/APPS/DLL directory.  They need to be somewhere along your libpath.  Place DBF_edit.exe and DBF_edit.hlp in a directory together.  If executed from that directory the program will be able to find the help.

I have included the shareware version of REXXBase.dll and the source zip file.  If you do not have the licensed version you should rename REXXBASE.DLL.Nagger to REXXBase.dll and place with the other .DLLs.  If you use the DBF_edit a lot and want to buy a copy of the licensed DLL you will find the contant information in the documentation.  If you do attempt to buy it please tell them that you are using it with DBF_edit, written by Doug Rickman of NASA.


Copyright:
You are free to use and modify the program.  Please give credit where credit is due.

Doug Rickman

Change History
 
 July 11, 2000 
    1. First release. 


P.S. If you find DBF_edit useful please drop me a line and let me know.  I built it to solve a type of problem that has bothered me for years.  Maybe it will help others.