MRI Multiple sclerosis Database (MRI MS DB)
We are making the MRI MS DB available to the research community free of charge. 
If you use this database in your research, we kindly ask that you reference the papers listed below:

Further download information for the database may be obtained by contacting Prof. Christos P. Loizou (panloicy@logosnet.cy.net).
Pre-prints of the publication papers are also available upon request, or can be downlaoded for personal use from the
website of the Laboratory of eHealth of the University of Cyprus, at:
http://www.medinfo.cs.ucy.ac.cy/

MRI MS DB Description:
In the IMT-Segmentation folder there are 38 folders representing data for each patient 38patients).
In each patient folder we have:
1) MRI TIFF Images from first and second examination (0 months, 6-12 months)
2) Lesion segmentations (*.plq files). The delineation/s can be loaded into matlab i.e load(file.plq, '-.mat'); Then points can be drawn on the image.

%How to load the point deliniations into MATLAB and plot them to the image.  
load('IM_00031_1.plq','-mat');
a=imread('IM_00031.tif');
figure, imshow(a), hold on, plot(yi,xi, 'LineWidth', 3), hold off;

Copyright Notice
-----------COPYRIGHT NOTICE STARTS WITH THIS LINE------------
Copyright (c) 2012 Institute of Neurology and Genetics, Nicosia, Cyprus 
All rights reserved.

Permission is hereby granted, without written agreement and without license or royalty fees,
to use, copy, modify, and distribute this database and its documentation for any purpose,
provided that the copyright notice in its entirety appear in all copies of this database,
and the original source of this database, the Laboratory of eHealth at the University
of Cyprus (http://www.medinfo.cs.ucy.ac.cy/) and the Institute of Neurology and Genetics, at 
Nicosia, Cyprus, are acknowledged in any publication that reports research using this database.

The following papers are to be cited in the bibliography whenever parts or the whole database is used as:

• C.P. Loizou, V. Murray, M.S. Pattichis, I. Seimenis, M. Pantziaris, C.S. Pattichis, 
“Multi-scale amplitude modulation-frequency modulation (AM-FM) texture analysis of multiple 
sclerosis in brain MRI images,” IEEE Trans. Inform. Tech. Biomed., vol. 15, no. 1, pp. 119-129, 2011.   
• C.P. Loizou, E.C. Kyriacou, I. Seimenis, M. Pantziaris, S. Petroudi, M. Karaolis, C.S. Pattichis, 
“Brain white matter lesion classification in multiple sclerosis subjects for the prognosis of future disability,” 
Intelligent Decision Technologies Journal (IDT), vol. 7, pp. 3-10, 2013.
• C.P. Loizou, M. Pantziaris, C.S. Pattichis, I. Seimenis, 
“Brain MRI Image normalization in texture analysis of multiple sclerosis”, 
J. Biomed. Graph. & Comput., vol. 3, no.1, pp. 20-34, 2013. 
• C.P. Loizou, S. Petroudi, I. Seimenis, M. Pantziaris, C.S. Pattichis, Quantitative texture analysis of brain 
white matter lesions derived from T2-weighted MR images in MS patients with clinically isolated syndrome”, J. Neuroradiol., 
acepted. 

IN NO EVENT SHALL THE UNIVERSITY OF CYPRUS BE LIABLE TO ANY PARTY FOR DIRECT, INDIRECT,
SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE USE OF THIS DATABASE AND ITS DOCUMENTATION,
EVEN IF THE UNIVERSITY OF CYPRUS HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

THE UNIVERSITY OF CYPRUS SPECIFICALLY DISCLAIMS ANY WARRANTIES, INCLUDING, 
BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE.
THE DATABASE PROVIDED HEREUNDER IS ON AN "AS IS" BASIS, AND THE UNIVERSITY OF CYPRUS 
HAS NO OBLIGATION TO PROVIDE MAINTENANCE, SUPPORT, UPDATES, ENHANCEMENTS, OR MODIFICATIONS.
-----------COPYRIGHT NOTICE ENDS WITH THIS LINE------------
