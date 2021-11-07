# Pachhai_etal_2021_Data
This Pachhai_readme20211105.txt file was generated on [20211105] by Surya Pachhai


-------------------
GENERAL INFORMATION
-------------------


1. Title of Dataset 

Data for: Internal structure of ultralow-velocity zones consistent with origin from a basal magma ocean 


2. Author Information

  Principal Investigator Contact Information
        Name: Surya Pachhai
           Institution: University of Utah
           Address: Frederick Albert Sutton Building
                    115 S 1460 E, ROOM 383
                    Salt Lake City, UT 84112-0102
           Email: surya.pachhai@utah.edu

        Name: Mingming Li
           Institution: Arizona State University
           Address: 781 Terrace Mall
                    Tempe, AZ 85287-6004
           Email: Mingming.Li@asu.edu 

        Name:  Michael S. Thorne
           Institution: University of Utah
           Address: Frederick Albert Sutton Building
                    115 S 1460 E, ROOM 383
                    Salt Lake City, UT 84112-0102
           Email: michael.thorne@utah.edu

       Name:  Jan Dettmer
           Institution: Department of Geoscience, University of Calgary 
           Address:  2500 University Drive NW, Calgary  
                     AB T2N 1N4, Canada
           Email: jan.dettmer@ucalgary.ca  
      
       Name:  Hrvoje Tkalcic
           Institution: The Australian National University
           Address:  142 Mills Rd       
                     Acton ACT 0200
                     Canberra, Australia
           Email: hrvoje.tkalcic@anu.edu.au



3. Date of data collection (single date, range, approximate date) <suggested format YYYYMMDD>

Data included here were collected from approximately 20050227 to 20140722.  This collection of data were compiled
from the Seismology and Mathematical Group of the Research School of Earth Sciences, The Australian National University, who deploy the instruments, maintain them, and collect and handle the data from the networks.
The earthquakes used in this study occurred from 2005 to 2014

4. Geographic location of data collection (where was data collected?): Australia.

5. Information about funding sources that supported the analysis of the data:
This work was partially supported by NSF grant EAR-1723081.



--------------------------
SHARING/ACCESS INFORMATION
-------------------------- 


1. Licenses/restrictions placed on the data:
Public Domain

2. Links to publications that cite or use the data:
This collection of data was compiled for:
Surya Pachhai, Mingming Li, Michael S. Thorne, Jan Dettmer, and Hrvoje Tkalcic (2021) Internal structure of ultralow-velocity zones consistent with origin from a basal magma ocean. TBD
3. Links to other publicly accessible locations of the data:
NA


4. Links/relationships to ancillary data sets:
NA

5. Was data derived from another source?
           If yes, list source(s):


6. Recommended citation for the data:
Surya Pachhai, Mingming Li, Michael S. Thorne, Jan Dettmer, and Hrvoje Tkalcic (2021) Internal structure of ultralow-velocity zones consistent with origin from a basal magma ocean. TBD


---------------------
DATA & FILE OVERVIEW
---------------------

Seismic data are provided for 10 earthquakes (see Table S1 in Pachhai et al. 2021) for earthqauke parameters.

Data for each earthquake are provided in their own directory.  The naming convention for each directory is:
yyyymmddhhmm

i.e., the directory name is given in terms of event year, month, day, hour, and minute that the earthquake occurred.

Within each directory the seismograms for that earthquake are stored in Seismic Analysis Code (SAC) format.

Vertical component seismograms are given that are windowed in time around the ScP seismic arrival.

The naming convention of each file is

Final_Alignedstationcode.SAC

  Final_Aligned     = prefix on all the sac files
  stationcode = the seismic station abbreviation
  SAC         = file format (seismic analysis code)

In total: 199 individual seismic recordings are provided.


2. Relationship between files:        


3. Additional related data collected that was not included in the current data package:
NA


4. Are there multiple versions of the dataset? yes/no
no


--------------------------
METHODOLOGICAL INFORMATION
--------------------------


1. Description of methods used for collection/generation of data: 
All of the earthquakes occurred in the Tonga/Fiji trench and were recorded in Australia.  The earthquakes were chosen such that the ScP arrivals are clean with high signal to noise ratio and P does not have complexity.  

All events collected before 2018 were collected as a part of the following work:
Data collection is described in this paper.  Data collected for the 2018 earthquakes followed the same procedure.


2. Methods for processing the data: <describe how the submitted data were generated from the raw or collected data>

Data are initially processed as follows: (1) the mean and trend of the trace is removed, (2) downsampled to 0.05 sec, (3) filtered between 0.5 to 1.5 Hz (4) Deconvolved P wavelet from individual ScP, and (5) aligned all the waveforms using iterative adaptive approach (Rawlinson et al. 2004).

3. Instrument- or software-specific information needed to interpret the data:

These data are written in seismic analysis code (SAC) format. 

4. Standards and calibration information, if appropriate:
NA

5. Environmental/experimental conditions:
NA

6. Describe any quality-assurance procedures performed on the data:
Quality assurance is described in detail in the Extended material of the paper. 

7. People involved with sample collection, processing, analysis and/or submission:
Surya Pachhai
