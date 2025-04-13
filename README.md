# CBT198
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 198 IS FROM BOB BREAK OF ST. LOUIS, MISSOURI, AND IS A    *   FILE 198
//*           JES2 EXIT LOADER PROGRAM WHICH RUNS AS A JES2 EXIT 5  *   FILE 198
//*           ROUTINE.  THIS PROGRAM SHOULD ASSEMBLE AND RUN FOR    *   FILE 198
//*           ALL RELEASES OF JES2 FROM MVS/ESA RELEASE 3 THROUGH   *   FILE 198
//*           THE OS/390 RELEASES THROUGH AT LEAST RELEASE 2.5.     *   FILE 198
//*                                                                 *   FILE 198
//*           THIS EXIT ALLOWS SUBSTITUTION ON THE FLY, THROUGH     *   FILE 198
//*           A NEW JES2 COMMAND, OF A NEW VERSION OF ANY JES2      *   FILE 198
//*           EXIT, WITHOUT HAVING TO RECYCLE JES2 OR IPL THE       *   FILE 198
//*           MVS SYSTEM.  ALL TYPES OF JES2 EXITS ARE SUPPORTED:   *   FILE 198
//*           JES2 ADDRESS SPACE, CSA RESIDENT, LPA RESIDENT.       *   FILE 198
//*                                                                 *   FILE 198
//*           A new version in member CBTEX05, with some notes in   *   FILE 198
//*           member CBTEX05$, is for z/OS 1.7, and has just been   *   FILE 198
//*           added.                                                *   FILE 198
//*                                                                 *   FILE 198
//*           THERE ARE 4 VERSIONS OF THE EXIT IN THIS PDS, ONE     *   FILE 198
//*           IS THE ORIGINAL BY BOB BREAK, AND ONE WAS MODIFIED    *   FILE 198
//*           BY JACK SCHUDEL OF THE UNIVERSITY OF FLORIDA.  THE    *   FILE 198
//*           VERSION BY BOB BREAK REQUIRES THAT THE NEW LOAD       *   FILE 198
//*           MODULE BE IN AN APF AUTHORIZED LINKLIST LIBRARY,      *   FILE 198
//*           WHILE THE VERSION BY JACK SCHUDEL EASES THIS          *   FILE 198
//*           RESTRICTION SOMEWHAT.  BOTH ARE PRESENTED HERE.       *   FILE 198
//*                                                                 *   FILE 198
//*           A NEW VERSION BY YAIR ELHARRAR OF BAR-ILAN UNIVERSIY  *   FILE 198
//*           IN TEL-AVIV, ISRAEL, REQUIRES ONLY THAT THE NEW       *   FILE 198
//*           VERSION RESIDE IN AN AUTHORIZED STEPLIB.              *   FILE 198
//*                                                                 *   FILE 198
//*               CBTEX05   -  BOB BREAK'S VERSION  (z/OS 1.7)      *   FILE 198
//*               HASPEX05  -  BOB BREAK'S VERSION  (ORIGINAL)      *   FILE 198
//*               LOADEXIT  -  JACK SCHUDEL'S VERSION               *   FILE 198
//*                        (TAKEN FROM FILE 140 OF JES2 SHARE TAPE) *   FILE 198
//*               HASPEX5   -  YAIR ELHARRAR'S VERSION              *   FILE 198
//*                                                                 *   FILE 198
//*      THIS HASP EXIT 5 PROCESSES THE FOLLOWING INSTALLATION      *   FILE 198
//*      JES2 COMMANDS:                                             *   FILE 198
//*                                                                 *   FILE 198
//*      1. $REPEXIT - REPLACE A JES2 EXIT MODULE.  THE EXIT        *   FILE 198
//*                    ENVIRONMENT MAY BE "JES2", "SUBTASK",        *   FILE 198
//*                    "USER", OR "FSS".                            *   FILE 198
//*                                                                 *   FILE 198
//*      2. $ADDEXIT - ADD A JES2 EXIT MODULE.  THE EXIT            *   FILE 198
//*                    ENVIRONMENT MAY BE "JES2", "SUBTASK",        *   FILE 198
//*                    "USER", OR "FSS".                            *   FILE 198
//*                                                                 *   FILE 198
//*         AUTHOR                                                  *   FILE 198
//*         ------                                                  *   FILE 198
//*         BOB BREAK                                               *   FILE 198
//*         ST. LOUIS, MO.                                          *   FILE 198
//*         cb7485@momail.sbc.com                                   *   FILE 198
//*         bbreak@prodigy.net                                      *   FILE 198
//*         314-340-9301                                            *   FILE 198
//*         314-845-2018                                            *   FILE 198
//*                                                                 *   FILE 198
//*         JACK SCHUDEL'S EMAIL:  schudel@ufl.edu                  *   FILE 198
//*                                                                 *   FILE 198
//*         YAIR ELHARRAR'S EMAIL:  yair@ashur.cc.biu.ac.il         *   FILE 198
//*                                                                 *   FILE 198
```
