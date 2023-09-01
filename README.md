# Temperature_Monitoring_System
 The provided code is an implementation of a temperature monitoring system using an 8051 microcontroller, a multiplexed ADC (Analog-to-Digital Converter), a 4x4 keypad, and a 16x2 LCD. The system reads analog temperature values from six different temperature sensors using a multiplexed ADC and displays the corresponding temperature readings on the LCD. Additionally, it allows the user to switch between displaying the temperature values in Celsius and Fahrenheit using a button (BUTTON).

The code continuously monitors the state of the BUTTON (connected to P3^7). When the button is pressed, the code enters a Fahrenheit conversion mode. In this mode, it reads the temperature values again and displays them in Fahrenheit on the LCD. Once the button is released, the code switches back to displaying Celsius values.

Additionally, the code controls six LEDs (LED1 to LED6) connected to pins P3^1 to P3^6. The LEDs are turned on or off based on whether the corresponding temperature value is greater than or equal to 11. If the value is greater than or equal to 11, the LED is turned off; otherwise, it is turned on.

Overall, this code creates a temperature monitoring system that continuously reads temperature values from multiple sensors, displays the values on an LCD, and allows the user to switch between Celsius and Fahrenheit display modes using a button. Additionally, it provides visual feedback through LEDs based on the temperature readings.
