# SIMCOM USB Driver for 4G module

---
__Advertisement__
#### Order easy online at:
- __[TDM-SIM7600CE-M1S](https://linhkienthuduc.com/module-4g-3g-2g-gps-simcom-sim7600ce-m1s-lte-cat-4-ra-chan)__ - 2G/3G/4G LTE CAT 4 GPS BREAKOUT MODULE
- __[TDM-A7600C-L1](https://linhkienthuduc.com/module-4g-3g-2g-simcom-a7600c-l1-lte-cat-1-ra-chan)__ - 2G/3G/4G LTE CAT 1 BREAKOUT MODULE.
- __[A7670C-LASS](https://linhkienthuduc.com/module-4g-simcom-a7670c-lass-da-ra-chan-thay-the-module-sim800l)__ - 2G/3G/4G LTE CAT 1 BREAKOUT MODULE.
----


## Windows (Win10/Win11)

**A7670/A7672/A7600C-L1**
- Please use A7600X-Windows-Driver.7z to install USB Driver
- The driver will contain atleast 2 port UART and RNDIS Driver (Internet):
    - AT Command Port
    - Diagnostic Port
    - NMEA Port - GPS (Optinal)

**SIM7600**
- Please use SIM7600_Windows10_Driver.zip to install USB Driver
- The driver will contain atleast 3 port UART and RNDIS Driver (Internet):
    - AT Command Port
    - Diagnostic Port
    - NMEA Port - GPS


## Linux (Ubuntu/Debian/...)
- The driver have already install with driver: ECM/EEM/RNDIS/NDIS/QMI
- To bring up the internet on linux:

- Command to check usb interface:
```
ip a
```
And check the usb0 interface
- Acquire IP (DHCP) - Optinal if IP is not auto detected:
```
sudo dhclient -v usb0
```
- Acquire DNS - Optional
```
sudo route add -net 0.0.0.0 usb0
```
