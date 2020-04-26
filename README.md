# poe_v2

This holds the EAGLE files and BOM for the airu PoE v2 board.

This board can be configured to work with or without the power over Ethernet (PoE) module. 

For PoE operation, install the AG9900M module (U13). If the Ethernet cable is connected to a PoE modem, it will provide power and data connections for the board.

For standard operation, install the second microUSB (USB2) connection. This USB connection will proovide power, the Ethernet cable will provide a data connection, and both can be routed through the same port of the AirU Housing. 

USB2 can only be used for power. The USB1 connection must be used to program the board.

For more information on programming the boards, read here:
https://github.com/aqandu/airu-v2-fw/tree/PoE
