# MILSurvey

This is the Matlab code used for the experiments in the paper:
[1] M.-A. Carbonneau, V. Cheplygina, E. Granger, and G. Gagnon, “Multiple Instance Learning: A Survey of Problem Characteristics and Applications,” ArXiv e-prints, vol. abs/1612.0, 2016. 


This code has dependencies on various toolboxes:

1) The MIL Toolbox
This is where some of the algorithm implementation come from.  
http://prlab.tudelft.nl/david-tax/mil.html  
[2] C. V Tax D.M.J., “{MIL}, A {M}atlab Toolbox for Multiple Instance Learning.” Jun-2016. 

2) The PRTools
This is necessary to run the MIL Toolbox.  
http://prtools.org/

3) Dd_tools
This is necessary to run the MIL Toolbox.  
http://prlab.tudelft.nl/david-tax/dd_tools.html  
[3] D. M. J. Tax, “DDtools, the Data Description Toolbox for Matlab.” Jun-2015.

4) LIBSVM
This is the implementation used for all SVM in the experiments. (I removed some console prints and recompiled. I included my version in the repository)
https://www.csie.ntu.edu.tw/~cjlin/libsvm/  
[4] C.-C. Chang and C.-J. Lin, “LIBSVM: A Library for Support Vector Machines,” ACM Trans. Intell. Syst. Technol., vol. 2, no. 3, May 2011.

5) EMD
A package for earth mover's distance. (I changed some settings in the code to be able to deal with larger data set. I included my version in the repository) 
http://www.mathworks.com/matlabcentral/fileexchange/12936-emd-earth-movers-distance-mex-interface

6) VLFeat 
This is used only for the implementation of k-means in RSIS. It can be replaced by any other implementation if necessary.  
http://www.vlfeat.org/  
[5] A. Vedaldi and B. Fulkerson, “{VLFeat}: An Open and Portable Library of Computer Vision Algorithms.” 2008.
