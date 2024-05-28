# Z-Stack-firmware
Z-Stack-firmware 460800bps mod<br>
Custom coordinator firmware based on https://github.com/Koenkk/Z-Stack-firmware

**SONOFF Zigbee 3.0 USB Dongle Plus-P**<br>
CC1352P2_CC2652P_launchpad_coordinator_*.zip<br>
zigbee2mqtt 
```yaml
serial:
  port: >-
    /dev/serial/by-id/usb-Silicon_Labs_Sonoff_Zigbee_3.0_USB_Dongle_Plus_0001-if00-port0
  baudrate: 460800
```
**SLZB-06**<br>
CC1352P2_CC2652P_other_coordinator_*.zip<br>
After CC2652P firmware update set baudrate to 460800bps<br>

```System and Tools -> System Tools -> File Brouser -> File : configSerial.json```<br>
{"baud":460800,"port":6638}<br>
```Save```

