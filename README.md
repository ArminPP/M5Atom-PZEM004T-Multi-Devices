# Reading 3 PZEM004T V3 devices with an ESP32 without any modification

## It is possible to use the PZEM004T with 3.3V for serial communication without changing or adding some resistors or cuting some wires...
In this quick & dirty example I use 3 devices with different addresses (0x01 - 0x03) to monitor the Solar, the power grid and the consumption of my house.

The measured data will be sent every 10s to EmonCMS.

