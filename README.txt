JaSTA - Java Superposition T-matrix App version 1.0.1 25/10/2013
---------------------------------------------------------------------
Optical properties of porous aggregate particles have been extensively studied through the use of various numerical techniques (viz. Superposition Transition Matrix (STM) code, Discrete Dipole Approximation (DDA) code etc.). The STM code, developed by Mackowski & Mishchenko, (1996, J. Opt. Soc. Am. A., 11, 1491),   is widely used by researchers to study the light scattering properties of cosmic dust aggregates.   This code is written in Fortran language.

Java Superposition T-matrix App (JaSTA) has been developed in the Department of Physics, Assam  University,  Silchar  (India)  to  study  the  light  scattering  properties  of  cosmic  dust  aggregates.  This  software package is based on Superposition  T-Matrix code   of D. Mackowski, K. Fuller & M. Mishchenko. JaSTA package consists  of a Graphical  User Interface  (GUI) in the front hand and a database  of related data in the backhand which can be updated periodically online.  Both the  interactive   GUI  and  database   package   directly  enables   user  to  model  by  self  monitoring   respective   input parameters   (viz.  wavelength,   complex  refractive   indices,  grain  size  parameter,   etc.)  to  study  the  related  optical properties (viz. extinction, polarization, etc.), of cosmic dust instantly, i.e. with zero computational time, which directly increases  the  efficiency  of  the  user.  The  database  of  different  optical  properties  of  the  cosmic  dust  aggregates  is generated  in a very wide range using STM code, with high computational  accuracy.  This package also has an option where users can compile and run the scattering code directly for aggregates in GUI environment.  The current version of this software  is developed  for Linux and Windows  platform  (both 32 and 64 bit) which will be extended  for other platform in future.

---------------------------------------------------------------------


This directory contains the 1.0.1 release of JaSTA (Java Superposition T-matrix App).

Please check the system-specific notes below for any caveats related to your operating system.

For general installation instructions, see the JaSTA Manual.

Downloading:
==============
JaSTA is available for download from the following URL:

http://ausastro.in/jasta.html


System Requirements:
====================
1. Java Runtime Enviroment (JRE)
2. Java3D (proper graphics driver must be installed; GLX Version-1.3 is required to run on linux for NVIDIA graphics and opengl or equivalent drivers for other graphics adaptors on linux).
3. gfortran (for Linux installation)
4. xterm (for Linux Workstation). 

Installing the Multi - OS package:
==================================
1. Download the jasta-1.0.1.tar.gz or jasta-1.0.1.zip file from the above link.
2. Untar or unzip the downloaded file in the user home directory, i.e. /home/<username>.

Running and executing the Multi - OS package:
=============================================
1. If the OS is Windows, then enter the JaSTA folder or directory and double click the jasta.jar file to run the program.
2. If the OS is Linux, then open terminal and enter the following commands to run JaSTA,
  		
		$: cd home/<username>/JaSTA
		$: chmod u+x JaSTA
		$: ./JaSTA 


Installing the Windows package:
===============================
1. Download the windows setup file from the link given above.
2. Double click the jasta-1.0.1-windows-x64-installer.exe or jasta-1.0.1-windows-x86-installation.exe
3. Click NEXT on the setup window.
4. Accept the LICENSE AGREEMENT.
5. Click NEXT to install.
6. The Software installs in the following directory:
	
	C:\JaSTA\

7. A desktop icon named 'JaSTA' is also created.

Running or executing the Windows package:
=========================================
1. Double click the desktop icon named 'JaSTA' to run the program.

Installing under Linux:
=======================
1. Download the linux setup file from the link given above.
2. Give execution permission to the setup file (e.g. $chmod u+x /<path-to-file>/<filename>)
3. Double click the jasta-1.0.1-linux-x64-installer.run or jasta-1.0.1-linux-x86-installation.run
4. Click NEXT on the setup window.
5. Accept the LICENSE AGREEMENT.
6. Click NEXT to install.
7. The Software installs in the following directory:
	
	$HOME/JaSTA/

8. A desktop icon named 'JaSTA' is also created.

Running or executing the Windows package:
=========================================
1. Double click the desktop icon named 'JaSTA' to run the program.


Working with JaSTA :
============================
The working instructions for JaSTA are presented in the JaSTA manual which is included in this package and also available for download from the following link,

  http://cpc.cs.qub.ac.uk/summaries/AETB_v1_0.html

Note:
==============================================
If the progress bar and the console window does not appear while runtime on linux OS, then install the JaSTA workstation version.
The workstation version uses xterm console to show the realtime update of the calculation process. Do not close the xterm window
during ongoing process of computations, otherwise the calculation will stop. 

Files included in the JaSTA package (Multi-OS):
==============================================
1.  csca			// precompiled executable file for csca.for (linux)
2.  nsphere1			// precompiled executable file for nsphere1.for (linux)
3.  csca.exe			// precompiled executable file for csca.for (Wndows)
4.  nsphere1.exe		// precompiled executable file for nsphere1.for (Windows)	
5.  JaSTA Manual.pdf		// manual for JaSTA.
6.  jasta.jar			// the executable file for JaSTA package (both Windows and Linux)
7.  chilkat.dll			// DLL file for extracting downloaded DATA_NET.rar during database update (Windows)
8.  libchilkat.so		// SO file for extracting downloaded DATA_NET.rar during database update
9.  j3dcore-ogl.dll		// DLL file for 3D visualization of the structure file (Windows)
10. libj3dcore-ogl.so		// SO file for 3D visualization of the structure file
11. csca.for			// fortran file to calculate the Cext,Csca,Cabs
12. JaSTA			// bash file to execute the JaSTA package either from desktop or from terminal
13. sctmdim.for			// dimension file that limits the maximum number of monomers to 128
14. DATA.IN			// it takes monomer size and number of monomers as input from the GUI for the csca.for file 
15. csca.out			// provides the output of the csca.for file
16. nsphere1.out		// provides the output of the nsphere1.for file
17. pol.out			// provides the required scattering matrix coefficients
18. sca.out			// provides the scattering elements
19. sca_final.out		// provides the normalized values of the scattering elements
20. test1.out			// output file 
21. hp_1.png			// image file used in the quick tutorial
22. hp_1a.png			// image file used in the quick tutorial
23. hp_2.png			// image file used in the quick tutorial
24. hp_2a.png			// image file used in the quick tutorial
25. hp_2b.png			// image file used in the quick tutorial	
26. hp_3a.png			// image file used in the quick tutorial	
27. hp_4a.png			// image file used in the quick tutorial
28. hp_5a.png			// image file used in the quick tutorial
29. hp_6a.png			// image file used in the quick tutorial
30. dataversion.txt		// used as database update notifier
31. inp.text			// takes input parameters provided in the GUI
32. README.TXT			// README file
33. ml.tmtbcca8			// BCCA structure file for 8 monomers
34. ml.tmtbcca16		// BCCA structure file for 16 monomers
35. ml.tmtbcca32		// BCCA structure file for 32 monomers	
36. ml.tmtbcca64		// BCCA structure file for 64 monomers
37. ml.tmtbcca128		// BCCA structure file for 128 monomers
38. ml.tmtbpca8			// BPCA structure file for 8 monomers
39. ml.tmtbpca16		// BPCA structure file for 16 monomers
40. ml.tmtbpca32		// BPCA structure file for 32 monomers
41. ml.tmtbpca64		// BPCA structure file for 64 monomers
42. ml.tmtbpca128		// BPCA structure file for 128 monomers
43. ml.usrstruct		// user defined structure file
44. command.sh			// bash file to take input from inp.txt and run nsphere1.for and csca.for files (linux)
45. command.bat			// batch file to take input from inp.txt and run nsphere1.for and csca.for files (Windows)
46. LICENSE.txt			// contains the lincense information
47. build.xml			// XML file for the build information


Files included in the JaSTA package (Windows):
==============================================
1.  csca.exe			// precompiled executable file for csca.for
2.  nsphere1.exe		// precompiled executable file for nsphere1.for
3.  JaSTA.exe			// the executable file for JaSTA package
4.  chilkat.dll			// DLL file for extracting downloaded DATA_NET.rar during database update
5.  j3dcore-ogl.dll		// DLL file for 3D visualization of the structure file
6.  favicon.ico			// Icon file for the JaSTA package
7.  csca.for			// fortran file to calculate calculate the Cext,Csca,Cabs
8.  nsphere1.for		// fortran file containing Superposition T-matrix codes by Mackowski & Mishchenko		
9.  sctmdim.for			// dimension file that limits the maximum number of monomers to 128
10. DATA.IN			// it takes monomer size and number of monomers as input from the GUI for the csca.for file 
11. csca.out			// provides the output of the csca.for file
12. nsphere1.out		// provides the output of the nsphere1.for file
13. pol.out			// provides the required scattering matrix coefficients
14. sca.out			// provides the scattering elements
15. sca_final.out		// provides the normalized values of the scattering elements
16. test1.out			// output file
17. hp_1.png			// image file used in the quick tutorial
18. hp_1a.png			// image file used in the quick tutorial
19. hp_2.png			// image file used in the quick tutorial
20. hp_2a.png			// image file used in the quick tutorial
21. hp_2b.png			// image file used in the quick tutorial	
22. hp_3a.png			// image file used in the quick tutorial	
23. hp_4a.png			// image file used in the quick tutorial
24. hp_5a.png			// image file used in the quick tutorial
25. hp_6a.png			// image file used in the quick tutorial
26. dataversion.txt		// used as database update notifier
27. inp.text			// takes input parameters provided in the GUI
28. README.TXT			// README file
29. ml.tmtbcca8			// BCCA structure file for 8 monomers
30. ml.tmtbcca16		// BCCA structure file for 16 monomers
31. ml.tmtbcca32		// BCCA structure file for 32 monomers	
32. ml.tmtbcca64		// BCCA structure file for 64 monomers
33. ml.tmtbcca128		// BCCA structure file for 128 monomers
34. ml.tmtbpca8			// BPCA structure file for 8 monomers
35. ml.tmtbpca16		// BPCA structure file for 16 monomers
36. ml.tmtbpca32		// BPCA structure file for 32 monomers
37. ml.tmtbpca64		// BPCA structure file for 64 monomers
38. ml.tmtbpca128		// BPCA structure file for 128 monomers
39. ml.usrstruct		// user defined structure file
40. command.bat			// batch file to take input from inp.txt and run nsphere1.for and csca.for files
41. count.bat			// batch file for welcome screen
42. LICENSE.txt			// contains the lincense information
43. build.xml			// XML file for the build information



Files included in the JaSTA package (Linux):
==============================================
1.  csca			// precompiled executable file for csca.for
2.  nsphere1			// precompiled executable file for nsphere1.for
3.  jasta.jar			// the executable file for JaSTA package
4.  libchilkat.so		// SO file for extracting downloaded DATA_NET.rar during database update
5.  libj3dcore-ogl.so		// SO file for 3D visualization of the structure file
6.  nsphere1.for		// fortran file containing Superposition T-matrix codes by Mackowski & Mishchenko
7.  csca.for			// fortran file to calculate calculate the Cext,Csca,Cabs
8.  JaSTA			// bash file to execute the JaSTA package either from desktop or from terminal
9.  sctmdim.for			// dimension file that limits the maximum number of monomers to 128
10. DATA.IN			// it takes monomer size and number of monomers as input from the GUI for the csca.for file 
11. csca.out			// provides the output of the csca.for file
12. nsphere1.out		// provides the output of the nsphere1.for file
13. pol.out			// provides the required scattering matrix coefficients
14. sca.out			// provides the scattering elements
15. sca_final.out		// provides the normalized values of the scattering elements
16. test1.out			// output file 
17. hp_1.png			// image file used in the quick tutorial
18. hp_1a.png			// image file used in the quick tutorial
19. hp_2.png			// image file used in the quick tutorial
20. hp_2a.png			// image file used in the quick tutorial
21. hp_2b.png			// image file used in the quick tutorial	
22. hp_3a.png			// image file used in the quick tutorial	
23. hp_4a.png			// image file used in the quick tutorial
24. hp_5a.png			// image file used in the quick tutorial
25. hp_6a.png			// image file used in the quick tutorial
26. dataversion.txt		// used as database update notifier
27. inp.text			// takes input parameters provided in the GUI
28. README.TXT			// README file
29. ml.tmtbcca8			// BCCA structure file for 8 monomers
30. ml.tmtbcca16		// BCCA structure file for 16 monomers
31. ml.tmtbcca32		// BCCA structure file for 32 monomers	
32. ml.tmtbcca64		// BCCA structure file for 64 monomers
33. ml.tmtbcca128		// BCCA structure file for 128 monomers
34. ml.tmtbpca8			// BPCA structure file for 8 monomers
35. ml.tmtbpca16		// BPCA structure file for 16 monomers
36. ml.tmtbpca32		// BPCA structure file for 32 monomers
37. ml.tmtbpca64		// BPCA structure file for 64 monomers
38. ml.tmtbpca128		// BPCA structure file for 128 monomers
39. ml.usrstruct		// user defined structure file
40. command.sh			// bash file to take input from inp.txt and run nsphere1.for and csca.for files
41. LICENSE.txt			// contains the lincense information
42. build.xml			// XML file for the build information


Folders included in the JaSTA package:
======================================
1. DATA				// contains user saved data
2. DATA_NET			// contains online data
3. lib				// external libraries
4. TEMP				// temporary folder for 'Compare Plot (user database)'
5. TEMP1			// temporary folder for 'Compare Plot (online database)'
6. j3d (linux)			// external library folder holding the java3d library files.


*********************************************
******Sample Input parameters and files******
*********************************************
Input Parameters:
=============================================
Size				0.09
Wavelength			0.450
Real Refractive Index		2.0
Imaginary Refractive Index	0.1
Number of Monomers		08
Aggregate Type			BCCA
=============================================

Input Files:
============
JaSTA incorporates three input files for a particular calculation,
inp.text, DATA.IN and the structure file. 
The inp.text and the DATA.IN files are automatically generated by the program, depending 
on the type of input parameters entered in the Input Panel of JaSTA.
----------------------
inp.text             |
----------------------
ml.tmtbcca8	//structure file
08		//Number of monomers
1.2568,2.0,0.1	//Xscale, real and imaginary refractive indeces
test1.out	//Output file

400,1.d-8,0
1.d-4,1.d-8
0,180,181
----------------------
----------------------
DATA.IN
----------------------
0.1,08
----------------------
----------------------
Structure File: 
There are 11 structure files included in the package. A particular structure file depend
on the Monomer number and the aggregate type selected as input parameters in the input panel.
The BCCA structure files:
ml.tmtbcca8
ml.tmtbcca16
ml.tmtbcca32
ml.tmtbcca64
ml.tmtbcca128

The BPCA structure files are:
ml.tmtbpca8
ml.tmtbpca16
ml.tmtbpca32
ml.tmtbpca64
ml.tmtbpca128

The user defined structure file is:
ml.usrstruct

The structure file for the above input parameters is, ml.tmtbcca8 and is defined below:
----------------------------------------------------
ml.tmtbcca8
----------------------------------------------------
  1     2.4530    -1.3043     4.0012  1  1       1
  1     0.8395    -0.7623     2.9510  1  1       2
  1    -1.6057    -0.6037     0.1318  1  1       3
  1     0.1067    -0.3559     1.1349  1  1       4
  1     0.0543     1.7421    -2.1906  1  1       5
  1     2.0372     2.0027    -2.1883  1  1       6
  1    -1.4974     0.4809    -2.2299  1  1       7
  1    -2.3874    -1.1995    -1.6100  1  1       8
----------------------------------------------------
This format must be maintained while using the user defined structure, i.e., ml.usrstruct file.
The second, third and fourth column defines the x, y and z coordinates respectively. The seventh
column defines the row number.
********************************************************************************************************



*****************************************************
******Sample Output parameters and output files******
*****************************************************
Output parameters:
=====================================================
albedo	0.79038876	Xscale	1.257
Q_sca	4.046		C_sca	0.4118336
Q_ext	5.119		C_ext	0.52105194
Q_abs	1.072		C_abs	0.10911657
=====================================================

Output Files:
=============================================================================================================
After a particular calculation, JaSTA creates four output files, test1.out, pol.out, sca.out and sca_final.out.
pol1.out and sca_final1.out are the copies of pol.out and sca_final.out for the database and the plot functions.
-------------------------------------------------------------------------------------------------------------------------------
test1.out
-------------------------------------------------------------------------------------------------------------------------------
scsmtm results
 input file:inp.text                      
 number of spheres:     8
 xscale, rirscale, riiscale, xv:  0.1257E+01  0.2000E+01  0.1000E+00  0.2514E+01
 qext,qabs,qsca,<cos theta>:  0.5119E+01  0.1072E+01  0.4046E+01  0.7083E+00
 theta    s11         s22         s33         s44         s21         s32         s43         s31         s42         s41
    0.00  0.6089E+02  0.6068E+02  0.6068E+02  0.6053E+02  0.0000E+00  0.4573E-01  0.0000E+00  0.0000E+00  0.0000E+00  0.4485E-01
    1.00  0.6077E+02  0.6056E+02  0.6056E+02  0.6042E+02 -0.4585E-02  0.4556E-01  0.1228E-02  0.3274E-05  0.2937E-05  0.4474E-01
    2.00  0.6043E+02  0.6022E+02  0.6022E+02  0.6007E+02 -0.1825E-01  0.4504E-01  0.4872E-02  0.1309E-04  0.1177E-04  0.4442E-01
    3.00  0.5986E+02  0.5965E+02  0.5965E+02  0.5950E+02 -0.4072E-01  0.4420E-01  0.1081E-01  0.2943E-04  0.2658E-04  0.4389E-01
    4.00  0.5907E+02  0.5886E+02  0.5886E+02  0.5872E+02 -0.7154E-01  0.4303E-01  0.1883E-01  0.5226E-04  0.4746E-04  0.4314E-01
    5.00  0.5808E+02  0.5786E+02  0.5786E+02  0.5772E+02 -0.1101E+00  0.4157E-01  0.2868E-01  0.8149E-04  0.7456E-04  0.4219E-01
    6.00  0.5689E+02  0.5667E+02  0.5667E+02  0.5653E+02 -0.1557E+00  0.3983E-01  0.4001E-01  0.1170E-03  0.1080E-03  0.4104E-01
    7.00  0.5551E+02  0.5529E+02  0.5529E+02  0.5515E+02 -0.2073E+00  0.3785E-01  0.5243E-01  0.1586E-03  0.1481E-03  0.3970E-01
    8.00  0.5397E+02  0.5375E+02  0.5375E+02  0.5361E+02 -0.2641E+00  0.3565E-01  0.6554E-01  0.2060E-03  0.1948E-03  0.3817E-01
    9.00  0.5229E+02  0.5206E+02  0.5206E+02  0.5192E+02 -0.3250E+00  0.3328E-01  0.7886E-01  0.2588E-03  0.2484E-03  0.3646E-01
   10.00  0.5047E+02  0.5024E+02  0.5024E+02  0.5010E+02 -0.3889E+00  0.3076E-01  0.9195E-01  0.3166E-03  0.3090E-03  0.3459E-01
   11.00  0.4854E+02  0.4831E+02  0.4830E+02  0.4817E+02 -0.4546E+00  0.2815E-01  0.1044E+00  0.3785E-03  0.3765E-03  0.3257E-01
   12.00  0.4652E+02  0.4628E+02  0.4628E+02  0.4615E+02 -0.5212E+00  0.2547E-01  0.1156E+00  0.4439E-03  0.4509E-03  0.3041E-01
   13.00  0.4443E+02  0.4419E+02  0.4419E+02  0.4406E+02 -0.5875E+00  0.2278E-01  0.1254E+00  0.5116E-03  0.5322E-03  0.2812E-01
   14.00  0.4230E+02  0.4205E+02  0.4205E+02  0.4192E+02 -0.6526E+00  0.2010E-01  0.1332E+00  0.5804E-03  0.6199E-03  0.2573E-01
   15.00  0.4013E+02  0.3989E+02  0.3988E+02  0.3976E+02 -0.7155E+00  0.1748E-01  0.1389E+00  0.6491E-03  0.7137E-03  0.2324E-01
   16.00  0.3796E+02  0.3771E+02  0.3770E+02  0.3758E+02 -0.7756E+00  0.1495E-01  0.1421E+00  0.7161E-03  0.8131E-03  0.2068E-01
   17.00  0.3580E+02  0.3555E+02  0.3554E+02  0.3542E+02 -0.8320E+00  0.1255E-01  0.1427E+00  0.7796E-03  0.9174E-03  0.1807E-01
   18.00  0.3366E+02  0.3341E+02  0.3340E+02  0.3328E+02 -0.8843E+00  0.1031E-01  0.1406E+00  0.8378E-03  0.1026E-02  0.1543E-01
   19.00  0.3157E+02  0.3131E+02  0.3130E+02  0.3119E+02 -0.9321E+00  0.8236E-02  0.1358E+00  0.8889E-03  0.1137E-02  0.1277E-01
   20.00  0.2954E+02  0.2927E+02  0.2926E+02  0.2915E+02 -0.9750E+00  0.6367E-02  0.1284E+00  0.9307E-03  0.1250E-02  0.1013E-01
   21.00  0.2757E+02  0.2731E+02  0.2729E+02  0.2719E+02 -0.1013E+01  0.4714E-02  0.1185E+00  0.9614E-03  0.1364E-02  0.7518E-02
   22.00  0.2569E+02  0.2542E+02  0.2540E+02  0.2530E+02 -0.1046E+01  0.3287E-02  0.1064E+00  0.9789E-03  0.1477E-02  0.4962E-02
   23.00  0.2390E+02  0.2362E+02  0.2360E+02  0.2351E+02 -0.1074E+01  0.2095E-02  0.9222E-01  0.9814E-03  0.1587E-02  0.2482E-02
   24.00  0.2220E+02  0.2192E+02  0.2190E+02  0.2181E+02 -0.1098E+01  0.1138E-02  0.7639E-01  0.9671E-03  0.1694E-02  0.1001E-03
   25.00  0.2060E+02  0.2032E+02  0.2030E+02  0.2021E+02 -0.1118E+01  0.4131E-03  0.5928E-01  0.9344E-03  0.1795E-02 -0.2164E-02
   26.00  0.1911E+02  0.1883E+02  0.1880E+02  0.1872E+02 -0.1133E+01 -0.8600E-04  0.4129E-01  0.8820E-03  0.1888E-02 -0.4291E-02
   27.00  0.1773E+02  0.1744E+02  0.1741E+02  0.1734E+02 -0.1145E+01 -0.3708E-03  0.2285E-01  0.8089E-03  0.1972E-02 -0.6263E-02
   28.00  0.1645E+02  0.1616E+02  0.1613E+02  0.1606E+02 -0.1154E+01 -0.4560E-03  0.4401E-02  0.7145E-03  0.2045E-02 -0.8063E-02
   29.00  0.1527E+02  0.1498E+02  0.1495E+02  0.1489E+02 -0.1160E+01 -0.3596E-03 -0.1363E-01  0.5983E-03  0.2105E-02 -0.9678E-02
   30.00  0.1420E+02  0.1391E+02  0.1387E+02  0.1381E+02 -0.1165E+01 -0.1020E-03 -0.3083E-01  0.4606E-03  0.2152E-02 -0.1109E-01
   31.00  0.1322E+02  0.1293E+02  0.1289E+02  0.1284E+02 -0.1167E+01  0.2941E-03 -0.4680E-01  0.3018E-03  0.2182E-02 -0.1230E-01
   32.00  0.1234E+02  0.1204E+02  0.1200E+02  0.1196E+02 -0.1169E+01  0.8048E-03 -0.6119E-01  0.1230E-03  0.2195E-02 -0.1330E-01
   33.00  0.1154E+02  0.1124E+02  0.1120E+02  0.1116E+02 -0.1169E+01  0.1405E-02 -0.7371E-01 -0.7458E-04  0.2191E-02 -0.1407E-01
   34.00  0.1083E+02  0.1052E+02  0.1048E+02  0.1045E+02 -0.1169E+01  0.2070E-02 -0.8409E-01 -0.2890E-03  0.2167E-02 -0.1463E-01
   35.00  0.1018E+02  0.9880E+01  0.9832E+01  0.9810E+01 -0.1169E+01  0.2775E-02 -0.9214E-01 -0.5181E-03  0.2125E-02 -0.1496E-01
   36.00  0.9610E+01  0.9303E+01  0.9252E+01  0.9237E+01 -0.1169E+01  0.3495E-02 -0.9773E-01 -0.7594E-03  0.2062E-02 -0.1508E-01
   37.00  0.9094E+01  0.8787E+01  0.8732E+01  0.8725E+01 -0.1168E+01  0.4208E-02 -0.1008E+00 -0.1010E-02  0.1979E-02 -0.1498E-01
   38.00  0.8633E+01  0.8324E+01  0.8265E+01  0.8266E+01 -0.1168E+01  0.4893E-02 -0.1013E+00 -0.1266E-02  0.1877E-02 -0.1469E-01
   39.00  0.8218E+01  0.7908E+01  0.7845E+01  0.7854E+01 -0.1168E+01  0.5529E-02 -0.9930E-01 -0.1526E-02  0.1757E-02 -0.1420E-01
   40.00  0.7843E+01  0.7533E+01  0.7466E+01  0.7482E+01 -0.1168E+01  0.6102E-02 -0.9492E-01 -0.1784E-02  0.1618E-02 -0.1354E-01
   41.00  0.7504E+01  0.7192E+01  0.7121E+01  0.7145E+01 -0.1167E+01  0.6596E-02 -0.8830E-01 -0.2039E-02  0.1462E-02 -0.1271E-01
   42.00  0.7193E+01  0.6881E+01  0.6805E+01  0.6837E+01 -0.1167E+01  0.7001E-02 -0.7964E-01 -0.2286E-02  0.1292E-02 -0.1174E-01
   43.00  0.6907E+01  0.6594E+01  0.6513E+01  0.6553E+01 -0.1166E+01  0.7306E-02 -0.6918E-01 -0.2521E-02  0.1107E-02 -0.1065E-01
   44.00  0.6641E+01  0.6328E+01  0.6241E+01  0.6289E+01 -0.1165E+01  0.7508E-02 -0.5719E-01 -0.2743E-02  0.9121E-03 -0.9448E-02
   45.00  0.6391E+01  0.6077E+01  0.5985E+01  0.6041E+01 -0.1163E+01  0.7602E-02 -0.4394E-01 -0.2947E-02  0.7076E-03 -0.8163E-02
   46.00  0.6154E+01  0.5840E+01  0.5743E+01  0.5805E+01 -0.1160E+01  0.7589E-02 -0.2974E-01 -0.3131E-02  0.4966E-03 -0.6814E-02
   47.00  0.5927E+01  0.5613E+01  0.5510E+01  0.5580E+01 -0.1156E+01  0.7470E-02 -0.1489E-01 -0.3294E-02  0.2816E-03 -0.5422E-02
   48.00  0.5709E+01  0.5395E+01  0.5286E+01  0.5363E+01 -0.1151E+01  0.7250E-02  0.3083E-03 -0.3432E-02  0.6529E-04 -0.4009E-02
   49.00  0.5497E+01  0.5183E+01  0.5067E+01  0.5152E+01 -0.1145E+01  0.6935E-02  0.1556E-01 -0.3544E-02 -0.1496E-03 -0.2593E-02
   50.00  0.5290E+01  0.4976E+01  0.4854E+01  0.4945E+01 -0.1137E+01  0.6534E-02  0.3060E-01 -0.3630E-02 -0.3603E-03 -0.1196E-02
   51.00  0.5087E+01  0.4773E+01  0.4646E+01  0.4743E+01 -0.1128E+01  0.6056E-02  0.4518E-01 -0.3689E-02 -0.5642E-03  0.1658E-03
   52.00  0.4888E+01  0.4575E+01  0.4441E+01  0.4545E+01 -0.1118E+01  0.5512E-02  0.5907E-01 -0.3721E-02 -0.7587E-03  0.1475E-02
   53.00  0.4693E+01  0.4380E+01  0.4240E+01  0.4350E+01 -0.1106E+01  0.4914E-02  0.7208E-01 -0.3726E-02 -0.9414E-03  0.2715E-02
   54.00  0.4501E+01  0.4188E+01  0.4043E+01  0.4158E+01 -0.1093E+01  0.4272E-02  0.8404E-01 -0.3706E-02 -0.1110E-02  0.3874E-02
   55.00  0.4314E+01  0.4000E+01  0.3850E+01  0.3971E+01 -0.1078E+01  0.3601E-02  0.9484E-01 -0.3662E-02 -0.1262E-02  0.4940E-02
   56.00  0.4130E+01  0.3817E+01  0.3660E+01  0.3787E+01 -0.1063E+01  0.2910E-02  0.1044E+00 -0.3596E-02 -0.1397E-02  0.5902E-02
   57.00  0.3951E+01  0.3638E+01  0.3476E+01  0.3607E+01 -0.1046E+01  0.2213E-02  0.1126E+00 -0.3509E-02 -0.1513E-02  0.6755E-02
   58.00  0.3776E+01  0.3463E+01  0.3297E+01  0.3432E+01 -0.1028E+01  0.1521E-02  0.1195E+00 -0.3405E-02 -0.1608E-02  0.7491E-02
   59.00  0.3607E+01  0.3295E+01  0.3123E+01  0.3263E+01 -0.1010E+01  0.8424E-03  0.1250E+00 -0.3286E-02 -0.1682E-02  0.8108E-02
   60.00  0.3444E+01  0.3132E+01  0.2955E+01  0.3100E+01 -0.9907E+00  0.1880E-03  0.1293E+00 -0.3154E-02 -0.1735E-02  0.8603E-02
   61.00  0.3287E+01  0.2975E+01  0.2794E+01  0.2942E+01 -0.9714E+00 -0.4345E-03  0.1323E+00 -0.3014E-02 -0.1766E-02  0.8978E-02
   62.00  0.3137E+01  0.2825E+01  0.2640E+01  0.2792E+01 -0.9519E+00 -0.1018E-02  0.1341E+00 -0.2867E-02 -0.1776E-02  0.9234E-02
   63.00  0.2993E+01  0.2682E+01  0.2493E+01  0.2648E+01 -0.9323E+00 -0.1557E-02  0.1349E+00 -0.2716E-02 -0.1766E-02  0.9375E-02
   64.00  0.2857E+01  0.2545E+01  0.2353E+01  0.2511E+01 -0.9128E+00 -0.2046E-02  0.1347E+00 -0.2565E-02 -0.1736E-02  0.9405E-02
   65.00  0.2728E+01  0.2417E+01  0.2220E+01  0.2382E+01 -0.8936E+00 -0.2484E-02  0.1337E+00 -0.2417E-02 -0.1688E-02  0.9332E-02
   66.00  0.2606E+01  0.2295E+01  0.2095E+01  0.2259E+01 -0.8748E+00 -0.2867E-02  0.1319E+00 -0.2273E-02 -0.1623E-02  0.9161E-02
   67.00  0.2491E+01  0.2180E+01  0.1978E+01  0.2144E+01 -0.8565E+00 -0.3194E-02  0.1295E+00 -0.2137E-02 -0.1544E-02  0.8902E-02
   68.00  0.2384E+01  0.2073E+01  0.1867E+01  0.2036E+01 -0.8387E+00 -0.3466E-02  0.1267E+00 -0.2010E-02 -0.1452E-02  0.8562E-02
   69.00  0.2283E+01  0.1973E+01  0.1764E+01  0.1935E+01 -0.8215E+00 -0.3685E-02  0.1234E+00 -0.1893E-02 -0.1350E-02  0.8151E-02
   70.00  0.2188E+01  0.1879E+01  0.1667E+01  0.1840E+01 -0.8050E+00 -0.3851E-02  0.1199E+00 -0.1789E-02 -0.1239E-02  0.7677E-02
   71.00  0.2100E+01  0.1791E+01  0.1577E+01  0.1751E+01 -0.7891E+00 -0.3968E-02  0.1163E+00 -0.1699E-02 -0.1122E-02  0.7151E-02
   72.00  0.2018E+01  0.1709E+01  0.1493E+01  0.1669E+01 -0.7740E+00 -0.4038E-02  0.1125E+00 -0.1623E-02 -0.1002E-02  0.6581E-02
   73.00  0.1942E+01  0.1633E+01  0.1415E+01  0.1591E+01 -0.7595E+00 -0.4066E-02  0.1088E+00 -0.1562E-02 -0.8815E-03  0.5975E-02
   74.00  0.1871E+01  0.1562E+01  0.1341E+01  0.1519E+01 -0.7455E+00 -0.4055E-02  0.1051E+00 -0.1515E-02 -0.7617E-03  0.5343E-02
   75.00  0.1804E+01  0.1496E+01  0.1273E+01  0.1452E+01 -0.7322E+00 -0.4010E-02  0.1016E+00 -0.1484E-02 -0.6454E-03  0.4693E-02
   76.00  0.1741E+01  0.1435E+01  0.1209E+01  0.1389E+01 -0.7194E+00 -0.3934E-02  0.9819E-01 -0.1467E-02 -0.5347E-03  0.4032E-02
   77.00  0.1683E+01  0.1377E+01  0.1150E+01  0.1330E+01 -0.7070E+00 -0.3832E-02  0.9499E-01 -0.1464E-02 -0.4313E-03  0.3366E-02
   78.00  0.1628E+01  0.1323E+01  0.1093E+01  0.1274E+01 -0.6949E+00 -0.3708E-02  0.9200E-01 -0.1474E-02 -0.3370E-03  0.2701E-02
   79.00  0.1576E+01  0.1272E+01  0.1041E+01  0.1222E+01 -0.6832E+00 -0.3566E-02  0.8923E-01 -0.1497E-02 -0.2533E-03  0.2044E-02
   80.00  0.1527E+01  0.1223E+01  0.9906E+00  0.1172E+01 -0.6716E+00 -0.3409E-02  0.8667E-01 -0.1531E-02 -0.1813E-03  0.1399E-02
   81.00  0.1480E+01  0.1178E+01  0.9433E+00  0.1125E+01 -0.6603E+00 -0.3241E-02  0.8432E-01 -0.1575E-02 -0.1220E-03  0.7696E-03
   82.00  0.1436E+01  0.1134E+01  0.8983E+00  0.1080E+01 -0.6490E+00 -0.3063E-02  0.8215E-01 -0.1628E-02 -0.7609E-04  0.1595E-03
   83.00  0.1393E+01  0.1093E+01  0.8555E+00  0.1037E+01 -0.6377E+00 -0.2880E-02  0.8016E-01 -0.1689E-02 -0.4389E-04 -0.4287E-03
   84.00  0.1352E+01  0.1053E+01  0.8145E+00  0.9961E+00 -0.6264E+00 -0.2694E-02  0.7832E-01 -0.1756E-02 -0.2559E-04 -0.9927E-03
   85.00  0.1312E+01  0.1015E+01  0.7751E+00  0.9565E+00 -0.6150E+00 -0.2505E-02  0.7660E-01 -0.1829E-02 -0.2107E-04 -0.1531E-02
   86.00  0.1274E+01  0.9787E+00  0.7373E+00  0.9184E+00 -0.6035E+00 -0.2316E-02  0.7498E-01 -0.1906E-02 -0.2994E-04 -0.2042E-02
   87.00  0.1237E+01  0.9433E+00  0.7008E+00  0.8816E+00 -0.5918E+00 -0.2127E-02  0.7343E-01 -0.1987E-02 -0.5163E-04 -0.2526E-02
   88.00  0.1201E+01  0.9090E+00  0.6656E+00  0.8459E+00 -0.5800E+00 -0.1941E-02  0.7192E-01 -0.2070E-02 -0.8534E-04 -0.2981E-02
   89.00  0.1166E+01  0.8758E+00  0.6316E+00  0.8114E+00 -0.5680E+00 -0.1756E-02  0.7043E-01 -0.2155E-02 -0.1301E-03 -0.3408E-02
   90.00  0.1132E+01  0.8436E+00  0.5987E+00  0.7780E+00 -0.5558E+00 -0.1574E-02  0.6894E-01 -0.2240E-02 -0.1847E-03 -0.3807E-02
   91.00  0.1099E+01  0.8123E+00  0.5669E+00  0.7455E+00 -0.5435E+00 -0.1395E-02  0.6743E-01 -0.2327E-02 -0.2480E-03 -0.4178E-02
   92.00  0.1066E+01  0.7819E+00  0.5361E+00  0.7140E+00 -0.5309E+00 -0.1220E-02  0.6588E-01 -0.2413E-02 -0.3186E-03 -0.4521E-02
   93.00  0.1035E+01  0.7523E+00  0.5063E+00  0.6835E+00 -0.5183E+00 -0.1047E-02  0.6427E-01 -0.2499E-02 -0.3950E-03 -0.4837E-02
   94.00  0.1004E+01  0.7236E+00  0.4774E+00  0.6539E+00 -0.5055E+00 -0.8776E-03  0.6261E-01 -0.2585E-02 -0.4758E-03 -0.5126E-02
   95.00  0.9739E+00  0.6958E+00  0.4496E+00  0.6253E+00 -0.4926E+00 -0.7113E-03  0.6087E-01 -0.2670E-02 -0.5595E-03 -0.5389E-02
   96.00  0.9446E+00  0.6687E+00  0.4227E+00  0.5975E+00 -0.4797E+00 -0.5481E-03  0.5905E-01 -0.2754E-02 -0.6445E-03 -0.5626E-02
   97.00  0.9162E+00  0.6426E+00  0.3967E+00  0.5707E+00 -0.4667E+00 -0.3881E-03  0.5716E-01 -0.2837E-02 -0.7295E-03 -0.5838E-02
   98.00  0.8886E+00  0.6172E+00  0.3717E+00  0.5449E+00 -0.4536E+00 -0.2314E-03  0.5520E-01 -0.2920E-02 -0.8130E-03 -0.6025E-02
   99.00  0.8618E+00  0.5928E+00  0.3476E+00  0.5199E+00 -0.4407E+00 -0.7814E-04  0.5316E-01 -0.3001E-02 -0.8936E-03 -0.6187E-02
  100.00  0.8359E+00  0.5691E+00  0.3244E+00  0.4959E+00 -0.4277E+00  0.7132E-04  0.5105E-01 -0.3082E-02 -0.9703E-03 -0.6325E-02
  101.00  0.8108E+00  0.5464E+00  0.3022E+00  0.4728E+00 -0.4149E+00  0.2166E-03  0.4889E-01 -0.3162E-02 -0.1042E-02 -0.6438E-02
  102.00  0.7866E+00  0.5244E+00  0.2809E+00  0.4507E+00 -0.4021E+00  0.3574E-03  0.4667E-01 -0.3242E-02 -0.1107E-02 -0.6528E-02
  103.00  0.7633E+00  0.5033E+00  0.2605E+00  0.4294E+00 -0.3895E+00  0.4929E-03  0.4441E-01 -0.3320E-02 -0.1165E-02 -0.6593E-02
  104.00  0.7408E+00  0.4831E+00  0.2410E+00  0.4091E+00 -0.3771E+00  0.6227E-03  0.4211E-01 -0.3398E-02 -0.1216E-02 -0.6635E-02
  105.00  0.7191E+00  0.4637E+00  0.2224E+00  0.3896E+00 -0.3648E+00  0.7461E-03  0.3979E-01 -0.3476E-02 -0.1258E-02 -0.6653E-02
  106.00  0.6983E+00  0.4451E+00  0.2046E+00  0.3710E+00 -0.3527E+00  0.8622E-03  0.3745E-01 -0.3552E-02 -0.1291E-02 -0.6647E-02
  107.00  0.6784E+00  0.4273E+00  0.1876E+00  0.3533E+00 -0.3408E+00  0.9704E-03  0.3511E-01 -0.3627E-02 -0.1314E-02 -0.6618E-02
  108.00  0.6592E+00  0.4103E+00  0.1715E+00  0.3364E+00 -0.3292E+00  0.1070E-02  0.3277E-01 -0.3701E-02 -0.1329E-02 -0.6566E-02
  109.00  0.6409E+00  0.3941E+00  0.1562E+00  0.3203E+00 -0.3178E+00  0.1160E-02  0.3045E-01 -0.3774E-02 -0.1333E-02 -0.6490E-02
  110.00  0.6234E+00  0.3786E+00  0.1416E+00  0.3050E+00 -0.3067E+00  0.1240E-02  0.2814E-01 -0.3845E-02 -0.1328E-02 -0.6391E-02
  111.00  0.6066E+00  0.3638E+00  0.1277E+00  0.2904E+00 -0.2958E+00  0.1309E-02  0.2586E-01 -0.3913E-02 -0.1313E-02 -0.6270E-02
  112.00  0.5906E+00  0.3498E+00  0.1146E+00  0.2766E+00 -0.2851E+00  0.1367E-02  0.2362E-01 -0.3979E-02 -0.1289E-02 -0.6126E-02
  113.00  0.5753E+00  0.3364E+00  0.1021E+00  0.2634E+00 -0.2747E+00  0.1414E-02  0.2141E-01 -0.4043E-02 -0.1255E-02 -0.5961E-02
  114.00  0.5607E+00  0.3237E+00  0.9028E-01  0.2510E+00 -0.2646E+00  0.1448E-02  0.1925E-01 -0.4103E-02 -0.1214E-02 -0.5775E-02
  115.00  0.5467E+00  0.3115E+00  0.7908E-01  0.2392E+00 -0.2548E+00  0.1470E-02  0.1714E-01 -0.4160E-02 -0.1163E-02 -0.5569E-02
  116.00  0.5334E+00  0.3000E+00  0.6848E-01  0.2280E+00 -0.2452E+00  0.1479E-02  0.1509E-01 -0.4213E-02 -0.1106E-02 -0.5343E-02
  117.00  0.5208E+00  0.2891E+00  0.5846E-01  0.2174E+00 -0.2358E+00  0.1476E-02  0.1308E-01 -0.4261E-02 -0.1041E-02 -0.5099E-02
  118.00  0.5087E+00  0.2787E+00  0.4898E-01  0.2074E+00 -0.2267E+00  0.1461E-02  0.1114E-01 -0.4305E-02 -0.9695E-03 -0.4838E-02
  119.00  0.4971E+00  0.2689E+00  0.4002E-01  0.1979E+00 -0.2178E+00  0.1434E-02  0.9249E-02 -0.4345E-02 -0.8925E-03 -0.4561E-02
  120.00  0.4861E+00  0.2595E+00  0.3156E-01  0.1889E+00 -0.2092E+00  0.1396E-02  0.7421E-02 -0.4379E-02 -0.8103E-03 -0.4269E-02
  121.00  0.4756E+00  0.2507E+00  0.2357E-01  0.1804E+00 -0.2008E+00  0.1348E-02  0.5653E-02 -0.4408E-02 -0.7238E-03 -0.3965E-02
  122.00  0.4656E+00  0.2423E+00  0.1604E-01  0.1723E+00 -0.1927E+00  0.1290E-02  0.3944E-02 -0.4431E-02 -0.6338E-03 -0.3649E-02
  123.00  0.4561E+00  0.2343E+00  0.8934E-02  0.1647E+00 -0.1847E+00  0.1222E-02  0.2295E-02 -0.4449E-02 -0.5408E-03 -0.3324E-02
  124.00  0.4470E+00  0.2268E+00  0.2235E-02  0.1575E+00 -0.1770E+00  0.1147E-02  0.7037E-03 -0.4462E-02 -0.4459E-03 -0.2991E-02
  125.00  0.4383E+00  0.2197E+00 -0.4078E-02  0.1506E+00 -0.1695E+00  0.1065E-02 -0.8304E-03 -0.4469E-02 -0.3496E-03 -0.2652E-02
  126.00  0.4301E+00  0.2130E+00 -0.1003E-01  0.1442E+00 -0.1622E+00  0.9773E-03 -0.2309E-02 -0.4471E-02 -0.2527E-03 -0.2309E-02
  127.00  0.4222E+00  0.2067E+00 -0.1563E-01  0.1380E+00 -0.1551E+00  0.8851E-03 -0.3733E-02 -0.4467E-02 -0.1560E-03 -0.1963E-02
  128.00  0.4147E+00  0.2007E+00 -0.2091E-01  0.1322E+00 -0.1482E+00  0.7896E-03 -0.5105E-02 -0.4459E-02 -0.6024E-04 -0.1617E-02
  129.00  0.4075E+00  0.1951E+00 -0.2589E-01  0.1267E+00 -0.1414E+00  0.6921E-03 -0.6427E-02 -0.4446E-02  0.3393E-04 -0.1273E-02
  130.00  0.4007E+00  0.1898E+00 -0.3059E-01  0.1214E+00 -0.1348E+00  0.5938E-03 -0.7700E-02 -0.4428E-02  0.1258E-03 -0.9317E-03
  131.00  0.3942E+00  0.1849E+00 -0.3503E-01  0.1165E+00 -0.1284E+00  0.4959E-03 -0.8926E-02 -0.4405E-02  0.2148E-03 -0.5952E-03
  132.00  0.3880E+00  0.1802E+00 -0.3923E-01  0.1117E+00 -0.1222E+00  0.3996E-03 -0.1011E-01 -0.4379E-02  0.3002E-03 -0.2649E-03
  133.00  0.3822E+00  0.1758E+00 -0.4321E-01  0.1072E+00 -0.1162E+00  0.3058E-03 -0.1125E-01 -0.4349E-02  0.3816E-03  0.5779E-04
  134.00  0.3766E+00  0.1717E+00 -0.4699E-01  0.1029E+00 -0.1102E+00  0.2157E-03 -0.1234E-01 -0.4315E-02  0.4584E-03  0.3718E-03
  135.00  0.3713E+00  0.1679E+00 -0.5060E-01  0.9886E-01 -0.1045E+00  0.1300E-03 -0.1340E-01 -0.4278E-02  0.5301E-03  0.6763E-03
  136.00  0.3664E+00  0.1643E+00 -0.5405E-01  0.9497E-01 -0.9889E-01  0.4972E-04 -0.1441E-01 -0.4237E-02  0.5963E-03  0.9704E-03
  137.00  0.3617E+00  0.1609E+00 -0.5736E-01  0.9128E-01 -0.9344E-01 -0.2462E-04 -0.1539E-01 -0.4194E-02  0.6566E-03  0.1254E-02
  138.00  0.3573E+00  0.1578E+00 -0.6055E-01  0.8778E-01 -0.8813E-01 -0.9243E-04 -0.1632E-01 -0.4148E-02  0.7108E-03  0.1527E-02
  139.00  0.3533E+00  0.1549E+00 -0.6364E-01  0.8446E-01 -0.8296E-01 -0.1533E-03 -0.1722E-01 -0.4098E-02  0.7587E-03  0.1789E-02
  140.00  0.3495E+00  0.1523E+00 -0.6665E-01  0.8133E-01 -0.7794E-01 -0.2068E-03 -0.1807E-01 -0.4047E-02  0.8000E-03  0.2041E-02
  141.00  0.3461E+00  0.1498E+00 -0.6960E-01  0.7839E-01 -0.7307E-01 -0.2530E-03 -0.1887E-01 -0.3992E-02  0.8346E-03  0.2283E-02
  142.00  0.3430E+00  0.1475E+00 -0.7249E-01  0.7565E-01 -0.6834E-01 -0.2917E-03 -0.1963E-01 -0.3934E-02  0.8625E-03  0.2517E-02
  143.00  0.3403E+00  0.1454E+00 -0.7535E-01  0.7311E-01 -0.6376E-01 -0.3229E-03 -0.2034E-01 -0.3873E-02  0.8837E-03  0.2744E-02
  144.00  0.3379E+00  0.1435E+00 -0.7819E-01  0.7079E-01 -0.5932E-01 -0.3469E-03 -0.2099E-01 -0.3809E-02  0.8983E-03  0.2965E-02
  145.00  0.3359E+00  0.1418E+00 -0.8101E-01  0.6869E-01 -0.5504E-01 -0.3640E-03 -0.2158E-01 -0.3742E-02  0.9065E-03  0.3182E-02
  146.00  0.3342E+00  0.1402E+00 -0.8384E-01  0.6683E-01 -0.5091E-01 -0.3745E-03 -0.2211E-01 -0.3671E-02  0.9084E-03  0.3398E-02
  147.00  0.3330E+00  0.1388E+00 -0.8666E-01  0.6522E-01 -0.4694E-01 -0.3788E-03 -0.2256E-01 -0.3595E-02  0.9043E-03  0.3613E-02
  148.00  0.3322E+00  0.1376E+00 -0.8950E-01  0.6388E-01 -0.4313E-01 -0.3776E-03 -0.2294E-01 -0.3516E-02  0.8945E-03  0.3830E-02
  149.00  0.3318E+00  0.1366E+00 -0.9236E-01  0.6282E-01 -0.3948E-01 -0.3713E-03 -0.2323E-01 -0.3432E-02  0.8795E-03  0.4052E-02
  150.00  0.3319E+00  0.1357E+00 -0.9523E-01  0.6206E-01 -0.3600E-01 -0.3606E-03 -0.2344E-01 -0.3342E-02  0.8595E-03  0.4279E-02
  151.00  0.3324E+00  0.1350E+00 -0.9812E-01  0.6161E-01 -0.3269E-01 -0.3461E-03 -0.2354E-01 -0.3248E-02  0.8350E-03  0.4516E-02
  152.00  0.3333E+00  0.1345E+00 -0.1010E+00  0.6149E-01 -0.2955E-01 -0.3284E-03 -0.2355E-01 -0.3148E-02  0.8065E-03  0.4763E-02
  153.00  0.3348E+00  0.1341E+00 -0.1039E+00  0.6170E-01 -0.2659E-01 -0.3082E-03 -0.2345E-01 -0.3043E-02  0.7744E-03  0.5022E-02
  154.00  0.3367E+00  0.1339E+00 -0.1069E+00  0.6225E-01 -0.2380E-01 -0.2862E-03 -0.2324E-01 -0.2932E-02  0.7394E-03  0.5294E-02
  155.00  0.3391E+00  0.1339E+00 -0.1098E+00  0.6314E-01 -0.2119E-01 -0.2628E-03 -0.2292E-01 -0.2815E-02  0.7017E-03  0.5582E-02
  156.00  0.3419E+00  0.1341E+00 -0.1127E+00  0.6439E-01 -0.1876E-01 -0.2387E-03 -0.2249E-01 -0.2693E-02  0.6621E-03  0.5885E-02
  157.00  0.3451E+00  0.1344E+00 -0.1156E+00  0.6597E-01 -0.1651E-01 -0.2144E-03 -0.2193E-01 -0.2565E-02  0.6209E-03  0.6204E-02
  158.00  0.3488E+00  0.1348E+00 -0.1185E+00  0.6789E-01 -0.1444E-01 -0.1903E-03 -0.2127E-01 -0.2432E-02  0.5787E-03  0.6539E-02
  159.00  0.3529E+00  0.1354E+00 -0.1214E+00  0.7013E-01 -0.1254E-01 -0.1670E-03 -0.2049E-01 -0.2294E-02  0.5358E-03  0.6890E-02
  160.00  0.3574E+00  0.1362E+00 -0.1242E+00  0.7268E-01 -0.1081E-01 -0.1447E-03 -0.1961E-01 -0.2152E-02  0.4929E-03  0.7257E-02
  161.00  0.3621E+00  0.1371E+00 -0.1269E+00  0.7550E-01 -0.9241E-02 -0.1237E-03 -0.1863E-01 -0.2007E-02  0.4502E-03  0.7636E-02
  162.00  0.3672E+00  0.1381E+00 -0.1296E+00  0.7858E-01 -0.7836E-02 -0.1042E-03 -0.1756E-01 -0.1859E-02  0.4082E-03  0.8028E-02
  163.00  0.3725E+00  0.1392E+00 -0.1322E+00  0.8188E-01 -0.6584E-02 -0.8650E-04 -0.1640E-01 -0.1709E-02  0.3672E-03  0.8428E-02
  164.00  0.3780E+00  0.1404E+00 -0.1348E+00  0.8537E-01 -0.5478E-02 -0.7060E-04 -0.1518E-01 -0.1558E-02  0.3275E-03  0.8836E-02
  165.00  0.3836E+00  0.1416E+00 -0.1372E+00  0.8900E-01 -0.4510E-02 -0.5658E-04 -0.1391E-01 -0.1408E-02  0.2894E-03  0.9247E-02
  166.00  0.3893E+00  0.1430E+00 -0.1395E+00  0.9272E-01 -0.3670E-02 -0.4443E-04 -0.1260E-01 -0.1259E-02  0.2532E-03  0.9659E-02
  167.00  0.3950E+00  0.1443E+00 -0.1417E+00  0.9649E-01 -0.2949E-02 -0.3411E-04 -0.1127E-01 -0.1112E-02  0.2190E-03  0.1007E-01
  168.00  0.4006E+00  0.1457E+00 -0.1438E+00  0.1003E+00 -0.2337E-02 -0.2552E-04 -0.9930E-02 -0.9697E-03  0.1870E-03  0.1047E-01
  169.00  0.4061E+00  0.1471E+00 -0.1457E+00  0.1040E+00 -0.1823E-02 -0.1853E-04 -0.8608E-02 -0.8323E-03  0.1573E-03  0.1086E-01
  170.00  0.4114E+00  0.1485E+00 -0.1475E+00  0.1076E+00 -0.1398E-02 -0.1301E-04 -0.7320E-02 -0.7014E-03  0.1301E-03  0.1123E-01
  171.00  0.4164E+00  0.1498E+00 -0.1491E+00  0.1111E+00 -0.1050E-02 -0.8767E-05 -0.6085E-02 -0.5784E-03  0.1054E-03  0.1158E-01
  172.00  0.4211E+00  0.1510E+00 -0.1506E+00  0.1143E+00 -0.7706E-03 -0.5632E-05 -0.4921E-02 -0.4644E-03  0.8324E-04  0.1191E-01
  173.00  0.4254E+00  0.1521E+00 -0.1519E+00  0.1173E+00 -0.5491E-03 -0.3415E-05 -0.3846E-02 -0.3606E-03  0.6369E-04  0.1221E-01
  174.00  0.4292E+00  0.1532E+00 -0.1530E+00  0.1200E+00 -0.3769E-03 -0.1933E-05 -0.2876E-02 -0.2682E-03  0.4675E-04  0.1248E-01
  175.00  0.4326E+00  0.1541E+00 -0.1540E+00  0.1224E+00 -0.2459E-03 -0.1012E-05 -0.2028E-02 -0.1882E-03  0.3244E-04  0.1271E-01
  176.00  0.4354E+00  0.1549E+00 -0.1548E+00  0.1244E+00 -0.1489E-03 -0.4937E-06 -0.1314E-02 -0.1215E-03  0.2074E-04  0.1291E-01
  177.00  0.4376E+00  0.1555E+00 -0.1555E+00  0.1259E+00 -0.8006E-04 -0.2421E-06 -0.7462E-03 -0.6882E-04  0.1166E-04  0.1306E-01
  178.00  0.4392E+00  0.1559E+00 -0.1559E+00  0.1271E+00 -0.3440E-04 -0.1451E-06 -0.3339E-03 -0.3073E-04  0.5178E-05  0.1317E-01
  179.00  0.4402E+00  0.1562E+00 -0.1562E+00  0.1278E+00 -0.8419E-05 -0.1206E-06 -0.8382E-04 -0.7706E-05  0.1294E-05  0.1324E-01
  180.00  0.4406E+00  0.1563E+00 -0.1563E+00  0.1280E+00  0.0000E+00 -0.1181E-06  0.0000E+00  0.0000E+00  0.0000E+00  0.1327E-01
 scattering matrix expansion coefficients
    w  a11         a22m        a22p        a23m        a23p        a44         a12         a34         a13         a24         a14
    0  0.4046E+01  0.0000E+00  0.0000E+00  0.0000E+00  0.0000E+00  0.3716E+01  0.0000E+00  0.0000E+00  0.0000E+00 -0.0000E+00 -0.1211E-03
    1  0.8598E+01  0.0000E+00  0.0000E+00  0.0000E+00  0.0000E+00  0.8544E+01  0.0000E+00  0.0000E+00  0.0000E+00 -0.0000E+00  0.6130E-03
    2  0.9573E+01  0.1947E+00  0.1490E+02 -0.1837E-05 -0.5035E-02  0.9588E+01 -0.1176E+01  0.1043E+00  0.5835E-02 -0.1081E-02  0.5009E-02
    3  0.8898E+01  0.1234E+00  0.1141E+02 -0.2355E-05 -0.6935E-02  0.8896E+01 -0.9264E+00  0.6043E-01 -0.2048E-02  0.6533E-04 -0.5852E-02
    4  0.7851E+01  0.8616E-01  0.9362E+01 -0.2133E-05 -0.4253E-02  0.7816E+01 -0.6202E+00 -0.6390E-01  0.3299E-02  0.1267E-02  0.7584E-02
    5  0.6552E+01  0.2299E-01  0.7536E+01 -0.2661E-05  0.9841E-03  0.6566E+01 -0.4561E+00 -0.5607E-01 -0.6848E-03  0.4702E-03  0.1668E-01
    6  0.5351E+01  0.1771E-01  0.6019E+01 -0.2391E-05 -0.3151E-02  0.5361E+01 -0.3078E+00 -0.4530E-01 -0.1096E-02  0.2686E-02  0.1566E-01
    7  0.4096E+01  0.1458E-03  0.4607E+01 -0.1802E-05 -0.8394E-02  0.4111E+01 -0.1999E+00  0.2784E-01 -0.2130E-02  0.1160E-02  0.7018E-02
    8  0.2871E+01  0.2112E-02  0.3260E+01 -0.5401E-06 -0.7996E-02  0.2877E+01 -0.1449E+00  0.8091E-01 -0.7964E-03 -0.6634E-03  0.2165E-02
    9  0.1705E+01 -0.1387E-02  0.1981E+01  0.1067E-06 -0.6702E-02  0.1711E+01 -0.1425E+00  0.1093E+00 -0.2205E-03 -0.6618E-03 -0.2034E-02
   10  0.8495E+00  0.1830E-02  0.1005E+01  0.1080E-06 -0.3138E-02  0.8534E+00 -0.1216E+00  0.8214E-01  0.5152E-03 -0.2584E-03 -0.1173E-02
   11  0.3424E+00  0.3032E-02  0.4102E+00  0.5659E-07 -0.9199E-03  0.3417E+00 -0.8000E-01  0.4557E-01  0.2593E-03  0.1847E-04 -0.6406E-03
   12  0.1148E+00  0.2930E-02  0.1371E+00  0.2673E-07 -0.1779E-03  0.1123E+00 -0.3805E-01  0.1722E-01  0.8699E-04  0.1733E-04 -0.7226E-04
   13  0.3140E-01  0.1459E-02  0.3708E-01  0.8335E-08 -0.1197E-04  0.2975E-01 -0.1362E-01  0.5253E-02  0.1139E-04  0.3267E-05  0.1581E-05
   14  0.7227E-02  0.5297E-03  0.8349E-02  0.2111E-08  0.1669E-05  0.6558E-02 -0.3802E-02  0.1218E-02  0.4393E-06 -0.7826E-07  0.5301E-05
   15  0.1393E-02  0.1409E-03  0.1568E-02  0.3658E-09  0.6592E-06  0.1201E-02 -0.8510E-03  0.2382E-03 -0.2212E-06 -0.2354E-06  0.1175E-05
   16  0.2310E-03  0.3019E-04  0.2521E-03  0.5207E-10  0.9792E-07  0.1879E-03 -0.1576E-03  0.3786E-04 -0.4731E-07 -0.5920E-07  0.2070E-06
   17  0.3304E-04  0.5264E-05  0.3493E-04  0.6293E-11  0.9381E-08  0.2526E-04 -0.2459E-04  0.5222E-05 -0.5351E-08 -0.1112E-07  0.2621E-07
   18  0.4154E-05  0.7779E-06  0.4249E-05 -0.8658E-12  0.2487E-11  0.2973E-05 -0.3302E-05  0.6105E-06 -0.2530E-09 -0.1106E-08  0.2723E-08
   19  0.4603E-06  0.9840E-07  0.4557E-06 -0.6339E-12 -0.7601E-10  0.3075E-06 -0.3858E-06  0.6180E-07  0.2228E-11 -0.6809E-10  0.2228E-09
   20  0.4508E-07  0.1079E-07  0.4317E-07 -0.1702E-12  0.3845E-11  0.2801E-07 -0.3941E-07  0.5405E-08 -0.6730E-11  0.1274E-10 -0.1072E-11
   21  0.3914E-08  0.1016E-08  0.3633E-08 -0.2899E-13  0.7440E-11  0.2282E-08 -0.3527E-08  0.4502E-09 -0.4474E-11  0.1915E-11 -0.2284E-12
   22  0.3317E-09  0.8638E-10  0.3042E-09 -0.3399E-14  0.7951E-12  0.1917E-09 -0.2992E-09  0.3792E-10 -0.5066E-12 -0.3319E-12  0.9123E-12
   23  0.2657E-10  0.6914E-11  0.2375E-10 -0.3055E-15  0.5099E-13  0.1548E-10 -0.2456E-10  0.4503E-11 -0.2842E-13 -0.2358E-13  0.6317E-13
   24  0.5665E-11  0.1154E-11  0.5400E-11 -0.2624E-16  0.6387E-14  0.3791E-11 -0.4731E-11  0.8770E-12 -0.3852E-14 -0.8600E-14  0.1589E-13
   25  0.2825E-12  0.7191E-13  0.2435E-12  0.2536E-18  0.4410E-16  0.1719E-12 -0.2665E-12  0.6369E-13 -0.2408E-16 -0.1902E-15  0.3495E-15
   26  0.1617E-12  0.3969E-13  0.1465E-12  0.2384E-18  0.5044E-16  0.9532E-13 -0.1422E-12  0.2067E-13 -0.2861E-16 -0.2061E-16  0.3703E-16
   27  0.1981E-14  0.6072E-15  0.1560E-14  0.2619E-19  0.5370E-18  0.1054E-14 -0.1952E-14  0.3341E-15 -0.4459E-18 -0.1294E-17  0.2188E-17
   28  0.2148E-14  0.6168E-15  0.1836E-14  0.2300E-20  0.3204E-18  0.1093E-14 -0.1979E-14  0.2171E-15 -0.1820E-18  0.8214E-19 -0.1047E-18
   29  0.5049E-17  0.2156E-17  0.3138E-17  0.1574E-21  0.5019E-20  0.1911E-17 -0.5347E-17  0.5649E-19 -0.3896E-20 -0.8726E-20  0.1340E-19
   30  0.1398E-16  0.4509E-17  0.1155E-16 -0.3092E-26  0.1609E-26  0.6281E-17 -0.1337E-16  0.1177E-17 -0.1057E-26  0.1911E-25  0.1430E-26
-----------------------------------------------------------------------------------------------------------------------------------------

-----------------------------------------------------------------------------------------------------------------------------------------
pol.out
-----------------------------------------------------------------------------------------------------------------------------------------
          0.00       60.8880        0.0000       60.6761        0.0000       -0.0000        0.9965        0.0000
          1.00       60.7728       -0.0046       60.5608        0.0012        0.0001        0.9965        0.0000
          2.00       60.4288       -0.0182       60.2163        0.0049        0.0003        0.9965        0.0001
          3.00       59.8601       -0.0407       59.6467        0.0108        0.0007        0.9964        0.0002
          4.00       59.0737       -0.0715       58.8590        0.0188        0.0012        0.9964        0.0003
          5.00       58.0789       -0.1101       57.8627        0.0287        0.0019        0.9963        0.0005
          6.00       56.8877       -0.1557       56.6696        0.0400        0.0027        0.9962        0.0007
          7.00       55.5142       -0.2073       55.2938        0.0524        0.0037        0.9960        0.0009
          8.00       53.9742       -0.2641       53.7512        0.0655        0.0049        0.9959        0.0012
          9.00       52.2854       -0.3250       52.0594        0.0789        0.0062        0.9957        0.0015
         10.00       50.4667       -0.3889       50.2374        0.0920        0.0077        0.9955        0.0018
         11.00       48.5378       -0.4546       48.3049        0.1044        0.0094        0.9952        0.0021
         12.00       46.5192       -0.5212       46.2824        0.1156        0.0112        0.9949        0.0025
         13.00       44.4317       -0.5875       44.1907        0.1254        0.0132        0.9946        0.0028
         14.00       42.2959       -0.6526       42.0504        0.1332        0.0154        0.9942        0.0031
         15.00       40.1321       -0.7155       39.8818        0.1389        0.0178        0.9938        0.0035
         16.00       37.9597       -0.7756       37.7046        0.1421        0.0204        0.9933        0.0037
         17.00       35.7975       -0.8320       35.5372        0.1427        0.0232        0.9927        0.0040
         18.00       33.6627       -0.8843       33.3972        0.1406        0.0263        0.9921        0.0042
         19.00       31.5712       -0.9321       31.3003        0.1358        0.0295        0.9914        0.0043
         20.00       29.5373       -0.9750       29.2610        0.1284        0.0330        0.9906        0.0043
         21.00       27.5735       -1.0131       27.2917        0.1185        0.0367        0.9898        0.0043
         22.00       25.6905       -1.0462       25.4032        0.1064        0.0407        0.9888        0.0041
         23.00       23.8970       -1.0745       23.6043        0.0922        0.0450        0.9878        0.0039
         24.00       22.2000       -1.0982       21.9018        0.0764        0.0495        0.9866        0.0034
         25.00       20.6043       -1.1176       20.3008        0.0593        0.0542        0.9853        0.0029
         26.00       19.1132       -1.1331       18.8044        0.0413        0.0593        0.9838        0.0022
         27.00       17.7281       -1.1451       17.4141        0.0229        0.0646        0.9823        0.0013
         28.00       16.4489       -1.1540       16.1298        0.0044        0.0702        0.9806        0.0003
         29.00       15.2740       -1.1605       14.9499       -0.0136        0.0760        0.9788       -0.0009
         30.00       14.2005       -1.1648       13.8715       -0.0308        0.0820        0.9768       -0.0022
         31.00       13.2243       -1.1674       12.8905       -0.0468        0.0883        0.9748       -0.0035
         32.00       12.3406       -1.1689       12.0020       -0.0612        0.0947        0.9726       -0.0050
         33.00       11.5437       -1.1695       11.2003       -0.0737        0.1013        0.9702       -0.0064
         34.00       10.8273       -1.1695       10.4792       -0.0841        0.1080        0.9678       -0.0078
         35.00       10.1849       -1.1692        9.8319       -0.0921        0.1148        0.9653       -0.0090
         36.00        9.6095       -1.1688        9.2518       -0.0977        0.1216        0.9628       -0.0102
         37.00        9.0944       -1.1684        8.7318       -0.1008        0.1285        0.9601       -0.0111
         38.00        8.6326       -1.1681        8.2651       -0.1013        0.1353        0.9574       -0.0117
         39.00        8.2177       -1.1679        7.8451       -0.0993        0.1421        0.9547       -0.0121
         40.00        7.8433       -1.1677        7.4656       -0.0949        0.1489        0.9518       -0.0121
         41.00        7.5036       -1.1675        7.1206       -0.0883        0.1556        0.9490       -0.0118
         42.00        7.1931       -1.1670        6.8047       -0.0796        0.1622        0.9460       -0.0111
         43.00        6.9069       -1.1663        6.5130       -0.0692        0.1689        0.9430       -0.0100
         44.00        6.6407       -1.1650        6.2412       -0.0572        0.1754        0.9398       -0.0086
         45.00        6.3908       -1.1630        5.9854       -0.0439        0.1820        0.9366       -0.0069
         46.00        6.1538       -1.1602        5.7426       -0.0297        0.1885        0.9332       -0.0048
         47.00        5.9272       -1.1564        5.5100       -0.0149        0.1951        0.9296       -0.0025
         48.00        5.7086       -1.1514        5.2855        0.0003        0.2017        0.9259        0.0001
         49.00        5.4965       -1.1451        5.0674        0.0156        0.2083        0.9219        0.0028
         50.00        5.2896       -1.1375        4.8545        0.0306        0.2150        0.9177        0.0058
         51.00        5.0870       -1.1284        4.6460        0.0452        0.2218        0.9133        0.0089
         52.00        4.8883       -1.1180        4.4413        0.0591        0.2287        0.9086        0.0121
         53.00        4.6931       -1.1061        4.2403        0.0721        0.2357        0.9035        0.0154
         54.00        4.5015       -1.0928        4.0430        0.0840        0.2428        0.8982        0.0187
         55.00        4.3136       -1.0783        3.8496        0.0948        0.2500        0.8924        0.0220
         56.00        4.1298       -1.0625        3.6605        0.1044        0.2573        0.8864        0.0253
         57.00        3.9505       -1.0458        3.4760        0.1126        0.2647        0.8799        0.0285
         58.00        3.7761       -1.0281        3.2967        0.1195        0.2723        0.8730        0.0316
         59.00        3.6071       -1.0097        3.1229        0.1250        0.2799        0.8658        0.0347
         60.00        3.4439       -0.9907        2.9553        0.1293        0.2877        0.8581        0.0375
         61.00        3.2870       -0.9714        2.7941        0.1323        0.2955        0.8500        0.0402
         62.00        3.1367       -0.9519        2.6398        0.1341        0.3035        0.8416        0.0428
         63.00        2.9933       -0.9323        2.4926        0.1349        0.3115        0.8327        0.0451
         64.00        2.8569       -0.9128        2.3527        0.1347        0.3195        0.8235        0.0472
         65.00        2.7278       -0.8936        2.2202        0.1337        0.3276        0.8139        0.0490
         66.00        2.6059       -0.8748        2.0952        0.1319        0.3357        0.8040        0.0506
         67.00        2.4912       -0.8565        1.9776        0.1295        0.3438        0.7938        0.0520
         68.00        2.3835       -0.8387        1.8672        0.1267        0.3519        0.7834        0.0531
         69.00        2.2827       -0.8215        1.7638        0.1234        0.3599        0.7727        0.0541
         70.00        2.1884       -0.8050        1.6672        0.1199        0.3678        0.7618        0.0548
         71.00        2.1005       -0.7891        1.5770        0.1163        0.3757        0.7508        0.0553
         72.00        2.0184       -0.7740        1.4929        0.1125        0.3835        0.7397        0.0557
         73.00        1.9419       -0.7595        1.4145        0.1088        0.3911        0.7284        0.0560
         74.00        1.8705       -0.7455        1.3414        0.1051        0.3986        0.7171        0.0562
         75.00        1.8038       -0.7322        1.2731        0.1016        0.4059        0.7058        0.0563
         76.00        1.7414       -0.7194        1.2093        0.0982        0.4131        0.6944        0.0564
         77.00        1.6829       -0.7070        1.1495        0.0950        0.4201        0.6831        0.0564
         78.00        1.6279       -0.6949        1.0934        0.0920        0.4269        0.6717        0.0565
         79.00        1.5760       -0.6832        1.0405        0.0892        0.4335        0.6602        0.0566
         80.00        1.5269       -0.6716        0.9906        0.0867        0.4399        0.6488        0.0568
         81.00        1.4802       -0.6603        0.9433        0.0843        0.4461        0.6373        0.0570
         82.00        1.4356       -0.6490        0.8983        0.0822        0.4520        0.6257        0.0572
         83.00        1.3930       -0.6377        0.8555        0.0802        0.4578        0.6141        0.0575
         84.00        1.3520       -0.6264        0.8145        0.0783        0.4633        0.6024        0.0579
         85.00        1.3125       -0.6150        0.7751        0.0766        0.4686        0.5906        0.0584
         86.00        1.2743       -0.6035        0.7373        0.0750        0.4736        0.5786        0.0588
         87.00        1.2372       -0.5918        0.7008        0.0734        0.4783        0.5664        0.0594
         88.00        1.2012       -0.5800        0.6656        0.0719        0.4828        0.5541        0.0599
         89.00        1.1662       -0.5680        0.6316        0.0704        0.4870        0.5416        0.0604
         90.00        1.1321       -0.5558        0.5987        0.0689        0.4910        0.5289        0.0609
         91.00        1.0988       -0.5435        0.5669        0.0674        0.4946        0.5159        0.0614
         92.00        1.0664       -0.5309        0.5361        0.0659        0.4979        0.5027        0.0618
         93.00        1.0348       -0.5183        0.5063        0.0643        0.5009        0.4893        0.0621
         94.00        1.0039       -0.5055        0.4774        0.0626        0.5035        0.4756        0.0624
         95.00        0.9739       -0.4926        0.4496        0.0609        0.5058        0.4616        0.0625
         96.00        0.9446       -0.4797        0.4227        0.0591        0.5078        0.4474        0.0625
         97.00        0.9162       -0.4667        0.3967        0.0572        0.5093        0.4330        0.0624
         98.00        0.8886       -0.4536        0.3717        0.0552        0.5105        0.4182        0.0621
         99.00        0.8618       -0.4407        0.3476        0.0532        0.5113        0.4033        0.0617
        100.00        0.8359       -0.4277        0.3244        0.0511        0.5117        0.3881        0.0611
        101.00        0.8108       -0.4149        0.3022        0.0489        0.5117        0.3727        0.0603
        102.00        0.7866       -0.4021        0.2809        0.0467        0.5112        0.3571        0.0593
        103.00        0.7633       -0.3895        0.2605        0.0444        0.5103        0.3413        0.0582
        104.00        0.7408       -0.3771        0.2410        0.0421        0.5090        0.3253        0.0568
        105.00        0.7191       -0.3648        0.2224        0.0398        0.5073        0.3092        0.0553
        106.00        0.6983       -0.3527        0.2046        0.0375        0.5051        0.2930        0.0536
        107.00        0.6784       -0.3408        0.1876        0.0351        0.5024        0.2766        0.0518
        108.00        0.6592       -0.3292        0.1715        0.0328        0.4994        0.2602        0.0497
        109.00        0.6409       -0.3178        0.1562        0.0304        0.4959        0.2436        0.0475
        110.00        0.6234       -0.3067        0.1416        0.0281        0.4919        0.2271        0.0451
        111.00        0.6066       -0.2958        0.1277        0.0259        0.4876        0.2105        0.0426
        112.00        0.5906       -0.2851        0.1146        0.0236        0.4828        0.1940        0.0400
        113.00        0.5753       -0.2747        0.1021        0.0214        0.4776        0.1775        0.0372
        114.00        0.5607       -0.2646        0.0903        0.0193        0.4720        0.1610        0.0343
        115.00        0.5467       -0.2548        0.0791        0.0171        0.4660        0.1446        0.0314
        116.00        0.5334       -0.2452        0.0685        0.0151        0.4596        0.1284        0.0283
        117.00        0.5208       -0.2358        0.0585        0.0131        0.4528        0.1123        0.0251
        118.00        0.5087       -0.2267        0.0490        0.0111        0.4457        0.0963        0.0219
        119.00        0.4971       -0.2178        0.0400        0.0092        0.4382        0.0805        0.0186
        120.00        0.4861       -0.2092        0.0316        0.0074        0.4304        0.0649        0.0153
        121.00        0.4756       -0.2008        0.0236        0.0057        0.4222        0.0496        0.0119
        122.00        0.4656       -0.1927        0.0160        0.0039        0.4138        0.0344        0.0085
        123.00        0.4561       -0.1847        0.0089        0.0023        0.4050        0.0196        0.0050
        124.00        0.4470       -0.1770        0.0022        0.0007        0.3960        0.0050        0.0016
        125.00        0.4383       -0.1695       -0.0041       -0.0008        0.3867       -0.0093       -0.0019
        126.00        0.4301       -0.1622       -0.0100       -0.0023        0.3771       -0.0233       -0.0054
        127.00        0.4222       -0.1551       -0.0156       -0.0037        0.3673       -0.0370       -0.0088
        128.00        0.4147       -0.1482       -0.0209       -0.0051        0.3573       -0.0504       -0.0123
        129.00        0.4075       -0.1414       -0.0259       -0.0064        0.3470       -0.0635       -0.0158
        130.00        0.4007       -0.1348       -0.0306       -0.0077        0.3365       -0.0763       -0.0192
        131.00        0.3942       -0.1284       -0.0350       -0.0089        0.3258       -0.0889       -0.0226
        132.00        0.3880       -0.1222       -0.0392       -0.0101        0.3150       -0.1011       -0.0260
        133.00        0.3822       -0.1162       -0.0432       -0.0112        0.3039       -0.1131       -0.0294
        134.00        0.3766       -0.1102       -0.0470       -0.0123        0.2927       -0.1248       -0.0328
        135.00        0.3713       -0.1045       -0.0506       -0.0134        0.2814       -0.1363       -0.0361
        136.00        0.3664       -0.0989       -0.0540       -0.0144        0.2699       -0.1475       -0.0393
        137.00        0.3617       -0.0934       -0.0574       -0.0154        0.2583       -0.1586       -0.0425
        138.00        0.3573       -0.0881       -0.0605       -0.0163        0.2466       -0.1694       -0.0457
        139.00        0.3533       -0.0830       -0.0636       -0.0172        0.2348       -0.1801       -0.0487
        140.00        0.3495       -0.0779       -0.0667       -0.0181        0.2230       -0.1907       -0.0517
        141.00        0.3461       -0.0731       -0.0696       -0.0189        0.2111       -0.2011       -0.0545
        142.00        0.3430       -0.0683       -0.0725       -0.0196        0.1992       -0.2113       -0.0572
        143.00        0.3403       -0.0638       -0.0754       -0.0203        0.1874       -0.2214       -0.0598
        144.00        0.3379       -0.0593       -0.0782       -0.0210        0.1756       -0.2314       -0.0621
        145.00        0.3359       -0.0550       -0.0810       -0.0216        0.1639       -0.2412       -0.0643
        146.00        0.3342       -0.0509       -0.0838       -0.0221        0.1523       -0.2508       -0.0661
        147.00        0.3330       -0.0469       -0.0867       -0.0226        0.1410       -0.2603       -0.0678
        148.00        0.3322       -0.0431       -0.0895       -0.0229        0.1298       -0.2694       -0.0691
        149.00        0.3318       -0.0395       -0.0924       -0.0232        0.1190       -0.2784       -0.0700
        150.00        0.3319       -0.0360       -0.0952       -0.0234        0.1085       -0.2870       -0.0706
        151.00        0.3324       -0.0327       -0.0981       -0.0235        0.0984       -0.2952       -0.0708
        152.00        0.3333       -0.0296       -0.1010       -0.0236        0.0887       -0.3031       -0.0707
        153.00        0.3348       -0.0266       -0.1039       -0.0235        0.0794       -0.3105       -0.0701
        154.00        0.3367       -0.0238       -0.1069       -0.0232        0.0707       -0.3174       -0.0690
        155.00        0.3391       -0.0212       -0.1098       -0.0229        0.0625       -0.3239       -0.0676
        156.00        0.3419       -0.0188       -0.1127       -0.0225        0.0549       -0.3297       -0.0658
        157.00        0.3451       -0.0165       -0.1156       -0.0219        0.0478       -0.3350       -0.0636
        158.00        0.3488       -0.0144       -0.1185       -0.0213        0.0414       -0.3398       -0.0610
        159.00        0.3529       -0.0125       -0.1214       -0.0205        0.0355       -0.3439       -0.0581
        160.00        0.3574       -0.0108       -0.1242       -0.0196        0.0302       -0.3475       -0.0549
        161.00        0.3621       -0.0092       -0.1269       -0.0186        0.0255       -0.3505       -0.0514
        162.00        0.3672       -0.0078       -0.1296       -0.0176        0.0213       -0.3530       -0.0478
        163.00        0.3725       -0.0066       -0.1322       -0.0164        0.0177       -0.3550       -0.0440
        164.00        0.3780       -0.0055       -0.1348       -0.0152        0.0145       -0.3565       -0.0402
        165.00        0.3836       -0.0045       -0.1372       -0.0139        0.0118       -0.3576       -0.0363
        166.00        0.3893       -0.0037       -0.1395       -0.0126        0.0094       -0.3583       -0.0324
        167.00        0.3950       -0.0029       -0.1417       -0.0113        0.0075       -0.3587       -0.0285
        168.00        0.4006       -0.0023       -0.1438       -0.0099        0.0058       -0.3589       -0.0248
        169.00        0.4061       -0.0018       -0.1457       -0.0086        0.0045       -0.3588       -0.0212
        170.00        0.4114       -0.0014       -0.1475       -0.0073        0.0034       -0.3585       -0.0178
        171.00        0.4164       -0.0011       -0.1491       -0.0061        0.0025       -0.3581       -0.0146
        172.00        0.4211       -0.0008       -0.1506       -0.0049        0.0018       -0.3576       -0.0117
        173.00        0.4254       -0.0005       -0.1519       -0.0038        0.0013       -0.3571       -0.0090
        174.00        0.4292       -0.0004       -0.1530       -0.0029        0.0009       -0.3566       -0.0067
        175.00        0.4326       -0.0002       -0.1540       -0.0020        0.0006       -0.3560       -0.0047
        176.00        0.4354       -0.0001       -0.1548       -0.0013        0.0003       -0.3556       -0.0030
        177.00        0.4376       -0.0001       -0.1555       -0.0007        0.0002       -0.3552       -0.0017
        178.00        0.4392       -0.0000       -0.1559       -0.0003        0.0001       -0.3549       -0.0008
        179.00        0.4402       -0.0000       -0.1562       -0.0001        0.0000       -0.3548       -0.0002
        180.00        0.4406        0.0000       -0.1563        0.0000       -0.0000       -0.3547        0.0000
------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------
sca.out
---------------------------------------------------------
   1.257  0.4046E+01  0.5119E+01  0.1072E+01  0.5411-311
---------------------------------------------------------

-------------------------------------------------------------------
sca_final.out
-------------------------------------------------------------------
 1.257 4.046 5.119 1.072 0.4118336 0.52105194 0.10911657 0.79038876
-------------------------------------------------------------------
********************************************************************************************************************************************
NOTE: The brief description of all the input and output files are given in the list of files.

Documentation
-------------

JaSTA is fully documented in the JaSTA manual, which is contained
in this distribution as the file JaSTA_manual.pdf. There is information 
about the documentation online in the following link.

  http://cpc.cs.qub.ac.uk/summaries/AETB_v1_0.html


Development
-----------

JaSTA development is hosted by Mendeley Data under Computer Physics Communications

http://cpc.cs.qub.ac.uk/summaries/AETB_v1_0.html

Bug Reporting
-------------

You can send JaSTA bug reports to <prithishh3@gmail.com>. 

-------------------------------------------------------------------------------
Copyright (C) 2007 Free Software Foundation,
Inc.
This file is part of JaSTA.

JaSTA is free software; you can redistribute it and/or modify it under the
terms of the GNU General Public License as published by the Free Software
Foundation; either version 3, or (at your option) any later version.

JaSTA is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR
A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
JaSTA; see the file COPYING.  If not, write to the Free Software
Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA 02110-1301 USA.
