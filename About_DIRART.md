DIRART is a relatively large and ambitious project. It was started two years ago as a deformable image registration MATLAB program with simple graphics. After continuous improvements and a few major redesigns, it has become a software package for deformable image registration and adaptive radiotherapy research. The scale of DIRART is relatively large. Up to now, it contains 450+ MATLAB program files with 40000+ program lines, plus many C/C++ programs to interface with ITK (Insight Segmentation and Registration Toolkit) and other software packages.


From users’ standpoint, DIRART is: 1) a collection of DIR (deformable image registration) algorithms under two common frameworks, plus visualization and validation features, 2) an ART (adaptive radiotherapy) toolkit which is able to perform dose and structure remapping, dose accumulation and analysis using the DIR results, 3) a treatment plan viewer with many visualization options, 4) a viewer and verification tool for DIR results that are generated by other DIR and ART software packages, 5) a complimentary package to CERR (Computational Environment for Radiotherapy Research)26 to provide additional DIR and ART functions to CERR. Moreover, by exchanging DICOM-RT data, it could be used an external software tool in addition to the commercial treatment planning systems.


DIRART works very closely to CERR. In fact, it uses many CERR MATLAB functions, especially functions for DICOM-RT import and export, dose metrics computation, etc. Therefore, DIRART requires installation of CERR to be fully functional. Figure 1 outlines the major functions of DIRART and its interactive relationships with CERR, TPS (treatment planning system) and imaging devices.