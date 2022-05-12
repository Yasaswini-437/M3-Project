# INTRODUCTION
- Over the past two decades, the automotive industry has aggressively researched ways to exploit modern computing and electronic advances in the development of safety, reliability, and entertainment technologies.
- Despite this, automatic rain-sensing wiper systems are relatively uncommon in modern vehicles for a number of reasons. 
- They are often too expensive, too unsightly, or too unreliable to be desired in new automobiles.
- Many attempts have been made at constructing an effective, reliable, and cheap rain detection and wiper control system for vehicles speed and intermittent interval automatically according to the amount of rain. 
- To measure the amount of water usually use optical sensor. 
- In this type of sensors uses the fact that the refraction angle and the amount of reflection of the light are different when the 2 windshield is wet. 
- Even though optical sensors are used widely they have some disadvantage. 
- One of disadvantages is the sensitivity to external light. Another problem is occurs when car drive at night or gone through tunnel and even in underground parking. 
- For this many systems still activate the wiper when the car comes out of tunnels or underground parking lot. 
- Another shortfall, maybe a major one is that the sensing area is a relatively small portion of windshield. 
- Hence the system operate only with limited area.[2] 
- The wiper system may fail to activate when there are some raindrops on the driver’s line of sight, but not on the sensing area. 
- They are often too expensive, too unsightly, or too unreliable to be desired in new automobiles.
# HARDWARE AND SOFTWARE
- This section describes the hardware required for actual implementation and the software used for designing and simulating the test results. 
- The speed of the wiper is controlled electronically with the help of the microcontroller.
- In the software Description, the programming flow is discussed using MPLAB IDE V 8.30+ for complete Development environment. and simulation software Proteus.
## Hardware Description:
- The rain sensor is used to detect the amount of the rain and give the signal to the controller. 
- The ADC in the controller detects the sensor input and gives the signal to the driver circuit. 
- The motor driver actuates the motor to run at high speed or low speed based on the amount of the rain level detected. 
- The rain level sensor will detect the level of water content on the windshield and based on the amount of water deposited on the windshield, the speed of the wiper is controlled. 
- If the water level or the rain dew deposited on the windshield is more, then according to time to fill water tank speeded of wiper move automatically . 
- In that case, the system will turn on the wiper motor to activate at high speed using the driver circuit. 
- If the level of water content is low, then the wiper motor is activated at low speed.These are the basic building blocks of the hardware besides the resistors and capacitors that are required for any electronic circuit
## Software Description:
- The software used designing and simulating the test results were Proteus 7.0 and ‘C’ 18 MPLAB C language compilers.
- MPLAB IDE V 8.30+ for complete Development environment.
- Proteus 7.0 is a Virtual System Modeling (VSM) that combines circuit simulation, animated components and microprocessor models to co-simulate the complete microcontroller based designs. 
- This program allows users to interact with the design using on-screen indicators and/or LED and LCD displays and, if attached to the PC, switches and buttons. 
- One of the main components of Proteus 7.0 is the Circuit Simulation -- a product that uses a SPICE3f5 analogue Simulator kernel combined with an event-driven digital simulator that allows users to utilize any SPICE model by any manufacturer. 
- Proteus VSM comes with extensive debugging features, including breakpoints, single stepping and variable display for a neat design prior to hardware prototyping.
# HARDWARE IMPLEMENTATION:
- The basic control units of the hardware comprises of power supply unit, control switch, wiper motor, rain level sensor,motor driver circuit, moisture sensor, temperature sensor and the most important of all PIC controller.
- Power supply unit maintains the continuous power to the controller and the wiper motor. 
- Control switch is directly connected to the controller. 
- Motor driver circuit is linked with the wiper motor and the controller. 
- The command it gets from the controller is used to either drive the wiper motor or switch it off. 
- Rain detection sensor detects the amount of water level on the windscreen and accordingly sends the signal to the controller.
## Temperature sensors
- The LM35 series are precision integrated-circuit temperature sensors, whose output voltage is linearly proportional to the Celsius (Centigrade) temperature. 
- The LM35 thus has an advantage over linear temperature sensors calibrated in ° Kelvin, as the user is not required to subtract a large constant voltage from its output to obtain convenient Centigrade scaling.
## Rain level Sensor (SL-156-02)
- Rain level Sensor is a highly versatile device for automatic wiping of vehicle windscreen when it is wet due to moisture, raindrops or even mud. 
- It measure the amount of water inside tube with respect to time within the windscreen. 
- When water level are increase with respect to raindrops fall onto the windscreen, then system then activates the wiper to operate in full automatic mode. 
- The main features is Automatic wiper activation and deactivation and Intelligent wipers speed control .
## Humidity Sensor(SY-HS-200) :
- Humidity Sensor module is used to take input from various physical parameter. 
- like inside and outside temperature and moister . 
- If temperature are varied then adjust that temperature so that moister are not inside windscreen.
- Humidity sensor gives both moisture and temperature outputs are available in analog as well as two digital formats.

