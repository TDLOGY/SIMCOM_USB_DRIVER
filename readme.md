# SIMCOM USB Driver for 4G module

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
