### this is an attempt to reduce the costs in a 2 Photon microscope

#### given developments in hardware, there is potential space to use affordable tools to substitute components tradionally used in 2P microscopes:
##### Galvanomotors that drive the scanning mirrors - current alternative: galvos for laser shows (~75€)
##### signal amplifiers for PMTs - current alternative RedPitaya
##### IO Boards for driving motors and digitizing data: current alternative Red Pitaya (200€-300€)



software:
luckly someone already wrote what seems to be a very well documented API for python and the Red Pitaya: PyRPL http://pyrpl.readthedocs.io/en/latest/index.html
this project starts with that, in the hope to leverage from open source tools and contribute to their further development.


#####pmt:
http://sensl.com/downloads/ds/DS-MicroMseries.pdf
http://sensl.com/downloads/ds/UM-MicroM.pdf
http://sensl.com/downloads/ds/APP-Biophotonics.pdf
http://sensl.com/applications/biophotonics/
http://www.sensl.com/downloads/irp/2012_Li_SPM_Detection_Low_Level_Bioluminescence_Development_Deployable_Whole_cell_biosensors.pdf
http://www.gaudi.ch/GaudiLabs/?page_id=718



------------------------------ outdated-------------------------------------------
This setup uses a Red Pitaya to generate waveforms (eventually will be used to collect data as well) and galvo motors that can be bought on ebay - the ideia is to try their performance with the same movement used in 2 photon microscopes.



Useful information about how to write code to control the redpitaya with code can be found here:
http://redpitaya.readthedocs.io/en/latest/appsFeatures/remoteControl/remoteControl.html



