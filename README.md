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

BOM:

#	Source	Part/Item	Description	Qty	Unit Price	Ext Price
1	Digi-Key	490-12737-1-ND / GRM188R61E106MA73J	CAP CER 10UF 25V X5R 0603	10	₹14.619	₹146.19
2	Digi-Key	4713-GMC10X5R226M16NTCT-ND	CAP 22UF 20% 16V 0603	12	₹36.978	₹443.74
3	Digi-Key	587-2984-1-ND / TMK107B7105KA-T	CAP CER 1UF 25V X7R 0603	10	₹5.160	₹51.60
4	Digi-Key	490-4781-1-ND / GCM188R72A103KA37D	CAP CER 10000PF 100V X7R 0603	5	₹9.560	₹47.80
5	Digi-Key	490-4934-1-ND / GCM188R71H473KA55D	CAP CER 0.047UF 50V X7R 0603	5	₹20.070	₹100.35
6	Digi-Key	311-1343-1-ND / CC0603ZRY5V9BB104	CAP CER 0.1UF 50V Y5V 0603	5	₹9.560	₹47.80
7	Digi-Key	712-QSCP251Q180J1GV001TCT-ND	CAP CER 18PF 250V C0G 0603	5	₹25.800	₹129.00
8	Digi-Key	490-7203-1-ND / GRM188R61E475KE11D	CAP CER 4.7UF 25V X5R 0603	5	₹22.930	₹114.65
9	Digi-Key	541-10.0KHCT-ND / CRCW060310K0FKEA	RES 10K 1% 1/8W 0603	15	₹3.058	₹45.87
10	Digi-Key	311-47.0KHRCT-ND / RC0603FR-0747KL	RES 47K 1% 1/10W 0603	5	₹9.560	₹47.80
11	Digi-Key	P255KHCT-ND / ERJ-3EKF2553V	RES 255K 1% 1/10W 0603	5	₹9.560	₹47.80
12	Digi-Key	311-180KGRCT-ND / RC0603JR-07180KL	RES 180K 5% 1/10W 0603	5	₹9.560	₹47.80
13	Digi-Key	P56.0KHCT-ND / ERJ-3EKF5602V	RES 56K 1% 1/10W 0603	5	₹9.560	₹47.80
14	Digi-Key	311-2.20KHRCT-ND / RC0603FR-072K2L	RES 2.2K 1% 1/10W 0603	10	₹2.389	₹23.89
15	Digi-Key	311-5.10KHRCT-ND / RC0603FR-075K1L	RES 5.1K 1% 1/10W 0603	5	₹10.510	₹52.55
16	Digi-Key	13-RT0603BRD0729K8LCT-ND	RES 29.8K 0.1% 1/10W 0603	5	₹10.510	₹52.55
17	Digi-Key	311-12.0KHRCT-ND / RC0603FR-0712KL	RES 12K 1% 1/10W 0603	5	₹9.560	₹47.80
18	Digi-Key	P240KGCT-ND / ERJ-3GEYJ244V	RES 240K 5% 1/10W 0603	5	₹9.560	₹47.80
19	Digi-Key	541-1.00KHCT-ND / CRCW06031K00FKEA	RES 1K 1% 1/8W 0603	5	₹9.560	₹47.80
20	Digi-Key	A126758CT-ND / 2309407-1	CONN SKT SODIMM 260POS SMD	2	₹174.860	₹349.72
21	Digi-Key	HFJ122CT-ND / FH12-22S-0.5SH(55)	CONN FFC 22POS 0.5MM R/A	2	₹245.560	₹491.12
22	Digi-Key	WM11255CT-ND / 0467651301	CONN RCP MICRO HDMI 19POS SMD RA	2	₹196.830	₹393.66
23	Digi-Key	2073-USB4970-00-ACT-ND	USB TYPE C 6P RECEPTACLE	2	₹30.580	₹61.16
24	Digi-Key	296-44345-1-ND / BQ25895RTWR	IC BATT CHG LI-ION 24WQFN	2	₹321.050	₹642.10
25	Digi-Key	505-SSM2518CPZ-ND	IC AUDIO AMP D 20-LFCSP	1	₹717.580	₹717.58
26	Digi-Key	SMAJ6.0CALFCT-ND	TVS DIODE 6VWM DO214AC	2	₹45.860	₹91.72
27	Digi-Key	296-43620-1-ND / TPS61088RHLR	IC REG BOOST ADJ 10A 20VQFN	2	₹261.810	₹523.62
28	Digi-Key	296-25509-1-ND / TPD2EUSB30DRTR	TVS DIODE 5.5VWM SOT3	5	₹112.750	₹563.75
29	Digi-Key	2057-CA-DKCA1-100L1-I0I0-ND	COAX CBL U.FL-MHF1 to U.FL-MHF1	1	₹204.480	₹204.48
30	Digi-Key	638-1103-ND / USB2512B-AEZG	IC USB 2.0 2PORT HUB 36QFN	2	₹168.170	₹336.34
31	Digi-Key	828-1091-1-ND / BMI270	IMU ACCEL/GYRO 14LGA	1	₹404.180	₹404.18
32	Digi-Key	535-10643-1-ND	CRYSTAL 24MHz 18pF SMD	2	₹49.690	₹99.38
33	Digi-Key	2073-SWT0005-015516SSACT-ND	TACTILE SWITCH SPST-NO	5	₹36.310	₹181.55
34	Digi-Key	3442-MWSA1205S-2R2MTCT-ND	FIXED IND 2.2uH 15A SMD	2	₹140.460	₹280.92
35	Digi-Key	732-3349-1-ND / 74437349010	FIXED IND 1uH 10A SMD	2	₹220.720	₹441.44
36	Digi-Key	AP2112K-1.8TRG1DICT-ND	IC REG LINEAR 1.8V 600mA SOT-25	2	₹25.800	₹51.60
37	Digi-Key	296-51806-1-ND / TLV75533PDQNR	IC REG LINEAR 3.3V 500mA X2SON	2	₹29.620	₹59.24
38	Digi-Key	535-AANI-FB-0173-1-ND	FPC ANTENNA LTE 4G/3G/2G	1	₹280.920	₹280.92
39	Digi-Key	1738-FIT0649-ND	CBL Micro HDMI-Mini HDMI 2.62'	1	₹468.200	₹468.20
40	Digi-Key	2987-DH-20M50055-ND	CBL USB AM-Micro, 1m	2	₹150.970	₹301.94
41	Digi-Key	609-10165794-Z0100YBLF-ND	CBL USB C-C	1	₹446.220	₹446.22
42	Digi-Key	399-C0603C104K3RACTUCT-ND	CAP CER 0.1UF 25V X7R 0603	10	₹6.689	₹66.89
43	Digi-Key	1528-6308-ND	HEAT SINK THERMAL STICKER TABS	1	₹143.330	₹143.33
44	Digi-Key	1188-KAPTON-TAPE10MM-ND	TAPE MASKING KAPTON	1	₹278.050	₹278.05
45	Digi-Key	495-2142-ND / B57861S0103F040	THERMISTOR NTC 10K 3988K BEAD	?	?	? (qty/price cut off)
46	Arducam	B0517	12MP IMX477P Camera Module for ROCK 5A/5B	1	$59.99	$59.99
47	AliExpress cart	(4 items — battery, BLE module, connectors)	Misc components, "almost sold out" cart	4	—	$290.47
48	PCB Fab	Board Fee + Engineering	PCB manufacture + assembly, 230g	1	—	₹7,858.80
49	Amazon	Duracell 20000mAh Powerbank	1 Type-C PD + 2 USB-A, 22.5W	1	₹3,029.00
50	Enclosure fabricator	CNC aluminium enclosure (estimate only, pending final model)	1	—	$100.00 (est.)	

Total ~ 666 usd.
