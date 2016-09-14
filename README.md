# health-sensor-aurora-ble-fota-bootloader
Bootloader for flashing the Totem Health Patch over air. 
Use a programming rig in combination with nRFgo Stuio and a J-Link to flash the BLE bootlaoder on the device.
To be used when 'your firmware' is not flashed correctly using the Nordic Master Controll app. 

Sometimes, when flashing firmware, the device stays in application mode and does not go back to bootloader mode. 
When this happens, the device is no longer visible (as a bluetooth device). 
A reboot using the steps mentioned above are necessary to solve this problem
