# CBT607
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 607 is from Mike Rayborn and contains a version of        *   FILE 607
//*           IND$FILE which can legally be run on Hercules or      *   FILE 607
//*           on any other MVS system.  This version does not       *   FILE 607
//*           belong to IBM or to a vendor.                         *   FILE 607
//*                                                                 *   FILE 607
//*           Load modules for the IND$FILE module and the code     *   FILE 607
//*           page modules are supplied, as well as source code     *   FILE 607
//*           for the code page modules.                            *   FILE 607
//*                                                                 *   FILE 607
//*           Particulars and restrictions for this version of      *   FILE 607
//*           IND$FILE may be seen in the $$README member.          *   FILE 607
//*                                                                 *   FILE 607
//*           email:  mrayborn@bellsouth.net                        *   FILE 607
//*                                                                 *   FILE 607
//*      This release of IND$FILE uses external code page load      *   FILE 607
//*      modules.                                                   *   FILE 607
//*                                                                 *   FILE 607
//*      The default code page module is CDPG1047 and is            *   FILE 607
//*      included as a load module with the IND$FILE loadlib.  In   *   FILE 607
//*      this archive you will find the assembler source CDPG1047   *   FILE 607
//*      which is a job with the source suppied.                    *   FILE 607
//*                                                                 *   FILE 607
//*      Other code pages can be developed by cloning the           *   FILE 607
//*      CDPG1047 source to create other code page load modules.    *   FILE 607
//*      These can then be loaded by IND$FILE by supplying          *   FILE 607
//*      additional parms for the file transfer.                    *   FILE 607
//*                                                                 *   FILE 607
//*      IND$FILE GET host.file.name ASCII CRLF CODEPAGE CDPG1047   *   FILE 607
//*         or                                                      *   FILE 607
//*      IND$FILE GET host.file.name ASCII CRLF CDPG CDPG1047       *   FILE 607
//*                                                                 *   FILE 607
//*      If the transfer request does not include the ASCII         *   FILE 607
//*      parameter, then no external code page module will be       *   FILE 607
//*      loaded as binary transfers don't use translation           *   FILE 607
//*      tables.                                                    *   FILE 607
//*                                                                 *   FILE 607
//*      If you have questions just drop me a line at               *   FILE 607
//*      mrayborn@bellsouth.net                                     *   FILE 607
//*                                                                 *   FILE 607
//*      -- Mike                                                    *   FILE 607
//*                                                                 *   FILE 607
```
