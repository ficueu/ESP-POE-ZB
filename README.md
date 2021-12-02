# ESP-POE-ZB
ESP32 POE: ZigBee + BLE gateway

Features:
* ESP32-S (with external antenna connector) used as BLE receiver, main gateway controller,
* Ebyte E72-2G4M20S1E (CC2652p added external connector) as ZigBee coordinator,
* POE 802.3af with LAN8720,
* USBC for flashing, based on CH340C (can be used for powering),
* connector for powering 10-57 VDC (abs max 70V - needs to replace capacitor),
* connectors: 3xGPIO (internal pulled up, for SCL, SDA, 1Wire), 3.3V, 5V, GND,
* internal connector: SCL, SDA, 3.3V, GND,
* compatibile with Kradex Z102 enclosure for din rail.

Pinout:
```
i2c:
  sda: 14
  scl: 13

dallas:
  - pin: 16
```

![alt text](https://obrazki.elektroda.pl/4374662700_1638476744_bigthumb.jpg)


![alt text](https://obrazki.elektroda.pl/5504499500_1638476324_bigthumb.jpg)
