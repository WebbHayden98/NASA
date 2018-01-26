Daily Notes 6 November 2017:
Today my main focus is looking into the software provided by the WMAP mission
website. Through the instructions provided with the software I have found the
additional programs that need to be installed for me to used the software. These
two programs are HEALPix and The IDL Astronomy User's Library. HEALPix is used
for the pixelization of a sphere. All pixels are equal surface area and use black dots to
show constant latitude rings. HEALPix has been downloaded onto the desktop and
will be installed when I take a look at IDL. I moved on to the software from the NASA github
and Devin showed me how to fix a bug I had encountered with the TestModeMixing.
I have installed openmpi and created a new path so that it should stay after system
restarts this time.

Sites Used:
https://lambda.gsfc.nasa.gov/product/map/current/m_sw.cfm
https://lambda.gsfc.nasa.gov/data/map/dr5/software/widl_v3.1/wmap_idl_installation.txt
https://healpix.jpl.nasa.gov/
https://idlastro.gsfc.nasa.gov/homepage.html

Daily Notes 10 November 2017:
Today began by briefly looking over code academy to refresh on some of the syntax for
python. I then returned to the test programs in the cmd_analysis software taken from
the github repository. After moving the purecls.txt file to my work folder the healpy_ext test
start working without an error. I will need to look into what the values that it returns actually
means.
```
NSIDE = 128
ORDERING = RING in fits file
INDXSCHM = IMPLICIT
NSIDE = 128
ORDERING = RING in fits file
INDXSCHM = IMPLICIT
.
----------------------------------------------------------------------
Ran 1 test in 1.120s

OK
```
I am still having problems with modemixing test, openmpi is still causing some issue when
running the program. I googled the error message and found that the cause may be in the
path I used when downloading openmpi. I ran the install for openmpi several times and tried
varies ways of formating in each step, but none have yet to change the output of modemixing.
After speaking with Devin I am trying to use one of his guides to install mpich would
could solve the problem. While running the install an error message apears after every command
I run, I believe it to be due to the path used by one of the earlier installs.

Sites Used:
https://www.codecademy.com/courses/learn-python/lessons/taking-a-vacation/exercises/pull-it-together-?action=lesson_resume
http://pytom.org/doc/pytom/faq.html
https://github.com/DevinSmoot/HPC-Guides/blob/ubuntu_vm_guide-dev/ubuntu_vm_guide.md
https://stackoverflow.com/questions/36156822/error-when-starting-open-mpi-in-mpi-init-via-python

Daily Notes 4 December 2017:
I emailed Nathan Miller about help with my research and advice on what I should be
working on. Then on Dr. Everet's advice I looked into the U.S. Department of Energy
for potential help and contacts on my work. The Los Alamos National Laboratory
sited professor Hinshaw as the analysis head of WMAP and director of Legacy archive for
LAMBDA.

Sites Used:
https://energy.gov/em/los-alamos-national-laboratory
gsfc-softwarerequest@mail.nasa.gov
https://p25ext.lanl.gov/colloquium_files/hinshaw_abstract.html
http://www.lanl.gov/science-innovation/science-programs/office-of-science-programs/high-energy-physics/theoretical-physics/quantum-field.php
http://www.lanl.gov/science-innovation/science-programs/office-of-science-programs/high-energy-physics/theoretical-physics/neutrino-theory.php
https://science.gsfc.nasa.gov/sed/bio/gary.f.hinshaw
https://www.phas.ubc.ca/users/gary-hinshaw
https://science.energy.gov/~/media/hep/pdf/files/pdfs/tfcrreport.pdf



## Abstract for Oklahoma Reserach Day
We are going to start with the abstract:
ABSTRACT CONTENT (979 characters out of 1500)

The objective of this research is to better understand the current work being done with Cosmic Microwave Background (CMB).
Our thesis is that multiple open research questions remain within the field of CMB, and some are better suited for study using tools from computer science, including artificial intelligence, machine learning, and data science.
Our method of study is a literature review. We began our review with the Lambda group, a part of NASA's High Energy Astrophysics Science Archive Research Center. We extended our research to include literature related to the Wilkinson Microwave Anisotropy Probe. 
Our preliminary work suggests that NASA holds a wealth of information on this topic and has made it freely availible to the public. Through our partnership with the OneOklahoma Cyberinfrastructure Inititive (OneOCII), we have access to the network and computing power to reproduce some of the analysis completed by this team and then expand on the current body of work.

 

Your abstract should include:

1)      Objective of the research;

2)      Thesis or hypothesis;

3)      Methodology or approaches to address the thesis or hypothesis; and

4)      Summary of the findings or relevant results associated with the project.

