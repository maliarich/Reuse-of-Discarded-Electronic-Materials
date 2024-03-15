when a Buzzer, BC547 transistor and relay are connected to gether it creates a project such,
 as an alarm system where the relay is used to control the power supply to the buzzer,
and the BC547 transistor is used to control the relay based on the input signal.


## Working Explainations

When the pushbutton is pressed, it allows current to flow through the circuit. 
The current flows through the resistor and the diode, activating the relay coil
. This closes the relay's normally open contact, allowing current to flow through the buzzer, producing the alarm sound.
 The IN4007 diode protects the relay coil from voltage spikes when the relay is turned off.

### Materials required for the project

 ![materials for the circuit](/images/materialss.jpg)

##  Here's a step-by-step explanation:

1. Connect the the cathode (-) terminal of the  IN4007 diode to the common terminal of the relay 
2. Connect the anode of the  IN4007 diode to the coil terminal of the relay.
3. Connect a resistor of 220 ohms to the coil ternilas ( this joins one terminal of the resistor to the common terminal) 
4. Connect the positive terminal of te buzzer to the Normally opened terminal of the relay.
5. Connect the Emitter of the BC 547 transistor to the cathode of the buzzer.
6. Connect the collector terminal of the BC 547 transistor to the last coil terminal of the relay.
7. From the Emitter of the BC547 transistor, connect the negative power terminal (-9v)
8. From the common groud of the relay,Connect the postive terminal of the power supply (+9v) 
9. Connect a wire from the common ground of the relay and placed it on one terminal of a pushbutton 
10. From the other pushbuton terminal,connect the wire (jumper) and connect to the Base of the BC547 Transistor.
11. Connect a 220 ohms resistor to the common terminal of the relay and join it with the anode of the LED.
12. Connect the cathode of the LED to the Emitter of the BC547 transistor 
13. Ensure wires and components are properly placed 
14. Test the circuit.

##  Circuit Diagram 
 ![the circuit Diagram](/images/Relay%20Circuittt.jpg)

## Complete Project.
 ![Components for the circuit](/images/complete%20c%201.jpg)

 Note: 
 * Read about Relays: https://circuitdigest.com/article/relay-working-types-operation-applications

 * BC547 Transistor:
https://github.com/maliarich/Reuse-of-Discarded-Electronic-Materials/blob/main/Using-BC547-and-Pushbutton.md

Also note that the specific characteristics of your components might vary,
 so it's essential to double-check datasheets and adjust component values accordingly for optimal performance. Additionally,
 consider safety precautions while working with electrical circuits and components.
