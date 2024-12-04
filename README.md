# MQC
## 4 Pin JST SH Interface
![MQC](assets/MQC.png)

## Compatibility
The MQC xChip has 2x 4 pins JST SH connectors allowing interfacing to [Sparkfun's Qwiic](https://www.sparkfun.com/qwiic) and [Adafruit's STEMMA QT](https://learn.adafruit.com/introducing-adafruit-stemma-qt/what-is-stemma-qt), with the following caveats:
- the xChips runs I²C  and 3.3v only.
- the Qwiic also runs I²C  and 3.3V only, so all Sparkfun Qwiic sensors are directly compatible.
- the STEMMA QT runs I²C , but voltage can vary from 3-5V, so before using a STEMMA QT sensor, make sure it is running on 3.3v.

## Usage
### Mounting
The MQC has 4 mounting holes spaced 1" (25.4mm) apart, which is used by most Adafruit and Sparkfun sensors. Use a thick washer or a larger nut as a spacer to mount the sensor on top of the connectors. Notice the "corners" of the nuts in the above image.
### Wiring
Use a standard Qwiic or STEMMA QT cable (as per the image above), to connect to one of the connectors on the MQC and the other end to one of the connectors on the Adafruit/Sparkfun sensor.


