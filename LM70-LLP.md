February 2005![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.001.png)![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.002.png)

**LM70**

**SPI/MICROWIRE 10-Bit plus Sign Digital Temperature Sensor**

**General Description**

The LM70 is a temperature sensor, Delta-Sigma analog-to- digital converter with an SPI and MICROWIRE compatible interface available in LLP and MSOP 8-pin packages. The host can query the LM70 at any time to read temperature. A shutdown mode decreases power consumption to less than 10 µA. This mode is useful in systems where low average power consumption is critical.

The LM70 has 10-bit plus sign temperature resolution (0.25˚C per LSB) while operating over a temperature range of −55˚C to +150˚C.

The LM70’s 2.65V to 5.5V supply voltage range, low supply current and simple SPI interface make it ideal for a wide range of applications. These include thermal management and protection applications in hard disk drives, printers, elec- tronic test equipment, and office electronics.

**Applications**

n System Thermal Management n Personal Computers

n Disk Drives

n Office Electronics

n Electronic Test Equipment

**Features**

n 0.25˚C temperature resolution.

n Shutdown mode conserves power between temperature

reading

n SPI and MICROWIRE Bus interface

n MSOP-8 and LLP-8 packages save space

**Key Specifications**

j Supply Voltage j Supply Current

j Temperature

Accuracy

2.65V to 5.5V operating 260 µA (typ)

490 µA (max) shutdown 12 µA (typ) −40˚C to 85˚C ±2˚C(max) −10˚C to 65˚C +1.5/−2˚C(max) −55˚C to 125˚C +3/−2˚C(max) −55˚C to 150˚C +3.5/−2˚C(max)

**Simplified Block Diagram**

![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.003.png)

10122301

© 2005 National Semiconductor Corporation DS101223 www.national.com

**Connection Diagrams![ref1]**

**LM70**

**MSOP-8 LLP-8**

10122302 ![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.005.png)![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.006.png)

**TOP VIEW** 10122325 **NS Package Number MUA08A TOP VIEW**

**NS Package Number LDA08A**

**Ordering Information**



|**Order Number**|**Package Marking**|**NS Package Number**|**Supply Voltage**|**Transport Media**|
| - | - | :-: | - | - |
|LM70CILD-3|T33|LLP-8, LDA08A|2\.65V to 3.6V|1000 Units in Tape and Reel|
|LM70CILDX-3|T33|LLP-8, LDA08A|2\.65V to 3.6V|4500 Units in Tape and Reel|
|LM70CILD-5|T35|LLP-8, LDA08A|4\.5V to 5.5V|1000 Units in Tape and Reel|
|LM70CILDX-5|T35|LLP-8, LDA08A|4\.5V to 5.5V|4500 Units in Tape and Reel|
|LM70CIMM-3|T04C|MSOP-8, MUA08A|2\.65V to 3.6V|1000 Units in Tape and Reel|
|LM70CIMMX-3|T04C|MSOP-8, MUA08A|2\.65V to 3.6V|3500 Units in Tape and Reel|
|LM70CIMM-5|T03C|MSOP-8, MUA08A|4\.5V to 5.5V|1000 Units in Tape and Reel|
|LM70CIMMX-5|T03C|MSOP-8, MUA08A|4\.5V to 5.5V|3500 Units in Tape and Reel|

**Pin Descriptions**



|**Label**|**SOP-8 Pin #**|**LLP-8 Pin #**|**Function**|**Typical Connection**|
| - | - | - | - | - |
|SI/O|1|1|Input/Output - Serial bus bi-directional data line. Schmitt trigger input.|From and to Controller|
|SC|2|3|Clock - Serial bus clock Schmitt trigger input line.|From Controller|
|GND|4|7|Power Supply Ground|Ground|
|<p>+</p><p>V</p>|5|5|Positive Supply Voltage Input|DC Voltage from 2.65V to 5.5V. Bypass with a 0.1 µF ceramic capacitor.|
|CS|7|8|Chip Select input.|From Controller|
|NC|3, 6, 8|2, 4, 6|No Connect|These pins are not connected to the LM70 die in any way.|

**Typical Application![ref2]**

![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.008.png)

10122303

**FIGURE 1. COP Microcontroller Interface**

3 www.national.com

**Absolute Maximum Ratings[ (Note 1)](#_page5_x0.00_y0.00)![ref1]**

**LM70**

Supply Voltage −0.3V to 6.0V Voltage at any Pin −0.3V to V+ + 0.3V

Input Current at any Pin[ (Note 2)](#_page5_x0.00_y0.00) 5 mA Package Input Current[ (Note 2)](#_page5_x0.00_y0.00) 20 mA Storage Temperature −65˚C to +150˚C Soldering Information, Lead Temperature

MSOP-8 and LLP-8 Packages

[(Note 3)](#_page5_x0.00_y0.00)

Vapor Phase (60 seconds) 215˚C Infrared (15 seconds) 220˚C

ESD Susceptibility[ (Note 4)](#_page5_x0.00_y0.00)

Human Body Model 3000V Machine Model 300V

**Operating Ratings**

Specified Temperature Range TMIN to TMAX [(Note 5)](#_page5_x0.00_y0.00) −55˚C to +150˚C Supply Voltage Range (+VS) +2.65V to +5.5V

4 www.national.com

**Temperature-to-Digital Converter Characteristics**

Unless otherwise noted, these specifications apply for V+ = 2.65V to 3.6V for the LM70-3 and V+ = 4.5V to 5.5V for the LM70-5 [(Note 6).](#_page5_x0.00_y0.00) **Boldface limits apply for TA = TJ = TMIN to TMAX;** all other limits TA = TJ=+25˚C, unless otherwise noted.

<table><tr><th colspan="1"><b>Parameter</b></th><th colspan="1"><b>Conditions</b></th><th colspan="1" valign="top"><b>Typical [(Note 7)](#_page5_x0.00_y0.00)</b></th><th colspan="1"><b>LM70-5 Limits [(Note 8)](#_page5_x0.00_y0.00)</b></th><th colspan="1"><b>LM70-3 Limits [(Note 8)](#_page5_x0.00_y0.00)</b></th><th colspan="1" valign="top"><b>Units (Limit)</b></th></tr>
<tr><td colspan="1" rowspan="4" valign="top">Temperature Error[ (Note 6)](#_page5_x0.00_y0.00)</td><td colspan="1"><p>T = −10˚C to +65˚C</p><p>A</p></td><td colspan="1"></td><td colspan="1"><b>+1.5/−2.0</b></td><td colspan="1"><b>+1.5/−2.0</b></td><td colspan="1">˚C (max)</td></tr>
<tr><td colspan="1">TA = −40˚C to +85˚C</td><td colspan="1"></td><td colspan="1" valign="top"><b>±2.0</b></td><td colspan="1" valign="top"><b>±2.0</b></td><td colspan="1">˚C (max)</td></tr>
<tr><td colspan="1">TA = −55˚C to +125˚C</td><td colspan="1"></td><td colspan="1"><b>+3.0/−2.0</b></td><td colspan="1"><b>+3.0/−2.0</b></td><td colspan="1">˚C (max)</td></tr>
<tr><td colspan="1">TA = −55˚C to +150˚C</td><td colspan="1"></td><td colspan="1"><b>+3.5/−2.0</b></td><td colspan="1"><b>+3.5/−2.0</b></td><td colspan="1">˚C (max)</td></tr>
<tr><td colspan="1" valign="top">Resolution</td><td colspan="1"></td><td colspan="1">11 0.25</td><td colspan="1"></td><td colspan="1"></td><td colspan="1">Bits ˚C</td></tr>
<tr><td colspan="1">Temperature Conversion Time</td><td colspan="1" valign="top">[(Note 9)](#_page5_x0.00_y0.00)</td><td colspan="1" valign="top">140</td><td colspan="1" valign="top"><b>210</b></td><td colspan="1" valign="top"><b>210</b></td><td colspan="1" valign="top">ms (max)</td></tr>
<tr><td colspan="1" valign="top">Quiescent Current</td><td colspan="1">Serial Bus Inactive Serial Bus Active Shutdown Mode</td><td colspan="1">260 260 12</td><td colspan="1" valign="top"><b>490</b></td><td colspan="1" valign="top"><b>490</b></td><td colspan="1"><p>µA (max) µA</p><p>µA</p></td></tr>
</table>

**Logic Electrical Characteristics Digital DC Characteristics**

Unless otherwise noted, these specifications apply for V+ = 2.65V to 3.6V for the LM70-3 and V+ = 4.5V to 5.5V for the LM70-5. **Boldface limits apply for TA = TJ = TMIN to TMAX;** all other limits TA = TJ=+25˚C, unless otherwise noted.

<table><tr><th colspan="1"><b>Symbol</b></th><th colspan="1"><b>Parameter</b></th><th colspan="1"><b>Conditions</b></th><th colspan="1"><b>Typical [(Note 7)](#_page5_x0.00_y0.00)</b></th><th colspan="1"><b>Limits [(Note 8)](#_page5_x0.00_y0.00)</b></th><th colspan="1"><b>Units (Limit)</b></th></tr>
<tr><td colspan="1" valign="top">VIN(1)</td><td colspan="1" valign="top">Logical “1” Input Voltage</td><td colspan="1"></td><td colspan="1"></td><td colspan="1" valign="top"><b>V+ x 0.7 V+ + 0.3</b></td><td colspan="1">V (min) V (max)</td></tr>
<tr><td colspan="1" valign="top">VIN(0)</td><td colspan="1" valign="top">Logical “0” Input Voltage</td><td colspan="1"></td><td colspan="1"></td><td colspan="1"><p><b>−0.3</b></p><p><b>+ x 0.3</b></p><p><b>V</b></p></td><td colspan="1">V (min) V (max)</td></tr>
<tr><td colspan="1" rowspan="2"></td><td colspan="1" rowspan="2" valign="top">Input Hysteresis Voltage</td><td colspan="1" valign="top"><p>+</p><p>V = 2.65V to 3.6V</p></td><td colspan="1">0\.8</td><td colspan="1"><b>0.27</b></td><td colspan="1">V (min)</td></tr>
<tr><td colspan="1" valign="top"><p>+</p><p>V = 4.5V to 5.5V</p></td><td colspan="1">0\.8</td><td colspan="1"><b>0.35</b></td><td colspan="1">V (min)</td></tr>
<tr><td colspan="1"><p>I</p><p>IN(1)</p></td><td colspan="1">Logical “1” Input Current</td><td colspan="1"><p>+</p><p>V = V</p><p>IN</p></td><td colspan="1">0\.005</td><td colspan="1"><b>3.0</b></td><td colspan="1">µA (max)</td></tr>
<tr><td colspan="1"><p>I</p><p>IN(0)</p></td><td colspan="1">Logical “0” Input Current</td><td colspan="1"><p>V = 0V</p><p>IN</p></td><td colspan="1">−0.005</td><td colspan="1"><b>−3.0</b></td><td colspan="1">µA (min)</td></tr>
<tr><td colspan="1">CIN</td><td colspan="1">All Digital Inputs</td><td colspan="1"></td><td colspan="1">20</td><td colspan="1"></td><td colspan="1">pF</td></tr>
<tr><td colspan="1"><p>V</p><p>OH</p></td><td colspan="1">High Level Output Voltage</td><td colspan="1"><p>I = −400 µA</p><p>OH</p></td><td colspan="1"></td><td colspan="1"><b>2.4</b></td><td colspan="1">V (min)</td></tr>
<tr><td colspan="1"><p>V</p><p>OL</p></td><td colspan="1">Low Level Output Voltage</td><td colspan="1"><p>I = +2 mA</p><p>OL</p></td><td colspan="1"></td><td colspan="1"><b>0.4</b></td><td colspan="1">V (max)</td></tr>
<tr><td colspan="1" valign="top">IO_TRI-STATE</td><td colspan="1">TRI-STATE Output Leakage Current</td><td colspan="1">VO = GND VO = V+</td><td colspan="1"></td><td colspan="1"><b>−1 +1</b></td><td colspan="1">µA (min) µA (max)</td></tr>
</table>

**Logic Electrical Characteristics** (Continued) ![ref2]**Serial Bus Digital Switching Characteristics**

Unless otherwise noted, these specifications apply for V+ = 2.65V to 3.6V for the LM70-3 and V+ = 4.5V to 5.5V for the LM70-5, CL (load capacitance) on output lines = 100 pF unless otherwise specified. **Boldface limits apply for TA = TJ = TMIN to TMAX;** all other limits TA = TJ = +25˚C, unless otherwise noted.

|**Symbol**|**Parameter**|**Conditions**|**Typical [(Note 7)](#_page5_x0.00_y0.00)**|**Limits [(Note 8)](#_page5_x0.00_y0.00)**|**Units (Limit)**|
| - | - | - | - | :- | - |
|t1|SC (Clock) Period|||**0.16** DC|µs (min) (max)|
|t2|CS Low to SC (Clock) High Set-Up Time|||**100**|ns (min)|
|t3|CS Low to Data Out (SO) Delay|||**70**|ns (max)|
|t4|SC (Clock) Low to Data Out (SO) Delay|||**70**|ns (max)|
|t5|CS High to Data Out (SO) TRI-STATE|||**200**|ns (min)|
|t6|SC (Clock) High to Data In (SI) Hold Time|||**60**|ns (min)|
|t7|Data In (SI) Set-Up Time to SC (Clock) High|||**30**|ns (min)|

**Timing Diagrams**

![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.009.png)

10122304

**FIGURE 2. Data Output Timing Diagram**

![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.010.png)

10122305

**FIGURE 3. TRI-STATE Data Output Timing Diagram**

![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.011.png)

10122306

**FIGURE 4. Data Input Timing Diagram**

<a name="_page5_x0.00_y0.00"></a>**Electrical Characteristics**

**LM70**

**Note 1:** Absolute Maximum Ratings indicate limits beyond which damage to the device may occur. DC andAC electrical specifications do not apply when operating the device beyond its rated operating conditions.

**Note 2:** When the input voltage (VI) at any pin exceeds the power supplies (VI < GND or VI > +VS) the current at that pin should be limited to 5 mA. The 20 mA maximum package input current rating limits the number of pins that can safely exceed the power supplies with an input current of 5 mA to four.

**Note 3:** See the section titled “Surface Mount” found in a current National Semiconductor Linear Data Book for other methods of soldering surface mount devices. **Note 4:** Human body model, 100 pF discharged through a 1.5 kΩ resistor. Machine model, 200 pF discharged directly into each pin.

**Note 5:** The life expectancy of the LM70 will be reduced when operating at elevated temperatures. LM70 θJA (thermal resistance, junction-to-ambient) when attached to a printed circuit board with 2 oz. foil is summarized in the table below:



|**Device Number**|**NS Package Number**|**Thermal Resistance (**θ**JA)**|
| - | :-: | :- |
|LM70CILD|LDA08A|51\.3˚C/W|
|LM70CIMM|MUA08A|200˚C/W|

**Note 6:** Both part numbers of the LM70 will operate properly over the V+ supply voltage range of 2.65V to 5.5V. The temperature error for temperature ranges of −10˚C to +65˚C, −40˚C to +85˚C, −55˚C to +125˚C and −55˚C to +150˚C include error induced by power supply variation of ±5% from the nominal value.

Temperature error will increase by ±0.3˚C for a power supply voltage (V+) variation of ±10% from the nominal value.

**Note 7:** Typicals are at TA = 25˚C and represent most likely parametric norm.

**Note 8:** Limits are guaranteed to National’s AOQL (Average Outgoing Quality Level).

**Note 9:** This specification is provided only to indicate how often temperature data is updated. The LM70 can be read at any time without regard to conversion state (and will yield last conversion result). A conversion in progress will not be interrupted. The output shift register will be updated at the completion of the read and a new conversion restarted.

**Note 10:** For best accuracy, minimize output loading. Higher sink currents can affect sensor accuracy with internal heating. This can cause an error of 0.64˚C at full rated sink current and saturation voltage based on junction-to-ambient thermal resistance.

**Electrical Characteristics** (Continued)![ref2]

![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.012.png)

10122308

**FIGURE 5. Temperature-to-Digital Transfer Function (Non-linear scale for clarity)**

**TRI-STATE Test Circuit**

![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.013.png)

10122307

**FIGURE 6.**

7 www.national.com

**Typical Performance Characteristics![ref1]**

**LM70**

**Average Power-On Reset Voltage vs Temperature Static Supply Current vs Temperature**

![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.014.png) ![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.015.png)

10122323 10122321

**Temperature Error**

![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.016.png)

10122322

8

www.national.com

0. **Functional Description**

The LM70 temperature sensor incorporates a band-gap type temperature sensor and 10-bit plus sign ∆Σ ADC (Delta-

Sigma Analog-to-Digital Converter). Compatibility of the LM70’s three wire serial interface with SPI and MICROWIRE allows simple communications with common microcontrol- lers and processors. Shutdown mode can be used to opti- mize current drain for different applications.Amanufacture’s ID register identifies the LM70 as National Semiconductor

product.

1. **POWER UP AND POWER DOWN**

The LM70 always powers up in a known state.The power up default condition is continuous conversion mode. Immediatly after power up the LM70 will output an erroneous code until the first temperature conversion has completed.

When the supply voltage is less than about 1.6V (typical), the LM70 is considered powered down. As the supply volt- age rises above the nominal 1.6V power up threshold, the internal registers are reset to the power up default state described above.

2. **SERIAL BUS INTERFACE**

The LM70 operates as a slave and is compatible with SPI or MICROWIRE bus specifications. Data is clocked out on the falling edge of the serial clock (SC), while data is clocked in on the rising edge of SC. A complete transmit/receive com- munication will consist of 32 serial clocks. The first 16 clocks comprise the transmit phase of communication, while the second 16 clocks are the receive phase.

When CS is high SI/O will be inTRISTATE®. Communication should![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.017.png)![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.018.png) be initiated by taking chip select (CS) low. This should not be done when SC is changing from a low to high state. Once CS is low the serial I/O pin (SI/O) will transmit the first bit of data. The master can then read this bit with the rising edge of SC. The remainder of the data will be clocked out by the falling edge of SC. Once the 14 bits of data (one sign bit, ten temperature bits and 3 high bits) are transmitted the SI/O line will go ![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.019.png)intoTRI-STATE. CS can be taken high at any time during the transmit phase. If CS is brought low in the middle of a conversion the LM70 will complete the con- version![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.020.png) and the output shift register will be updated after CS is brought back high.

The receive phase of a communication starts after 16 SC periods.![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.021.png) CS can remain low for 32 SC cycles. The LM70 will read the data available on the SI/O line on the rising edge of the serial clock. Input data is to an 8-bit shift register. The part will detect the last eight bits shifted into the register. The receive phase can last up to 16 SC periods.All ones must be shifted in order to place the part into shutdown.Azero in any location will take the LM70 out of shutdown. The following codes only should be transmitted to the LM70:

- 00 hex (normal operation)
- 01 hex (normal operation)
- 03 hex (normal operation)
- 07 hex (normal operation)
- 0F hex (normal operation)
- 1F hex (normal operation)
- 3F hex(normal operation)
- 7F hex(normal operation)
- FF hex (Shutdown, transmit manufacturer’s ID) .

any others may place the part into a Test Mode. Test Modes are used by National Semiconductor to thoroughly test the function of the LM70 during production testing. Only eight bits have been defined above since only the last eight trans- mitted, before CS is taken HIGH, are detected by the LM70

The following communication can be used to determine the Manufacturer’s/Device ID and then immediately place the part into continuous conversion mode. With CS continuously low:![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.022.png)

- Read 16 bits of temperature data
- Write 16 bits of data commanding shutdown
- Read 16 bits of Manufacture’s/Device ID data
- Write 8 to 16 bits of data commanding Conversion Mode
- Take CS HIGH.![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.023.png)

Note that 250 ms will have to pass for a conversion to complete before the LM70 actually transmits temperature data.

3. **TEMPERATURE DATA FORMAT**

Temperature data is represented by a 11-bit, two’s comple- ment word with an LSB (Least Significant Bit) equal to 0.25˚C:



<table><tr><th colspan="1" rowspan="2" valign="top"><b>Temperature</b></th><th colspan="2"><b>Digital Output</b></th></tr>
<tr><td colspan="1"><b>Binary</b></td><td colspan="1"><b>Hex</b></td></tr>
<tr><td colspan="1">+150˚C</td><td colspan="1">0100 1011 0001 1111</td><td colspan="1">4B 1Fh</td></tr>
<tr><td colspan="1">+125˚C</td><td colspan="1">0011 1110 1001 1111</td><td colspan="1">3E 9Fh</td></tr>
<tr><td colspan="1">+25˚C</td><td colspan="1">0000 1100 1001 1111</td><td colspan="1">0B 9Fh</td></tr>
<tr><td colspan="1">+0.25˚C</td><td colspan="1">0000 0000 0011 1111</td><td colspan="1">00 3Fh</td></tr>
<tr><td colspan="1">0˚C</td><td colspan="1">0000 0000 0001 1111</td><td colspan="1">00 1Fh</td></tr>
<tr><td colspan="1">−0.25˚C</td><td colspan="1">1111 1111 1111 1111</td><td colspan="1">FF FFh</td></tr>
<tr><td colspan="1">−25˚C</td><td colspan="1">1111 0011 1001 1111</td><td colspan="1">F3 9Fh</td></tr>
<tr><td colspan="1">−55˚C</td><td colspan="1">1110 0100 1001 1111</td><td colspan="1">E4 9Fh</td></tr>
</table>

Note: The last two bits are TRI-STATE and depicted as one in the table.

The first data byte is the most significant byte with most significant bit first, permitting only as much data as neces- sary to be read to determine temperature condition. For instance, if the first four bits of the temperature data indicate an overtemperature condition, the host processor could im- mediately take action to remedy the excessive tempera- tures.

4. **SHUTDOWN MODE/MANUFACTURER’S ID**

Shutdown mode is enabled by writing XX FF to the LM70 as shown in[` `*Figure 7*c](#_page10_x0.00_y0.00) and discussed in Section 1.2. The serial bus is still active when the LM70 is in shutdown. Current draw drops to less than 10 µA between serial communica- tions. When in shutdown mode the LM70 always will output 1000 0001 0000 00XX. This is the manufacturer’s ID/Device ID information. The first 5-bits of the field (1000 0XXX) are reserved for manufacturer’s ID.

9

www.national.com

**1.0 Functional Description** (Continued)![ref1]

**LM70**

**1.5 INTERNAL REGISTER STRUCTURE**

The LM70 has three registers, the temperature register, the configuration register and the manufacturer’s/device identifi- cation register. The temperature and manufacturer’s/device identification registers are read only. The configuration reg- ister is write only.

1. **CONFIGURATION REGISTER**

(Selects shutdown or continuous conversion modes):

(Write Only):



|**D15**|**D14**|**D13**|**D12**|**D11**|**D10**|**D9**|**D8**|**D7**|**D6**|**D5**|**D4**|**D3**|**D2**|**D1**|**D0**||
| - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | :- |
|X|X|X|X|X|X|X|X|Shutdown|||||||||

D0-D15 set to XX FF hex enables shutdown mode. will stop responding as described. These test modes are to D0-D15 set to XX 00 hex enables continuous conversion be used for National Semiconductor production testing only. mode. See Section 1.2 Serial Bus Interface for a complete discus-

sion.

Note: setting D0-D15 to any other values may place the

LM70 into a manufacturer’s test mode, upon which the LM70

2. **TEMPERATURE REGISTER** (Read Only):



|**D15**|**D14**|**D13**|**D12**|**D11**|**D10**|**D9**|**D8**|**D7**|**D6**|**D5**|**D4**|**D3**|**D2**|**D1**|**D0**|
| - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - |
|MSB|Bit 9|Bit 8|Bit 7|Bit 6|Bit 5|Bit 4|Bit 3|Bit 2|Bit 1|LSB|1|1|1|X|X|

D0–D1: Undefined. TRI-STATE will be output on SI/0. D5–D15: Temperature Data. One LSB = 0.25˚C. Two’s D2–D4: Always set high. complement format.

3. **MANUFACTURER’S/DEVICE ID REGISTER** (Read Only):



|**D15**|**D14**|**D13**|**D12**|**D11**|**D10**|**D9**|**D8**|**D7**|**D6**|**D5**|**D4**|**D3**|**D2**|**D1**|**D0**|
| - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - |
|1|0|0|0|0|0|0|1|0|0|0|0|0|0|X|X|

D0–D1: Undefined. TRI-STATE will be output on SI/0. D5–D15: Manufacturer’s ID Data. This register is accessed D2-D4: Always set LOW. whenever the LM70 is in shutdown mode.

<a name="_page10_x0.00_y0.00"></a>**2.0 Serial Bus Timing Diagrams![ref2]**

![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.024.png)

10122314

1) **Reading Continuous Conversion - Single Eight-Bit Frame**

![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.025.png)

10122315

2) **Reading Continuous Conversion - Two Eight-Bit Frames**

![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.026.png)

10122318

3) **Writing Shutdown Control FIGURE 7. Timing Diagrams**

11

www.national.com

**3.0 Application Hints**

To get the expected results when measuring temperature with an integrated circuit temperature sensor like the LM70, it is important to understand that the sensor measures its own die temperature. For the LM70, the best thermal path between the die and the outside world is through the LM70’s pins. In the MSOP-8 package the ground pin is connected to the back side of the LM70 die and thus has the most effect on the die temperature. Although the other pins will also have some effect on the LM70die temperature and therefore should not be discounted.The LM70 will provide an accurate measurement of the temperature of the printed circuit board on which it is mounted, because the pins represent a good thermal path to the die. A less efficient thermal path exists

between the plastic package and the LM70 die. If the ambi- ent air temperature is significantly different from the printed circuit board temperature, it will have a small effect on the measured temperature.

In probe-type applications, the LM70 can be mounted inside a sealed-end metal tube, and can then be dipped into a bath or screwed into a threaded hole in a tank.As with any IC, the LM70 and accompanying wiring and circuits must be kept insulated and dry, to avoid leakage and corrosion. This is especially true if the circuit may operate at cold temperatures where condensation can occur. Printed-circuit coatings and varnishes such as Humiseal and epoxy paints or dips are often used to insure that moisture cannot corrode the LM70 or its connections.



www.national.com

**4.0 Typical Applications![ref1]**

**LM70**

![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.027.png)

10122320

**FIGURE 8. Temperature monitor using Intel 196 processor**

![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.028.png)

10122319

**FIGURE 9. LM70 digital input control using micro-controller’s general purpose I/O.**

www.national.com 12

**Physical Dimensions** inches (millimeters) unless otherwise noted![ref2]

![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.029.png)

**8-Lead Molded Mini Small Outline Package (MSOP)**

**(JEDEC REGISTRATION NUMBER M0-187)**

**Order Number LM70CIMM-3, LM70CIMMX-3, LM70CIMM-5 or LM70CIMMX-5 NS Package Number MUA08A**

![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.030.png)

**8-Lead Molded Leadless Leadframe Package**

**Order Number LM70CILD-3, LM70CILDX-3, LM70CILD-5 or LM70CILDX-5 NS Package Number LDA08A**

13 www.national.com


**Notes![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.031.png)**

**10-BitplusSignDigitalTemperatureSensor**

**™**

National does not assume any responsibility for use of any circuitry described, no circuit patent licenses are implied and National reserves the right at any time without notice to change said circuitry and specifications.

For the most current product information visit us at www.national.com. **LM70~~SPI/MICROWIRE~~**

**LIFE SUPPORT POLICY**

NATIONAL’S PRODUCTS ARE NOT AUTHORIZED FOR USE AS CRITICAL COMPONENTS IN LIFE SUPPORT DEVICES OR SYSTEMS WITHOUT THE EXPRESS WRITTEN APPROVAL OF THE PRESIDENT AND GENERAL COUNSEL OF NATIONAL SEMICONDUCTOR CORPORATION. As used herein:

1\. Life support devices or systems are devices or systems 2. A critical component is any component of a life support which, (a) are intended for surgical implant into the body, or device or system whose failure to perform can be reasonably

(b) support or sustain life, and whose failure to perform when expected to cause the failure of the life support device or properly used in accordance with instructions for use system, or to affect its safety or effectiveness. provided in the labeling, can be reasonably expected to result

in a significant injury to the user.

**BANNED SUBSTANCE COMPLIANCE**

National Semiconductor certifies that the products and packing materials meet the provisions of the Customer Products Stewardship Specification (CSP-9-111C2) and the Banned Substances and Materials of Interest Specification (CSP-9-111S2) and contain no ‘‘Banned Substances’’ as defined in CSP-9-111S2.

**National Semiconductor National Semiconductor National Semiconductor National Semiconductor Americas![](Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.032.png) Customer Europe Customer Support Center Asia Pacific Customer Japan Customer Support Center Support Center** Fax: +49 (0) 180-530 85 86 **Support Center** Fax: 81-3-5639-7507

Email: new.feedback@nsc.com Email: europe.support@nsc.com Email: ap.support@nsc.com Email: jpn.feedback@nsc.com Tel: 1-800-272-9959 Deutsch Tel: +49 (0) 69 9508 6208 Tel: 81-3-5639-7560

English Tel: +44 (0) 870 24 0 2171

www.national.com Français Tel: +33 (0) 1 41 91 8790

This datasheet has been download from: [www.datasheetcatalog.com](http://www.datasheetcatalog.com)

Datasheets for electronics components.

National Semiconductor was acquired by Texas Instruments.

http://www.ti.com/corp/docs/investor\_relations/pr\_09\_23\_2011\_national\_semiconductor.html

This file is the datasheet for the following electronic components: 

LM70EVAL-MSOP - http://www.ti.com/product/lm70eval-msop?HQS=TI-null-null-dscatalog-df-pf-null-wwe LM70CIMM-5 - http://www.ti.com/product/lm70cimm-5?HQS=TI-null-null-dscatalog-df-pf-null-wwe LM70CIMM-3 - http://www.ti.com/product/lm70cimm-3?HQS=TI-null-null-dscatalog-df-pf-null-wwe LM70CILDX-5 - http://www.ti.com/product/lm70cildx-5?HQS=TI-null-null-dscatalog-df-pf-null-wwe LM70CILDX-3 - http://www.ti.com/product/lm70cildx-3?HQS=TI-null-null-dscatalog-df-pf-null-wwe LM70CILD-5 - http://www.ti.com/product/lm70cild-5?HQS=TI-null-null-dscatalog-df-pf-null-wwe LM70EVAL-LLP - http://www.ti.com/product/lm70eval-llp?HQS=TI-null-null-dscatalog-df-pf-null-wwe LM70CIMMX-5 - http://www.ti.com/product/lm70cimmx-5?HQS=TI-null-null-dscatalog-df-pf-null-wwe LM70CILD-3 - http://www.ti.com/product/lm70cild-3?HQS=TI-null-null-dscatalog-df-pf-null-wwe LM70CIMMX-3 - http://www.ti.com/product/lm70cimmx-3?HQS=TI-null-null-dscatalog-df-pf-null-wwe

[ref1]: Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.004.png
[ref2]: Aspose.Words.2417c57c-2a17-4a3c-9c53-dd0b23e8ab44.007.png
