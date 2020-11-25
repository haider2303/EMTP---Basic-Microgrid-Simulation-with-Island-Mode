# EMTP---Basic-Microgrid-Simulation-with-Island-Mode

MAIN FILE: MicroGrid.ecf

FolderName: Simulations

Library: Install the .exe file in MicroGridLib folder in the location where EMTP-RV is present.


This project contains the basic modeling of Microgrid in EMTP-RV. In order to run it, the Microgrid library must be installed in EMTP-RV.
All the parameters regarding the components are included with an excel file. 

Gerneral observations:
Whenever the system shifts to Island mode, their is a very short transient period that can be seen as a spike in voltage and power graphs. The reason is that distributed generation kicks in at that particular moment.
