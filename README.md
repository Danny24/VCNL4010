# VCNL4010 library
*Arduino* library for using the Vishay VCNL4010 sensor. The sensor is a fully integrated proximity and ambient light sensor with infrared emitter, I2C interface and interrupt function in a small package. It is available as a breakout
board from Adafruit at https://www.adafruit.com/product/466.  The actual datasheet for the VCNL4010 is located a http://www.vishay.com/docs/83462/vcnl4010.pdf.

##Ambient light sensing
The ambient light sensor (ALS) return a 16-bit value starting at close to 0 for no light and goes upwards as the light level increases.

##Proximity sensing
The proximity sensor has a range of approximately 200mm (2 cm, or 3/4 of an inch) and goes from 65536 when the closest reflector is touching the device to a value of around 2000 when nothing is being reflected in range.

Details are available at the [GitHub DSFamily Wiki](https://github.com/SV-Zanshin/VCNL4010/wiki)


![Zanshin Logo](https://www.sv-zanshin.com/images/gif/zanshinkanjitiny.gif) <img src="https://www.sv-zanshin.com/images/gif/zanshintext.gif" width="75"/>