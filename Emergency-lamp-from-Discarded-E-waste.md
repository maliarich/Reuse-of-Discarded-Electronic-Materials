
 ![letter head](/images/Lamp-DIY-Letter-head.jpg) 

### Overview

This guide documents how to build a small, portable solar-powered light using discarded electronics and locally available materials in a refugee settlement.
The design is affordable, repairable, and uses upcycled components, reducing e-waste while providing reliable lighting.

### Objectives

      . Reuse discarded electronics to create functional lighting.                                                    
      . Provide an affordable and sustainable lighting option for households in off-grid areas.
      . Build repair skills in the community.
      . Promote environmental sustainability through e-waste reduction.

### Materials  

 ![Components ](/images/Components-DIY-Lamp.jpg) 

| S\N| Components | Specification| Purpose |
| :--------:| :--------: |:------:|:-------:|
|1|Solar Panel| 6V, 1–3W (from discarded garden lights or small electronics)|Charges the battery|
|2|   Rechargeable Battery       |   3.7V Lithium-ion (from old phones, laptops, or gadgets)                         |  Stores solar energy  |
|3|     Wires    |     Reused from old electronics       | Electrical connections       |
|4|   10k Resistor    |       1/4W          |   Controls gate voltage    |
|5| IRFZ44N MOSFET |    N-channel         |      Acts as a switch for the LED    |
|6|  1N4007 Diode   |     General purpose        |    Prevents reverse current from battery to solar panel        |
|7|  Switch  |       SPST       |    Turns the light on/off      |
|8|  Wooden Case   |    Made from plywood/flywood     |   Holds all components safely          |
|9|  LED(s)  |  White, 3–5mm or high-power LED  |   Light output        |

### Tools Needed
      . Soldering iron and solder
      . Screwdriver
      . Hot glue or nails (for wooden case assembly)
      . Wire stripper/cutter
      . Small drill (optional, for making holes in wood case)

### Circuit Design & Working

How it Works

    1. Charging:
          The solar panel converts sunlight into electricity.
          The 1N4007 diode allows current to flow into the battery but blocks reverse discharge at night.
    2. Storage:
          The 3.7V battery stores the energy.
    3. Lighting:
          When the switch is turned ON, the battery powers the LED through the IRFZ44N MOSFET.
          The 10k resistor ensures correct MOSFET gate bias.

     ![Circuit Diagram DIY lamp](/images/Circuit-diagram-DIY-lamp.jpeg
)  

### Step-by-Step Build Process

1. Preparing the lamp Case
   
      Cut plywood into panels for the base, sides, and top.
      Drill holes for the switch, LED, and wiring.
      Sand edges for safety.

       ![casing ](/images/Casing-Board-DIY-lamp.jpg)

 2. Recover & Test Components
    
      Extract battery from old devices and test voltage (should be between 3.0–4.2V).
      Salvage wires from discarded electronics.
      Check solar panel output under sunlight.

4. Assemble the Charging Circuit
   
      Connect solar panel positive to the anode of 1N4007 diode.
      Connect diode cathode to battery positive.
      Connect solar panel negative directly to battery negative.

  ![Assembling](/images/Assembling-DIY-lamp.jpg
)  

4. Add the Lighting Circuit

      Connect battery positive to LED anode via the MOSFET switching setup.
      Connect MOSFET drain to LED, source to battery negative.
      Connect switch and 10k resistor to MOSFET gate as per diagram.

    ![Circuit Diagram DIY lamp](/images/Case-attarch-DIY-Lamp.jpg
)  

5. Secure Components
   
      Mount solar panel on top of the case.
      Fix the battery securely inside.
      Position LED to shine through a front hole or transparent cover.
      Glue or screw case together.

6. Test
   
      Place the light in the sun for 5–8 hours.
      Switch ON at night to test brightness.
      If dim, check battery charge and connections.
 ![Testing ](/images/Testing-DIY-lamp.jpg
)  


### Safety Tips
      
      . Do not short-circuit the battery.
      . Avoid overcharging or over-discharging lithium-ion cells.
      . Keep electronics away from water unless waterproofed.

### Maintenance
      
      . Wipe solar panel clean regularly.
      . Replace battery after 1–2 years or if capacity drops.
      . If LED burns out, replace with similar type.

### Possible Improvements
      
      . Add a charging indicator LED.
      . Include a low-voltage cut-off circuit for battery protection.
      . Use multiple LEDs for higher brightness.

 ### Final Product
 
 ![Testing ](/images/Complete-DIY-lamp.jpg 
)  
 
      
