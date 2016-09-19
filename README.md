# health-sensor-aurora-ble-fota-bootloader
Bootloader for flashing new firmware on the Totem Health Patch over air. 

When the health patch is preflashed with firmware v2, the user no longer needs a J-link and a programmer to flash the device. However, sometimes, flashing firmware over the air goes wrong which results in the device being in a wrong 'state'. when this happens, the device is not visible anymore within the bluetooth application. To solve this problem, a reset needs to be done suing the J-link and programmer. 
