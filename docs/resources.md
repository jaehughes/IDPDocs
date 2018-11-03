# IDP: Resources

*Note: In this lab we are using OrangePip which are a direct replica of the Arduino and is fully compliant with the Arduino IDE.  More specifically we are using the [Orangepip Mega2560](https://www.orangepipboards.com/) which is a direct equivalent of the Arduino Mega2560, thus any information/tutorials for either of these are relevant.*

## Electronics: Getting Started

We suggest you take a little bit of time familiarising yourself with the microcontroller and reading from sensors and setting outputs. This will enable you to understand how it is possible to interface with sensors using a microcontroller and how the sensor circuitry should be built. There is some cross over between this and the software groups, however, 2 Arduino have been provided per team to allow you to both work on this.

The Arduino IDE software is installed on the teaching system (and can be found on the PCs in the EIETL), or can be used online, or can be downloaded (for free) on to your personal computer.

First, familiarise yourself with the board and the different pins. **Read through [this](https://www.circuito.io/blog/arduino-uno-pinout/) page to understand the different inputs types and how the board works.**  Although this if for an smaller Arduino Uno, the same information holds for the Mega.  The specific pin out for the Arduino is given here:

![Arduino Mega](mega.jpg)

**Familiarisation with the Arduino**

Follow this [tutorial](https://www.arduino.cc/en/Guide/ArduinoMega2560) to using an programming an Arduino Mega.  If you a using a PC which is running the Arduino IDE for the first time, you may need to install the driver software which can be found [here](https://www.arduino.cc/en/Guide/Windows).  

Make sure you can run the 'blinky LED' script and your LED on your board blinks.

**Connect an LED to the Arduino**

Using your breadboard, now wire up an LED to another digital input on your Arduino, as shown in the figure below.  You can use jumpers to connect to the Arduino and to the LED; make sure you connect the LED the correct way around and use a current limiting resistor (assuming the max forward current of the LED is around 20-30mA).  For more information on how to pick this resistor, read [this page](https://www.build-electronic-circuits.com/current-limiting-resistor/).

Change the program written in the previous task to write to the new digital input with the LED is attached to.  Make the LED turn on/off
![Electonics task 1](e_1.png)

**Read from the Analogue Input**

Connect the LDR on breadboard with another resistor to form a potential divider as shown.  Connect the middle of this potential divider to the analogue Input.  To choose the correct resistor, a multi-meter should be used to measure the average resistance of the LDR, and a matched fixed resistor can be used to achieve the largest range of output voltage.  

![Electonics task 1](e22.png)

Build the circuit and check with a multimeter that the voltage in the middle of the LDR circuit changes as expected.

We can now using the following to read from the analog input and then print to the to the serial monitor.  The serial monitor can help for debugging.  Check that the sensor values change when the LDR is covered.

```
int sensorPin = A0;    // select the input pin for the potentiometer

int sensorValue = 0;  // variable to store the value coming from the sensor

void setup() {
  Serial.begin(9600);           //Start serial and set the correct Baud Rate
}

void loop() {
  sensorValue = analogRead(sensorPin);
  Serial.println(sensorValue);
}
```

**Wire-up motor controllers**

Using the [documentation and tutorials](https://learn.adafruit.com/adafruit-motor-shield-v2-for-arduino/overview) and examples sketches for the motor-shield, wire up the motors and check that you can control the direction.

*Passed the wired up motor-shield (with appropiate information) over to your software team.*

**Make a color sensor**

Reflectance can be used to measure the colour of an object nearby.  By shining an LED, and measuring the reflectance of the output using an LDR, the analogue reading can provide an indication of the color as the absorbance of the light will vary with the colour of the material. Using the approaches in the previous tasks (controlling an LED and reading from an LDR) make a colour sensor which uses reflectance.  You may need to adjust the resistor in the potential divider to maximise the sensitivity.

Color filters an be added to the LDR to detect specific colors. A similar approach can be made by using an IR diode + photodetector.  

You could consider using an op-amp to make a comparitor to convert this analogue input into a digital input

**Read from an I2C device**

I2C is a popular method of interfacing with sensors or devices.  This is a digital protocol, which allows multiple devices to be connected over only two data lines making it highly efficient and scale-able.  Information about I2C and how I2C can be interfaced using Arduino is described [here](https://howtomechatronics.com/tutorials/arduino/how-i2c-communication-works-and-how-to-use-it-with-arduino/).

**Understanding the prototyping shield & Vero Board**

To design your can first use breadboard to test, after which you can transfer them over to the prototyping board which is provided and forms a 'shield' above the microcontroller.  Additional circuits can be added by using strip board, which can then be connected by using additional headers.  

This is an excellent [tutorial](https://electronicsclub.info/stripboard.htm) on how to use strip board and how to design circuits when using strip board!  Well worth a read!

**Designing your electronics and sensing: Hints & Tips**

Things to consider when designing your electronics:
* Do you need a switch/interface to start your robot/reset?
* Add indicator LEDs to electronics to identify if the circuits are working without requiring software to  run.
* Talk with mechanics/software, how are you going to mount your sensors and does this influence the design you may require?
* If you want to tune sensititivites (for example potential dividers or inputs to compartors/amplifyers) consider using a variable resistor.
* Should sensors give you a digital/analogue input? Can you convert to a digital input to reduce the load on the software team?
* How can you connect external flying leads/parts attached to the robot to the electronics?

Make sure you look at the assessment page to see what is required for Design Acceptance and what must be achieved by when. This gives some additional advice on how to draw/design circuits.

**Practical Advice**

* Soldering





## Software: Getting Started

To start with, you should gain familiarity with the Arduino and software and achieve the basics: control of motors, reading from sensors and

**Familiarisation with the Arduino**

**Motor Control**

**Reading from Sensors**

**Interfacing to Python**



Things to consider when developing your software:
* Do you need a switch/interface to start your robot/reset?

## Mechanics: Getting Started

Start designing your chassis.

Advice on CAD for laser cutting: https://www.sculpteo.com/blog/2017/06/14/use-fusion-360-cad-software-for-laser-cutting

**Deparment Rapid Prototyping Facilities**

Information on the rapid prototyping facilities available in the department can be found here:

* [Laser Cutting](https://www.dysoncentre.eng.cam.ac.uk/laser-cutting)
* [3D Printing](https://www.dysoncentre.eng.cam.ac.uk/3d-printing)
* [Plasma Cutter](https://www.dysoncentre.eng.cam.ac.uk/plasma-cutter/cambridge-only/cambridge-only)

The laser cutter may be busy - there are training sessions daily at 12-13 and 14-15; these times should be avoided.  The laser cutter should only not be used out of hours and particular care should be taken when cardboard is cut, as this is easily flammable.


Things to consider when developing your software:
* What pins/how will you be interfacing with the electronics sensors?
* How can you test the software?







## Arduino Software Support
