It is almost garenteed that you will need to modify things in order to set up this skin to function properly. 

First of all, Prerequisites:
You will need HWiNFO installed and the sensors viewer needs to be running. "Shared Memory Support" needs to be
enabled in HWiNFO's settings. Some sort of nice text formatting software like notepad++ would be nice for editting
the skin's ini file, but not absolutely necessary. 

Setup:
You will need to use the included shared memory viewer program named "HWiNFOSharedMemoryViewer.exe"
The IDs for viewing the HWiNFO shared memory will need to be changed. They are located at ..Rainmeter\Skins\HWiNFO GPU skin\SensorIDs.inc 
Here are the cooresponding IDs that need to be changed in the SensorIDs .inc file:

GPU0ID = Your GPU ID in the Sensor Details
GPU0Instance = The Instance under your GPU Sensor Details
GPU0TempID = Extend your GPU tree and click GPU Temperature and put the Entry Details ID here
GPU0VoltageID = Also in the GPU tree, this is the GPU Core Voltage Entry Details ID
GPU0ClockID = GPU Clock Entry Details ID in the GPU tree
GPU0LoadId = GPU Core Load Entry Details ID
GPU0MemUsageID = GPU Memory Allocated Entry Details ID

Also there is no gpu vram in HWiNFO's sensors so if it bothers you and you don't have 2gb of vram you'll have to change it yourself in the GPU.ini and in the MeasureTotalVRAM measure change it to the current number. (mb = gb * 1024)

yeah GPU0LoadId isn't caps... im too lazy to go back and fix it now. just leave it ._.

whelp yeah if you configured all the IDs properly with the memory viewer program everything else should just work...


