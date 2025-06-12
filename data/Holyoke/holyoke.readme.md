This is the readme file attached to the digitized and adjusted data originally published by Dr. Edward A. Holyoke from Salem (Ma. USA) in his meteorological diary.

Holyoke's meteorological diary is published by E. Hale (1833) A Meteorological Journal from the Year 1786 to the Year 1829, inclusive, 
by Edward A. Holyoke, M.D., A.A.S., Mem. Amer. Acad. Arts Sci. 1:107-216.
The digitized data is taken from this publication.

The digitization and homogenization of the data is reported in: van der Schrier, G. and Jones, P. D. (2008) Daily temperature and pressure series 
for Salem, Massachusetts(1786-1829), Climatic Change 87:499-515, doi:10.1007/s10584-007-9292-x
Please refer to this study for details regarding Dr. Holyoke, the position of the instruments in his house and the adjustments made to the data. Please cite this study when using this data. 

A follow-up to this study is: van der Schrier, G. and Jones, P. D. (2008) Storminess and Cold Air Outbreaks in NE America during AD 1790-1820, Geophys. Res. Lett. 35, L02713, doi:10.1029/2007GL032259

*Description of the data*
The original digitized (non-adjusted) data is in the datafiles
-) holyoke.partI.dat
-) holyoke.partII.dat
-) holyoke.descript.dat
-) holyoke.pressure.dat
-) holyoke.temperature.dat

The files holyoke.partI.dat and holyoke.partII.dat contain pressure and thermometer readings from the years 1786-1820 (partI) and thermometer readings from 1821-1829 (partII). The third file contains the description of the weather spanning the period 1786-1829.
Missing pressure data has the value "99.99" and missing temperatures has the value "99". These datafiles reflect the data originally published by Hale (1833).

The format of the data in file holyoke.partI.dat is:
yyyy
      Month                      Month                       Month
 1   pres  pres   te  te  te  te pres  pres   te  te  te  te pres  pres   te te  te  te
 .   .     .      .   .   .   .  .     .      .   .   .   .  .     .      .  .   .   .
31   pres  pres   te  te  te  te pres  pres   te  te  te  te pres  pres   te te  te  te
where "pres" are pressure readings (in inches, two decimals) and "te" are 
thermometer readings (in Fahrenheit, integers)

The observation time for the first measurement was generally noted down as
`eight o'clock', but sometimes `from eight to nine'.  The second observation (for temperature and the state of the weather) is generally made around noon, but sometimes `at one P.M.', `at two P.M.' or `between one and two P.M.'. The third measurement (for temperature and the
state of the weather) is at sunset, and the fourth is uniformly at ten in the evening.

The format of the data in file holyoke.partII.dat is:
yyyy
      Month               Month               Month   
 1    te  te  te  te  te  te  te  te  te  te  te  te  te  te  te
 .    .   .   .   .   .   .   .   .   .   .   .   .   .   .   . 
31    te  te  te  te  te  te  te  te  te  te  te  te  te  te  te
where "te" are thermometer readings (in Fahrenheit, integers)
In contrast to the data in partI, the first of the five thermometer readings denote the measurement taken at night. The second to fifth readings correspond to similar observing times as in PartI.

The files holyoke.pressure.dat and holyoke.temperature.dat give the adjusted pressure and temperatures in mbar with one decimal place and in degrees centigrade with two decimals. Absent values in the pressure records are "9999.9" and in the temperature record "-99.00".

Dr. Gerard van der Schrier
schrier@knmi.nl
February 2011



