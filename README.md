# MCP23017_PCB

This Printed Circuit Board project is sponsored by JLCPCB. Please visit https://jlcpcb.com/RAT to order your PCB.

The MCP23017 PCB consists of 8 16-Bit I/O Expander with Serial Interface MCP23017 chips.

What is an MCP23017 chip?

It is an integrated circuit (IC) which is an extension of input or output (IO) pins of a microcontroller using the I2C serial communication protocol. It uses the SCL and SDA communication line between the MCP23017 and a microcontroller such as an Arduino or a Raspberry pi. Some of the microcontrollers have a limited number of IO pins, as such, an IO extension like MCP23017 is needed.

There are SCL and SDA communication pins on the MCP.

3 address pins to configure the address of the MCP, which can provide up to 8 MCP23017 for a microcontroller. The address is indexed from 0 to 7, using digital logic to set the address. The Most Significant Bit (MSB) is the A2.

There is an active low reset on the MCP, which a logic low is needed to reset the MCP.

There are 2 interrupt pins on the MCP.

There are 16 IO pins on a single MCP, which are GPA0 to GPA7, GPB0 to GPB7. The GPA0 to GPA7 are IO pins 0 to 7 and GPB0 to GPB7 are IO pins 8 to 15.

For this coding project, we will use the Adafruit_MCP23017 library, which is available on the Arduino IDE.

We will blink the LEDs with blink without delay, using the millis() function.

For this PCB, we will use the CH340 USB to TTL converter for power. The left of the PCB is 0V.

The GPIO1B/A for MCP1, the bottom is pin GPIO1B, the top is pin GPIO1A.

Note that the SCL/SDA, the SCL occupies the left column and the SDA occupies the right column.

Please have a look at the finished product at https://youtu.be/Q88LNainI1Q.

Once again, I would like to thank JLCPCB for sponsoring this project. Please order your PCB at https://jlcpcb.com/RAT.
