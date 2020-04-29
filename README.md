# airu-board

This repo hold the AirU PCB


## NOTE AirU PoE board note:
The AirU PoE board connects GPIO12 to a pull-up resistor, which automatically sets the flash voltage to 1.8v. In order to use this firmware, the VDD_SDIO efuse of the ESP32 must be set using the following command:
```
espefuse.py set_flash_voltage 3.3V
```
