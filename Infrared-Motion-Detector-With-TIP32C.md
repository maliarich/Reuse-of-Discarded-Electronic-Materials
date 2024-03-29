In this instructional guide, we will demonstrate how to build a simple DIY Infrared (IR) motion detector using commonly available electronic components.
- The motion detector will utilize an IR sensor to detect motion and trigger an LED indicator. This project can be a fun and educational way to learn about basic electronics and sensor technology.
- When motion is detected, the IR sensor will send a signal to the base of the TIP32C transistor, allowing current to flow through the LED and illuminate it.

### Materials Needed:

 ![Components for the circuit](/images/Materials-TIP32c.png)

Instructions:

Step 1: Gather Components
Ensure you have all the necessary components.

Step 2: Connect the IR Sensor
- Place the IR sensor module onto the breadboard.
- Connect the VCC pin of the IR sensor to the positive rail of the breadboard.
- Connect the GND pin of the IR sensor to the ground rail of the breadboard.
- Connect the OUT pin of the IR sensor to 1k ohms and to the base of the TIP32C 

Step 3: Connect the LED
- Insert the LED into the breadboard, ensuring the longer leg (anode) is connected to the collector of the TIP32C 
- Connect a 220 ohms resistor from the cathode (shorter leg) of the LED to the negative rail of the breadboard 


Step 4: Connect the TIP32C Transistor
- Connect the base pin (rightmost pin) of the TIP32C transistor to 1k resistor
- Connect a 1k ohms resistor from the base pin of the TIP32C transistor to the OUT pin of the IR sensor.
- Connect the Emitter of the TIP32C to the positive rail of the power supply

Step 5: Power Supply
- Connect the positive terminal of the power supply (5V DC) to the positive rail of the breadboard.
- Connect the negative terminal of the power supply to the ground rail of the breadboard.

### CIRCUIT DIAGRAM:

 ![The circuit](/images/circuit-TIP32c.png)

Step 6: Test the Circuit
- Apply power to the circuit.
- Adjust the sensitivity and time delay settings on the IR sensor module if needed.

### COMPLETE PROJECT:

 ![Complete Project](/images/TIP32.jpg)

TIP32C: https://www.st.com/resource/en/datasheet/tip32c.pdf
