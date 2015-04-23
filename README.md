# Startup guide for using the Arduino with your ethernet shield's SD card slot to collect and save data from HAB launches.
 
Parts
- Arduino Uno
- Ethernet Shield
- BMP180
- Jump wires
- USB cable
- Green Led
- Red Led

Downloads
- Adafruit's BMP085 Arduino Library (https://learn.adafruit.com/bmp085/using-the-bmp085)
- Arduino’s IDE 1.6.3 (http://arduino.cc/en/Main/Software)
- Data logging code (https://github.com/hnelson7/Arduino-sensor-data-logger/archive/master.zip)


Steps
- 1. Install Arduino's IDE
- 2. Install Adafruit’s BMP085 library
- 3. Download and Open up the data logging code from github
- 4. Put together your Arduino, ethernet shield, and sensor
    - Attach ethernet shield to arduino
    - Attach Sensor to bread board
    - Run wires from: 3.3V to VIN, GND to GND, A4 to SDA, A5 to SCL
    - Run wire from 7 to board to 330 ohm resistor(RRBB) to green LED then from green to GND
    - Run Wire from 8 to board to 330 ohm resistor(RRBB) to red LED the from the LED to the GND 
    - Plug into computer
- 5. Verify
- 6. Run

-image of board
https://cloud.githubusercontent.com/assets/8889460/7301070/e68cfc60-e9a5-11e4-9774-f0b36fd8c320.png

