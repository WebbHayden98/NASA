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

 
Hayden Copy: (990 characters out of 1500)
The objective of this research is to establish a better understanding of the current work available in the field of the Cosmic Microwave Background (CMB). Our thesis is that, while the current state of research has a created a base for the understanding of the CMB, more work is necessary through the use of computer science methods to expand upon the field. Our method o study is a literature review. We began our review with the Lambda group, a part of NASA's High Energy Astrophysics Science Archive Research Center. We extended our research to include literature related to the Wilkinson Microwave Anisotropy Probe. Our preliminary work suggests that NASA holds a wealth of information on this topic and has made it freely available to the public. Through our partnership with the OneOklahoma Cyberinfrastructure Initiative (OneOCII), we have access to the network and computing power to reproduce some of the analysis completed by this team and then expand on the current body of work.


## Review Articles
Gary Hinshaw- WMAP Leads

First-Year Wilkinson Microwave Anisotropy Probe (WMAP)* Observations: Preliminary Maps and Basic Results
http://iopscience.iop.org/article/10.1086/377253/pdf

Forward Search- Cited by 12067

FIVE-YEAR WILKINSON MICROWAVE ANISOTROPY PROBE * OBSERVATIONS: COSMOLOGICAL INTERPRETATION
http://iopscience.iop.org/article/10.1088/0067-0049/180/2/330/pdf

Dynamics of dark energy
https://arxiv.org/pdf/hep-th/0603057.pdf

Type Ia Supernova Discoveries at z > 1 from the Hubble Space Telescope: Evidence for Past Deceleration and Constraints on Dark Energy Evolution*
https://arxiv.org/pdf/astro-ph/0402512.pdf

Backward Search-

Local properties of the large-scale peaks of the CMB temperature
http://iopscience.iop.org/article/10.1088/1475-7516/2017/05/023/pdf

Multiscale analysis of the CMB temperature derivatives
http://iopscience.iop.org/article/10.1088/1475-7516/2017/02/026/pdf

Top referenced CMB articles

Maps of Dust Infrared Emission for Use in Estimation of Reddening and Cosmic Microwave Background Radiation Foregrounds
http://iopscience.iop.org/article/10.1086/305772/pdf

Forward Search- Cited by 12858

The Sloan Digital Sky Survey: Technical Summary
http://iopscience.iop.org/article/10.1086/301513/pdf

Stellar population synthesis at the resolution of 2003
https://watermark.silverchair.com/344-4-1000.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAd8wggHbBgkqhkiG9w0BBwagggHMMIIByAIBADCCAcEGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMBjvscytbL7sOiFObAgEQgIIBksj1OPLpTEnzmuJkoSxcGk1Mv6HoF78aSmEu3haew7edm8lI-HGTKxnMAskhpAhrrs3yw7WvPsWmWKhIZg2f0zTGQjp43OSktP7xPKpUsjpObbtwaCMk_Z3eCpo7HTx2W2yKSkKLY3szLeq0QmbZQjqCAeG4V49FipNElH45GTi_mW-In2G5vUAVsmRe785JyGnuzFfozfsRVl6-dmKHhaSXCub5zfFAfjV4UNN297WzoErCdIBmAkJNwOZjenDFQB_H_SA5rRf6eiPyULYiLEy2KkQnOZnIArR27J8HDqkvzCiu0-URaUGKdWIkiymsDE6-meap41VvaCNLO553UKIzLmkufkutZ8cqx67dILo-NEBbsDTMDoJ9LNJNLfX4X6V3kRDZuSoWQ1KEJGnqYuDMA1AbUlUUkB3PLJ58sk_2q1krNFe-KLYBcP_XWCPXqV6oTX5wAlLlwmfG9oT0xhY35WNwAFhp0CeuYSUcdNuQ5Gd6UqAfv74Q2yfpZrHoCjAvDh6lNkJc8u_vwiP9LwalIQ

Backward Search-

Sloan Digital Sky Survey IV: Mapping the Milky Way, Nearby Galaxies, and the Distant Universe
http://iopscience.iop.org/article/10.3847/1538-3881/aa7567/pdf
