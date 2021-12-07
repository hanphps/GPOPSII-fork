# GPOPSII-fork
GPOPS cannot run specific commands (MEX) unless using 2019 or earlier. Latest GPOP release has some issues relating to using older MATLAB versions

# Current Issues Fixed

adigatorGenFiles4gpops2.m does not adequately check if a field exist. It assumes once field exists, subfields exist. 
Fixed specific issues on line 78 & 81
