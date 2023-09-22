FUSION 4.40
A few bug fixes and somewhat major changes regarding the logic used when working with DTM files with gaps between adjacent tiles and surface models with different resolutions.
Logic changes related to grid alignment when coordinates have negative values that only affect operations where X or Y values are negative.
Changes to "fix" problems using wildcards to specify files to command line problems. Windows expands wildcard searches like *.las to include files
with .lasx extension. This behavior has long caused problems. New logic has been added to all programs that use point data to drop non point files
from the set of input files built using the wildcard specifier.

Version 4.30 Changes
Version 4.30 includes a major bug fix for the GridMetrics program. Several of the intensity metrics were being computed incorrectly when 
the /strata option was used. Namely the L-moment and percentile metrics. All intensity metrics were correct when the /strata option was 
not used on the command line. It also includes a minor fix to the LDV viewer that may affect some users.

***All users should update their version of FUSION.

Version 4.21 Changes
This is a minor update that fixes a couple of bugs and updates the FUSION installer to default to the c:\Programs Files\FUSION folder for
installation.

Version 4.20 Changes
This release fixes some major problems for all programs that write LAS/LAZ files. Basically everything worked if input files all used the same
version of the LAS format but when inputs included files of different versions, most tools that write LAS/LAZ files failed. The problem was
related to a mismatch in the version number and header size for the output file.

Version 4.10 Changes
This release fixes a couple of bugs related to TreeSeg, PolyClipData, and ReturnDensity. It also improves the logic used to interpolate
elevations from ground models for all programs. This latter problem was causing some really long execution times in certain situations
so I wanted to push the release out rather than wait for additional changes.

Version 4.00 Changes
This release has been delayed for far too long due to some technical issues and lack of time to do thorough testing of the 64-bit versions
of programs. Major changes to most programs as part of the development of 64-bit versions of command line tools. All code migrated to a 
new development environment (MS visual studio 2017). This necessitated several changes to code and provided an opportunity to make a few 
other changes that  have been on hold for a long time. All of the command line tools will shift to their 64-bit version if the environment 
variable FUSION64 is set to any value. Refer to the FUSION manual for more details.

The primary FUSION website is:
http://forsys.sefs.uw.edu/fusion.html

The latest version of FUSION is always available at:
http://forsys.sefs.uw.edu/fusion/fusionlatest.html

You can check for newer versions of FUSION by accessing the Help…About menu option in FUSION and 
clicking the button labeled “Check for a newer version of FUSION”. This action will open a web page on 
the FUSION server that will indicate if the version of FUSION you have is the “latest version” and provide 
a link to the latest version of both the FUSION software and the manual.

I hope you find the software interesting and useful.  If you have questions or need assistance, call or 
email me.


Bob McGaughey
RESEARCH FORESTER
USDA Forest Service
University of Washington
PO Box 352100
Seattle, WA  98195-2100
(206) 543-4713 (not currently at this number due to COVID restrictions)
robert.mcgaughey@usda.gov
