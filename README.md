# Electronic-Resources
This is living document, Included Self-Finding Learning Resources and Application notes [Not 100% correct and accurate, Feel free to PR to add/correct]

- [x] Create Overoll Electronic Resources checklist
- [ ] Add Description
- [ ] Add Images
- [ ] Link mostly used compenent Datasheets to relevant component
### To boost the practical knowledge I hope below are useful <br>

Most Commonly used Componenets, Circuits in Electronic Systems <br>

Componenets List

| Componenet| Description/Usage/Consideration |
| ----------- | ----------- |
| Resistor | - |
| Inductor | (Design Consideration - DC resistance, Parallel Parasitic Capacitance) |
| Capacitor | (Design Consideration - Size, ESR, ESL values) |
| Diodes (Zener, Schottky) | - |
| Transistor (Signal or Power) | (BJT - operated by current, FET - operated by voltage) |
| MOSFET | Conduction losses, switching losses (Latest - GaN Based)
| IGBT | Pros of BJT and MOSFET combined |
| Thyristor(SCR) | Semi controlled switch |
| TRIAC | - |
| DIAC | - |
| OPAMP (IC741) | (used as comparator, regulator, amplifier, filter, integrator, differentiator, wave generator and many more) |
| Timer IC (NE555) | (generate clock signal, schmitt trigger can made, oscillator adjustment) |
| Transformers | (step up & step down voltage and/or current) |
| Fuses | Protection of Circuits |
| LDR (Light Dependent Resistors) | - |
| Optocouplers/Photocouplers | - |
| Relays & Relay Drivers | - |
| Mechanical Switches | - |
| Push Buttons | - |
| RTC(Real Time Clock) | - |
| LCD | (16x2), (16x4) can use I2C module to reduce pin count to integrate with uC |
| Potentimeter | - |
| Shift Register Modules(74HC16) | To increase I/O in Micro controller (Serial in Parallel Out or Parallel in Serial Out) |
 
 
 Sensors List/ Extra Modules
 
 
| Componenet| Description/Usage/Consideration |
| ----------- | ----------- |
| PIR | - |
| GPS |  |
| Proximity | - |
| Level Sensor | - |
| Optical Sensors | - |
| IR sensor | - |
| Laser Sensor| - |
| Temperature Sensor | DS18B20, LM35, Themister (NTC, PTC), Thermo couple |
| Humidity Sensor | - |
| Pressure Sensor | - |
| Hall effect Sensor | - |
| Moisture Sensor | - |
| Color Detection Sensor |  |
| Ultra Sonic Sensor | - |
| Strain Gauge | - |
| Encoders| - |
| Non Invasive Current sensor | YHDC SCT-013-XXX |
| Voltage sensor | ZMPT101B |
| Flex sensor | - |


 Simple to Advance Circuits
 
 
| Circuit| Description/Usage/Consideration |
| ----------- | ----------- |
| Wheatstone Bridge & Kelvin Bridge | - |
| Rectifier | AC to DC (4 diode with Capacitor)|
| Invereter (Voltage Source Inverter/Current Source Inverter) | DC to AC (H bridge) |
| Volatge Regulators | With Zener Diode, 5-15V to 3.3V Converter (LD1117V33) |
| Buck Converter | - |
| Boost Converter | - |
| Buck-Boost Converter | - |
| Flyback Converter | - |
| Cuk Converter | - |
| Resonant Converter | - |
| Schmitt Trigger | Noise Cancellation |
| Battery Charging(TP4056/TP4057/MCP73831/2 Circuit (Constant Current or Constant Voltage) |
| Buffer Circuit/IC | - |
| Voltage Follower  - |
| Voltage Regulator | IC 7M317 |
| Logical Gate Circuits | 4 gates single IC AND(CD4081), OR(CD4071) |
| Multi Vibrator Circuit | Astable(no input), monstable(trigger), bistable(SR FF) |
| Sample and Hold Circuit | DAC |
| R - 2R ladder | DAC  (special IC AD5026)|
| ADC | Flash ADC, SAR ADC (special IC AD7920)|
| Protection Circuits | over current, over voltage protection |
| Motor Driver Circuit | H bridge |
| Level Shifter Circuit | HV & LV isolate (eg 5 V & 3.3V separation) |
| Diode ORing Circuit | to connect more than one power supply connection |
| Reverse Protection Circuits | schottky diode or MOSFET+driver |
| Filter Design | FIR, IIR |
| Thermal Design | Heat Sink Selection, TIM, Cooling methods |

Micro Controllers
 
| Micro Controllers| Description/Usage/Consideration |
| ----------- | ----------- |
| Arduino Family | [nano, uno, pro, mega, due, ... ](https://www.arduino.cc/en/hardware)  
| ESP32, NodeMCU|For IoT Projects|
| Raspberry Pi | [SBC & Micro Controller ](https://www.raspberrypi.com/products/) |
| Teensy| -|
| PIC | - |
| Pine Board | - |

Communication Protocols <br>
 - [I2C](https://www.analog.com/en/analog-dialogue/articles/i2c-communication-protocol-understanding-i2c-primer-pmbus-and-smbus.html)
 - [UART](https://www.analog.com/en/analog-dialogue/articles/uart-a-hardware-communication-protocol.html#:~:text=By%20definition%2C%20UART%20is%20a,going%20to%20the%20receiving%20end.)  (Async - should match Master & Slave with baudrate) 
 - SPI
 - Onewire

Test Equipments <br>
 - Multimeter
 - Oscilloscope
 - Clamp Meter
 - Thermal image detectors
 - Megger
 - Fluke Meter
 - Spectrum Analyzer

## Electronic Circuit Troubleshooting<br>
- ESD (Electro Static Discharge) - Main issue for no power on laptop
- Components wearout check
- Overheating
- Short circuit due to conductive material on PCB


## Youtube Channels<br>
[Analog Devices](https://www.youtube.com/user/AnalogDevicesInc)     <br>
[GreatScott!](https://www.youtube.com/channel/UC6mIxFTvXkWQVEHPsEdflzQ)    <br>
[ElectroBOOM](https://www.youtube.com/channel/UCJ0-OtVpF0wOKEqT2Z1HEtA)    <br>
[EEVblog](https://www.youtube.com/eevblog) <br>
[RealPars](https://www.youtube.com/c/realpars) <br>


## Web Links <br>
[Texas Instruments](https://www.ti.com/) <br>
[Power Electronics News](https://www.powerelectronicsnews.com/) <br>
[EE times](https://www.eetimes.com/)  <br>
[Analog Devices](https://www.analog.com/) <br>
[Digikey](https://www.digikey.com/en/blog) <br>
[Sparkfun](https://www.sparkfun.com/)   <br>
[Seeedstudio](https://www.seeedstudio.com/)    <br>
[randomtutorials](https://randomnerdtutorials.com/)    <br>
