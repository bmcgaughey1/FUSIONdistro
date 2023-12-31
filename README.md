# FUSION distribution repository
This repository provides an alternative download location for the FUSION/LDV lidar data visualization and analysis software. The primary
download site for FUSION is [here](http://forsys.sefs.uw.edu/fusion/fusionlatest.html).

There is a separate, FUSION-related, repository containing scripts for use with FUSION's AreaProcessor tool 
[here](https://github.com/bmcgaughey1/FUSIONscripts).

FUSION is distributed in two forms. The first (fusionlatest.exe) is a very simple installer that does not modify the windows registry or copy
files to system folders. This installer drives IT folks crazy because it does not follow most of the "normal" installation
procedures and does not register an uninstaller. The second (fusionlatest.zip) is a simple archive with all of the executables and documentation
that can be unzipped into any folder. This option is useful on some systems where administrators prevent installation of new software 
packages. 

To install FUSION, click one of the files mentioned in the previous paragraph. This should present you with a message that GitHub can't
show you files this large. Click the download icon at the upper right part of the screen and save the file to your local computer. Then either
run the installer (fusionlatest.exe) or unzip the archive (fusionlatest.zip) to install FUSION.

General information regarding FUSION is available [here](http://forsys.sefs.uw.edu/fusion/fusion_overview.html).

Example data for use with FUSION is available [here](http://forsys.sefs.uw.edu/fusion/fusionlatest.html).

FUSION (V3.40+) supports reading and writing of compressed LAS data files by linking to Martin Isenburg's LASzip.dll and LASzip64.dll 
libraries. To take advantage of this capability, you need to install LAStools and manually copy the LASzip.dll and LASzip64.dll files into 
FUSION's install folder.

LAStools can be found [here](https://rapidlasso.de/product-overview/) or [here](http://lastools.org/).



FUSION is developed at the US Department of Agriculture, Forest Service, Pacific Northwest Research Station by an employee of the Federal 
Government in the course of his official duties. Pursuant to Title 17, Section 105 of the United States Code, this software is not subject to 
copyright protection and is in the public domain. FUSION is primarily a research tool. USDA Forest Service assumes no responsibility whatsoever 
for its use by other parties, and makes no guarantees, expressed or implied, about its quality, reliability, or any other characteristic.
