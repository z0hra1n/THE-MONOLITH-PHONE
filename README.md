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

+----+------------------------+------------------------------------------+----------------------------------------------+-----+------------+--------------+
| #  | Source                 | Part Number                              | Description                                  | Qty | Unit Price | Ext. Price   |
+----+------------------------+------------------------------------------+----------------------------------------------+-----+------------+--------------+
| 1  | Digi-Key               | GRM188R61E106MA73J                       | 10µF 25V X5R 0603 Capacitor                  | 10  | ₹14.619    | ₹146.19      |
| 2  | Digi-Key               | GMC10X5R226M16NTCT                       | 22µF 16V 0603 Capacitor                      | 12  | ₹36.978    | ₹443.74      |
| 3  | Digi-Key               | TMK107B7105KA-T                          | 1µF 25V X7R 0603 Capacitor                   | 10  | ₹5.160     | ₹51.60       |
| 4  | Digi-Key               | GCM188R72A103KA37D                       | 10nF 100V X7R 0603 Capacitor                 | 5   | ₹9.560     | ₹47.80       |
| 5  | Digi-Key               | GCM188R71H473KA55D                       | 47nF 50V X7R 0603 Capacitor                  | 5   | ₹20.070    | ₹100.35      |
| 6  | Digi-Key               | CC0603ZRY5V9BB104                        | 100nF 50V Y5V 0603 Capacitor                 | 5   | ₹9.560     | ₹47.80       |
| 7  | Digi-Key               | QSCP251Q180J1GV001T                      | 18pF 250V C0G Capacitor                      | 5   | ₹25.800    | ₹129.00      |
| 8  | Digi-Key               | GRM188R61E475KE11D                       | 4.7µF 25V X5R 0603 Capacitor                 | 5   | ₹22.930    | ₹114.65      |
| 9  | Digi-Key               | CRCW060310K0FKEA                         | 10kΩ 1% 0603 Resistor                        | 15  | ₹3.058     | ₹45.87       |
| 10 | Digi-Key               | RC0603FR-0747KL                          | 47kΩ 1% 0603 Resistor                        | 5   | ₹9.560     | ₹47.80       |
| 11 | Digi-Key               | ERJ-3EKF2553V                            | 255kΩ 1% 0603 Resistor                       | 5   | ₹9.560     | ₹47.80       |
| 12 | Digi-Key               | RC0603JR-07180KL                         | 180kΩ 5% 0603 Resistor                       | 5   | ₹9.560     | ₹47.80       |
| 13 | Digi-Key               | ERJ-3EKF5602V                            | 56kΩ 1% 0603 Resistor                        | 5   | ₹9.560     | ₹47.80       |
| 14 | Digi-Key               | RC0603FR-072K2L                          | 2.2kΩ 1% 0603 Resistor                       | 10  | ₹2.389     | ₹23.89       |
| 15 | Digi-Key               | RC0603FR-075K1L                          | 5.1kΩ 1% 0603 Resistor                       | 5   | ₹10.510    | ₹52.55       |
| 16 | Digi-Key               | RT0603BRD0729K8L                         | 29.8kΩ 0.1% 0603 Resistor                    | 5   | ₹10.510    | ₹52.55       |
| 17 | Digi-Key               | RC0603FR-0712KL                          | 12kΩ 1% 0603 Resistor                        | 5   | ₹9.560     | ₹47.80       |
| 18 | Digi-Key               | ERJ-3GEYJ244V                            | 240kΩ 5% 0603 Resistor                       | 5   | ₹9.560     | ₹47.80       |
| 19 | Digi-Key               | CRCW06031K00FKEA                         | 1kΩ 1% 0603 Resistor                         | 5   | ₹9.560     | ₹47.80       |
| 20 | Digi-Key               | 2309407-1                                | 260-pin SODIMM Socket                        | 2   | ₹174.860   | ₹349.72      |
| 21 | Digi-Key               | FH12-22S-0.5SH(55)                       | 22-pin FFC Connector                         | 2   | ₹245.560   | ₹491.12      |
| 22 | Digi-Key               | 0467651301                               | Micro HDMI Receptacle                        | 2   | ₹196.830   | ₹393.66      |
| 23 | Digi-Key               | USB4970-00-A                             | USB Type-C Receptacle                        | 2   | ₹30.580    | ₹61.16       |
| 24 | Digi-Key               | BQ25895RTWR                              | Li-Ion Battery Charger IC                    | 2   | ₹321.050   | ₹642.10      |
| 25 | Digi-Key               | SSM2518CPZ                               | Class-D Audio Amplifier                      | 1   | ₹717.580   | ₹717.58      |
| 26 | Digi-Key               | SMAJ6.0CA                                | 6V TVS Diode                                 | 2   | ₹45.860    | ₹91.72       |
| 27 | Digi-Key               | TPS61088RHLR                             | 10A Boost Converter                          | 2   | ₹261.810   | ₹523.62      |
| 28 | Digi-Key               | TPD2EUSB30DRTR                           | USB ESD Protection                           | 5   | ₹112.750   | ₹563.75      |
| 29 | Digi-Key               | CA-DKCA1-100L1-I0I0                      | U.FL (MHF1) Coax Cable                       | 1   | ₹204.480   | ₹204.48      |
| 30 | Digi-Key               | USB2512B-AEZG                            | USB 2.0 2-Port Hub                           | 2   | ₹168.170   | ₹336.34      |
| 31 | Digi-Key               | BMI270                                   | 6-Axis IMU                                   | 1   | ₹404.180   | ₹404.18      |
| 32 | Digi-Key               | 24MHz Crystal                            | 24MHz Crystal                                | 2   | ₹49.690    | ₹99.38       |
| 33 | Digi-Key               | SWT0005-015516SSAC                       | Tactile Push Button                          | 5   | ₹36.310    | ₹181.55      |
| 34 | Digi-Key               | MWSA1205S-2R2MT                          | 2.2µH 15A Inductor                           | 2   | ₹140.460   | ₹280.92      |
| 35 | Digi-Key               | 74437349010                              | 1µH 10A Inductor                             | 2   | ₹220.720   | ₹441.44      |
| 36 | Digi-Key               | AP2112K-1.8TRG1                          | 1.8V LDO Regulator                           | 2   | ₹25.800    | ₹51.60       |
| 37 | Digi-Key               | TLV75533PDQNR                            | 3.3V LDO Regulator                           | 2   | ₹29.620    | ₹59.24       |
| 38 | Digi-Key               | AANI-FB-0173                             | LTE FPC Antenna                              | 1   | ₹280.920   | ₹280.92      |
| 39 | Digi-Key               | FIT0649                                  | Micro HDMI to Mini HDMI Cable                | 1   | ₹468.200   | ₹468.20      |
| 40 | Digi-Key               | DH-20M50055                              | USB-A to Micro USB Cable                     | 2   | ₹150.970   | ₹301.94      |
| 41 | Digi-Key               | 10165794-Z0100YBLF                       | USB-C to USB-C Cable                         | 1   | ₹446.220   | ₹446.22      |
| 42 | Digi-Key               | C0603C104K3RACTU                         | 100nF 25V X7R Capacitor                      | 10  | ₹6.689     | ₹66.89       |
| 43 | Digi-Key               | 6308                                     | Heat Sink Thermal Sticker                    | 1   | ₹143.330   | ₹143.33      |
| 44 | Digi-Key               | KAPTON-TAPE10MM                          | 10mm Kapton Tape                             | 1   | ₹278.050   | ₹278.05      |
| 45 | Digi-Key               | B57861S0103F040                          | 10kΩ NTC Thermistor                          | ?   | ?          | ?            |
| 46 | Arducam               | B0517                                     | 12MP IMX477P Camera                          | 1   | $59.99     | $59.99       |
| 47 | AliExpress            | Various                                   | Battery, BLE, Connectors (4 items)           | 4   | —          | $290.47      |
| 48 | PCB Fab               | —                                         | PCB Manufacturing + Engineering              | 1   | —          | ₹7,858.80    |
| 49 | Amazon               | Duracell 20000mAh                          | 22.5W PD Power Bank                          | 1   | ₹3,029.00  | ₹3,029.00    |
| 50 | Fabricator           | —                                         | CNC Aluminium Enclosure (Estimate)           | 1   | —          | $100.00      |
+----+------------------------+------------------------------------------+----------------------------------------------+-----+------------+--------------+

Estimated Total Project Cost ≈ $666 USD
