# MONOLITH
<img width="2000" height="2000" alt="MONOLITH  (1)" src="https://github.com/user-attachments/assets/a57141d0-c331-43c9-a943-bfd9e5269df6" />

Ahh, i finally get to yap about it.
This is MONOLITH. a phone, a brick , a portable computer, but most importantly, a MONOLITH.
The reason im calling it a monolith cuz its literally gonna be built like a shiny MONOLITH. especially because its outer body is inteded to be made from aluminum which acts as a passive heat sink and looks pretty cool.The design was heavily inspired by Nothing and Apple.

The pcb is quite complicated, and the design is pretty human.It was not easy to make as i am only 15, this is my second pcb, the schematic itself was very hard.The pcb ws harder.I got help from reddit and tomachie.com with the schematic so it was pretty easy to disagnose.But, when it came to me m,aking the pcb, after i was done connecting everything, the drc gave 2000 violations.I was scared, but turns out most of those were easy fixable in one or two clicks.I also did not keep in mind the manufacturing constraints, so i fixed the values, and most of the errors were gone.I was pleased.

<img width="486" height="848" alt="Screenshot 2026-08-06 211827" src="https://github.com/user-attachments/assets/dae78e4c-e6d6-4ea7-8eba-6d36afcc78e2" />
<img width="964" height="747" alt="image" src="https://github.com/user-attachments/assets/c0a0b757-9898-424e-98a3-8c2f12f18ffc" />
<img width="879" height="690" alt="image" src="https://github.com/user-attachments/assets/7ea41290-570f-4b81-9b41-ae089127bde7" />
<img width="1061" height="739" alt="image" src="https://github.com/user-attachments/assets/dcb5bd85-752f-4220-b85c-534f84602828" />

Finally, i made the enclosure very minimalist and functional.The back has a plastic went to let out the rf and wifi/bt signals.
the rear camera physically rotates to become the selfie camera.

<img width="398" height="643" alt="Screenshot 2026-08-06 215343" src="https://github.com/user-attachments/assets/88f685f4-95b9-4497-aa25-2f9728020a9b" />


The specs are pretty nuts.It has the radxa nx5 16 gb ram and 256 emms variant.An oled with 120hz refresh rate, and a batter of about 120000 mah.Im not sure itll last much without optimisation tho.

Yeah! i hope it overtakes apple!

## Bill of Materials

| Purpose | Component / Item | Qty | Total Cost | Distributor | Part Number |
|---------|-------------------|----:|-----------:|------------|-------------|
| Decoupling | 10µF 25V X5R 0603 Capacitor | 10 | ₹146.19 | Digi-Key | GRM188R61E106MA73J |
| Bulk Decoupling | 22µF 16V 0603 Capacitor | 12 | ₹443.74 | Digi-Key | GMC10X5R226M16NTCT |
| Power Filtering | 1µF 25V X7R 0603 Capacitor | 10 | ₹51.60 | Digi-Key | TMK107B7105KA-T |
| Signal Filtering | 10nF 100V X7R Capacitor | 5 | ₹47.80 | Digi-Key | GCM188R72A103KA37D |
| Signal Filtering | 47nF 50V X7R Capacitor | 5 | ₹100.35 | Digi-Key | GCM188R71H473KA55D |
| Decoupling | 100nF 50V Y5V Capacitor | 5 | ₹47.80 | Digi-Key | CC0603ZRY5V9BB104 |
| Crystal Load | 18pF C0G Capacitor | 5 | ₹129.00 | Digi-Key | QSCP251Q180J1GV001T |
| Power Filtering | 4.7µF 25V X5R Capacitor | 5 | ₹114.65 | Digi-Key | GRM188R61E475KE11D |
| Pull-ups / General | 10kΩ 1% Resistor | 15 | ₹45.87 | Digi-Key | CRCW060310K0FKEA |
| Voltage Divider | 47kΩ 1% Resistor | 5 | ₹47.80 | Digi-Key | RC0603FR-0747KL |
| Feedback Divider | 255kΩ 1% Resistor | 5 | ₹47.80 | Digi-Key | ERJ-3EKF2553V |
| Feedback Divider | 180kΩ 5% Resistor | 5 | ₹47.80 | Digi-Key | RC0603JR-07180KL |
| Feedback Divider | 56kΩ 1% Resistor | 5 | ₹47.80 | Digi-Key | ERJ-3EKF5602V |
| Pull-ups | 2.2kΩ 1% Resistor | 10 | ₹23.89 | Digi-Key | RC0603FR-072K2L |
| USB Configuration | 5.1kΩ 1% Resistor | 5 | ₹52.55 | Digi-Key | RC0603FR-075K1L |
| Precision Divider | 29.8kΩ 0.1% Resistor | 5 | ₹52.55 | Digi-Key | RT0603BRD0729K8L |
| General Purpose | 12kΩ 1% Resistor | 5 | ₹47.80 | Digi-Key | RC0603FR-0712KL |
| Feedback Divider | 240kΩ 5% Resistor | 5 | ₹47.80 | Digi-Key | ERJ-3GEYJ244V |
| General Purpose | 1kΩ 1% Resistor | 5 | ₹47.80 | Digi-Key | CRCW06031K00FKEA |
| Compute Module Interface | 260-pin SODIMM Socket | 2 | ₹349.72 | Digi-Key | 2309407-1 |
| Display Interface | 22-pin FFC Connector | 2 | ₹491.12 | Digi-Key | FH12-22S-0.5SH(55) |
| Display Output | Micro HDMI Receptacle | 2 | ₹393.66 | Digi-Key | 0467651301 |
| USB Connectivity | USB Type-C Receptacle | 2 | ₹61.16 | Digi-Key | USB4970-00-A |
| Battery Charging | BQ25895 Li-Ion Charger IC | 2 | ₹642.10 | Digi-Key | BQ25895RTWR |
| Audio Output | SSM2518 Class-D Amplifier | 1 | ₹717.58 | Digi-Key | SSM2518CPZ |
| Input Protection | 6V TVS Diode | 2 | ₹91.72 | Digi-Key | SMAJ6.0CA |
| 5V Power Rail | TPS61088 10A Boost Converter | 2 | ₹523.62 | Digi-Key | TPS61088RHLR |
| USB Protection | USB ESD Protection IC | 5 | ₹563.75 | Digi-Key | TPD2EUSB30DRTR |
| RF Connection | U.FL (MHF1) Coax Cable | 1 | ₹204.48 | Digi-Key | CA-DKCA1-100L1-I0I0 |
| USB Expansion | USB2512B 2-Port USB Hub | 2 | ₹336.34 | Digi-Key | USB2512B-AEZG |
| Motion Sensing | BMI270 IMU | 1 | ₹404.18 | Digi-Key | BMI270 |
| Clock Source | 24MHz Crystal | 2 | ₹99.38 | Digi-Key | 535-10643-1 |
| User Input | Tactile Push Button | 5 | ₹181.55 | Digi-Key | SWT0005-015516SSAC |
| Power Stage | 2.2µH 15A Inductor | 2 | ₹280.92 | Digi-Key | MWSA1205S-2R2MT |
| Power Stage | 1µH 10A Inductor | 2 | ₹441.44 | Digi-Key | 74437349010 |
| 1.8V Rail | AP2112K 1.8V LDO | 2 | ₹51.60 | Digi-Key | AP2112K-1.8TRG1 |
| 3.3V Rail | TLV75533 3.3V LDO | 2 | ₹59.24 | Digi-Key | TLV75533PDQNR |
| Cellular Connectivity | LTE FPC Antenna | 1 | ₹280.92 | Digi-Key | AANI-FB-0173 |
| Display Cable | Micro HDMI to Mini HDMI Cable | 1 | ₹468.20 | Digi-Key | FIT0649 |
| USB Accessories | USB-A to Micro USB Cable | 2 | ₹301.94 | Digi-Key | DH-20M50055 |
| USB Accessories | USB-C to USB-C Cable | 1 | ₹446.22 | Digi-Key | 10165794-Z0100YBLF |
| Additional Decoupling | 100nF X7R Capacitor | 10 | ₹66.89 | Digi-Key | C0603C104K3RACTU |
| Thermal Management | Heat Sink Thermal Sticker | 1 | ₹143.33 | Digi-Key | 6308 |
| Assembly | Kapton Tape (10mm) | 1 | ₹278.05 | Digi-Key | KAPTON-TAPE10MM |
| Temperature Monitoring | 10kΩ NTC Thermistor | 2 | ₹188.23 | Digi-Key | B57861S0103F040 |
| Camera | 12MP IMX477P Camera Module | 1 | $59.99 | Arducam | B0517 |
| Miscellaneous | Batteries, BLE Module, Connectors | 4 | $290.47 | AliExpress | Various |
| PCB Manufacturing | PCB Fabrication + Engineering | 1 | ₹7,858.80 | PCB Fab | — |
| Portable Power | 20,000mAh Power Bank | 1 | ₹3,029.00 | Amazon | Duracell |
| Enclosure | CNC Aluminium Enclosure (Estimate) | 1 | $100.00 | Local Fabricator | — |

**Estimated Total Project Cost:** **≈ USD 666**
