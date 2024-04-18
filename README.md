# I2C Interface with 20x4 Charcter Display 

## Overview

This example demonstrates basic usage of I2C driver by reading and writing to a 20x4 character display. Here ESP32 is used as a master device and character display is used as a slave device.

## How to use example

### Hardware Required

To run this example, you should have one ESP32, ESP32-S or ESP32-C based development board, Character Display, USB cable and other required cables for master-slave connections.

The Character Displays operates at 5V Input supply hence 5V source is required for the input to the Display.

#### Pin Assignment:

The following pin assignments are used by default, you can change these in the `menuconfig` .

- SDA Pin -> I2C_MASTER_SDA -> GPIO_NUM_15
- SCL Pin -> I2C_MASTER_SCL -> GPIO_NUM_2
- Clock Speed -> 400000

### Build and Flash

Enter `idf.py -p PORT flash monitor` to build, flash and monitor the project.

(To exit the serial monitor, type ``Ctrl-]``.)

## Example Output

```bash
You will see below output strings on the 20x4 Character Display.
- HELLO WORLD!
- FROM ESP32
- I2C COMMUNICATION
- !!WELCOME!!
```

