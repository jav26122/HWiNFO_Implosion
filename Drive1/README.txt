Configuration of the drive skin is less complex but pretty much the same as configuration for the GPU skin. This will be explained as if you havn't configured any HWiNFO skin before just incase.

Prerequisites:
You will need HWiNFO installed and the sensors viewer needs to be running. "Shared Memory Support" needs to be
enabled in HWiNFO's settings. Some sort of nice text formatting software like notepad++ would be nice for editting
the skin's ini file, but not absolutely necessary. 

Setup:
You will need to use the included shared memory viewer program named "HWiNFOSharedMemoryViewer.exe" which can be found in the @Resources folder or many other places.
The IDs for viewing the HWiNFO shared memory might need to be changed. They are located at ..Rainmeter\Skins\...\Drive1\HWiNFO.inc 
Here are the cooresponding IDs that need to be changed in the SensorIDs .inc file:

Drive-SensorId = The ID under the Sensor Details box of the drive you want to use.
Drive-SensorInstance = The Instance in the Sensor Details box.

Drive-WriteRate = The ID for the Write Rate in the Entry Details box. You may need to expand your drive to select the write rate in the tree.
Drive-ReadRate = The ID for the Read Rate in the Entry Details box. Also located in the tree
Drive1-Activity = The ID for the Total Activity in the Entry Details box.

One more thing that may need to be changed is the Drive Letter in the skin's .ini file. 
Under Variables you can change the DriveLetter to whatever drive letter you want to use.


