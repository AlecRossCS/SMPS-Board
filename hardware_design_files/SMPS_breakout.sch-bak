EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title ""
Date ""
Rev ""
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L Regulator_Switching:LM2576HVS-ADJ U1
U 1 1 61414D30
P 6800 2100
F 0 "U1" H 6800 2467 50  0000 C CNN
F 1 "LM2576HVS-ADJ" H 6800 2376 50  0000 C CNN
F 2 "Package_TO_SOT_SMD:TO-263-5_TabPin3" H 6800 1850 50  0001 L CIN
F 3 "http://www.ti.com/lit/ds/symlink/lm2576.pdf" H 6800 2100 50  0001 C CNN
	1    6800 2100
	1    0    0    -1  
$EndComp
$Comp
L Device:Q_PMOS_GDS Q1
U 1 1 61417CE1
P 2250 1800
F 0 "Q1" V 2592 1800 50  0000 C CNN
F 1 "Q_PMOS_GDS" V 2501 1800 50  0000 C CNN
F 2 "Package_TO_SOT_SMD:TO-252-3_TabPin2" H 2450 1900 50  0001 C CNN
F 3 "~" H 2250 1800 50  0001 C CNN
	1    2250 1800
	0    -1   -1   0   
$EndComp
Text Notes 550  700  0    50   ~ 10
Reverse Voltage protection\n
$Comp
L Device:R R1
U 1 1 61419BEA
P 2250 2250
F 0 "R1" H 2320 2296 50  0000 L CNN
F 1 "100k" H 2320 2205 50  0000 L CNN
F 2 "Resistor_SMD:R_0805_2012Metric_Pad1.20x1.40mm_HandSolder" V 2180 2250 50  0001 C CNN
F 3 "~" H 2250 2250 50  0001 C CNN
	1    2250 2250
	1    0    0    -1  
$EndComp
$Comp
L Device:D_Zener_ALT D1
U 1 1 6141A346
P 2650 1900
F 0 "D1" V 2604 1980 50  0000 L CNN
F 1 "10v" V 2695 1980 50  0000 L CNN
F 2 "Diode_SMD:D_SOD-123" H 2650 1900 50  0001 C CNN
F 3 "~" H 2650 1900 50  0001 C CNN
	1    2650 1900
	0    1    1    0   
$EndComp
Wire Wire Line
	2250 2000 2250 2050
Wire Wire Line
	2650 2050 2250 2050
Connection ~ 2250 2050
Wire Wire Line
	2250 2050 2250 2100
Wire Wire Line
	2650 1750 2650 1700
Wire Wire Line
	2650 1700 2450 1700
Connection ~ 2650 1700
Text GLabel 2950 1700 2    50   Output ~ 0
PInput
Wire Wire Line
	2650 1700 2950 1700
Text GLabel 4550 2000 0    50   Input ~ 0
PInput
$Comp
L Device:D_Schottky D2
U 1 1 6141C324
P 7550 2350
F 0 "D2" V 7504 2430 50  0000 L CNN
F 1 "D_Schottky" V 7595 2430 50  0000 L CNN
F 2 "Diode_SMD:D_SMA-SMB_Universal_Handsoldering" H 7550 2350 50  0001 C CNN
F 3 "~" H 7550 2350 50  0001 C CNN
	1    7550 2350
	0    1    1    0   
$EndComp
$Comp
L Device:L L1
U 1 1 6141CBBA
P 8050 2200
F 0 "L1" V 8240 2200 50  0000 C CNN
F 1 "L" V 8149 2200 50  0000 C CNN
F 2 "Inductor_SMD:L_Bourns_SRR1210A" H 8050 2200 50  0001 C CNN
F 3 "~" H 8050 2200 50  0001 C CNN
	1    8050 2200
	0    -1   -1   0   
$EndComp
Wire Wire Line
	7300 2200 7550 2200
Wire Wire Line
	7900 2200 7550 2200
Connection ~ 7550 2200
$Comp
L Device:R R3
U 1 1 6141FBDF
P 8300 2050
F 0 "R3" H 8370 2096 50  0000 L CNN
F 1 "R" H 8370 2005 50  0000 L CNN
F 2 "Resistor_SMD:R_0805_2012Metric_Pad1.20x1.40mm_HandSolder" V 8230 2050 50  0001 C CNN
F 3 "~" H 8300 2050 50  0001 C CNN
	1    8300 2050
	1    0    0    -1  
$EndComp
$Comp
L Device:R R2
U 1 1 61421F64
P 8300 1700
F 0 "R2" H 8230 1654 50  0000 R CNN
F 1 "R" H 8230 1745 50  0000 R CNN
F 2 "Resistor_SMD:R_0805_2012Metric_Pad1.20x1.40mm_HandSolder" V 8230 1700 50  0001 C CNN
F 3 "~" H 8300 1700 50  0001 C CNN
	1    8300 1700
	-1   0    0    1   
$EndComp
Wire Wire Line
	8300 1900 8300 1850
Wire Wire Line
	7300 2000 7400 2000
Wire Wire Line
	7400 2000 7400 1900
Wire Wire Line
	7400 1900 8300 1900
Connection ~ 8300 1900
Wire Wire Line
	8300 2200 8200 2200
$Comp
L Device:Jumper_NO_Small JP2
U 1 1 614248F0
P 8550 2050
F 0 "JP2" V 8504 2098 50  0000 L CNN
F 1 "fixed" V 8595 2098 50  0000 L CNN
F 2 "Jumper:SolderJumper-2_P1.3mm_Open_RoundedPad1.0x1.5mm" H 8550 2050 50  0001 C CNN
F 3 "~" H 8550 2050 50  0001 C CNN
	1    8550 2050
	0    1    1    0   
$EndComp
Wire Wire Line
	8550 2150 8550 2200
Wire Wire Line
	8550 2200 8300 2200
Connection ~ 8300 2200
Wire Wire Line
	8550 1950 8550 1900
Wire Wire Line
	8550 1900 8300 1900
$Comp
L Device:CP_Small C5
U 1 1 61425BD7
P 9150 2300
F 0 "C5" H 9238 2346 50  0000 L CNN
F 1 "1000u" H 9238 2255 50  0000 L CNN
F 2 "Capacitor_SMD:CP_Elec_16x17.5" H 9150 2300 50  0001 C CNN
F 3 "~" H 9150 2300 50  0001 C CNN
	1    9150 2300
	1    0    0    -1  
$EndComp
Text GLabel 10050 2200 2    50   Output ~ 0
Power_rail
$Comp
L Device:C_Small C1
U 1 1 61439841
P 4600 2100
F 0 "C1" H 4692 2146 50  0000 L CNN
F 1 "10u" H 4692 2055 50  0000 L CNN
F 2 "Capacitor_SMD:C_1210_3225Metric_Pad1.33x2.70mm_HandSolder" H 4600 2100 50  0001 C CNN
F 3 "~" H 4600 2100 50  0001 C CNN
	1    4600 2100
	1    0    0    -1  
$EndComp
Wire Wire Line
	4550 2000 4600 2000
$Comp
L power:GND1 #PWR02
U 1 1 61451438
P 4600 2300
F 0 "#PWR02" H 4600 2050 50  0001 C CNN
F 1 "GND1" H 4605 2127 50  0000 C CNN
F 2 "" H 4600 2300 50  0001 C CNN
F 3 "" H 4600 2300 50  0001 C CNN
	1    4600 2300
	1    0    0    -1  
$EndComp
$Comp
L power:GND1 #PWR01
U 1 1 61452539
P 2250 2550
F 0 "#PWR01" H 2250 2300 50  0001 C CNN
F 1 "GND1" H 2255 2377 50  0000 C CNN
F 2 "" H 2250 2550 50  0001 C CNN
F 3 "" H 2250 2550 50  0001 C CNN
	1    2250 2550
	1    0    0    -1  
$EndComp
Wire Wire Line
	7550 2550 7550 2500
Wire Wire Line
	9150 2450 9150 2400
Wire Wire Line
	4600 2300 4600 2200
$Comp
L power:GND1 #PWR03
U 1 1 6146C59E
P 5100 2300
F 0 "#PWR03" H 5100 2050 50  0001 C CNN
F 1 "GND1" H 5105 2127 50  0000 C CNN
F 2 "" H 5100 2300 50  0001 C CNN
F 3 "" H 5100 2300 50  0001 C CNN
	1    5100 2300
	1    0    0    -1  
$EndComp
Wire Wire Line
	5100 2300 5100 2200
$Comp
L Device:C_Small C3
U 1 1 6146FF06
P 5600 2100
F 0 "C3" H 5692 2146 50  0000 L CNN
F 1 "10u" H 5692 2055 50  0000 L CNN
F 2 "Capacitor_SMD:C_1210_3225Metric_Pad1.33x2.70mm_HandSolder" H 5600 2100 50  0001 C CNN
F 3 "~" H 5600 2100 50  0001 C CNN
	1    5600 2100
	1    0    0    -1  
$EndComp
$Comp
L power:GND1 #PWR04
U 1 1 6146FF0C
P 5600 2300
F 0 "#PWR04" H 5600 2050 50  0001 C CNN
F 1 "GND1" H 5605 2127 50  0000 C CNN
F 2 "" H 5600 2300 50  0001 C CNN
F 3 "" H 5600 2300 50  0001 C CNN
	1    5600 2300
	1    0    0    -1  
$EndComp
Wire Wire Line
	6300 2000 5600 2000
$Comp
L Device:C_Small C4
U 1 1 61472240
P 8650 2300
F 0 "C4" H 8742 2346 50  0000 L CNN
F 1 "10u" H 8742 2255 50  0000 L CNN
F 2 "Capacitor_SMD:C_1210_3225Metric_Pad1.33x2.70mm_HandSolder" H 8650 2300 50  0001 C CNN
F 3 "~" H 8650 2300 50  0001 C CNN
	1    8650 2300
	1    0    0    -1  
$EndComp
$Comp
L Device:C_Small C6
U 1 1 6147224D
P 9600 2300
F 0 "C6" H 9692 2346 50  0000 L CNN
F 1 "10u" H 9692 2255 50  0000 L CNN
F 2 "Capacitor_SMD:C_1210_3225Metric_Pad1.33x2.70mm_HandSolder" H 9600 2300 50  0001 C CNN
F 3 "~" H 9600 2300 50  0001 C CNN
	1    9600 2300
	1    0    0    -1  
$EndComp
Wire Wire Line
	8650 2400 8650 2450
Wire Wire Line
	8650 2200 8550 2200
Connection ~ 8550 2200
Connection ~ 8650 2200
Wire Wire Line
	9600 2450 9600 2400
$Comp
L Device:CP_Small C2
U 1 1 6147DFDC
P 5100 2100
F 0 "C2" H 5188 2146 50  0000 L CNN
F 1 "100u" H 5188 2055 50  0000 L CNN
F 2 "Capacitor_SMD:CP_Elec_8x10" H 5100 2100 50  0001 C CNN
F 3 "~" H 5100 2100 50  0001 C CNN
	1    5100 2100
	1    0    0    -1  
$EndComp
Wire Wire Line
	5600 2000 5100 2000
Connection ~ 5600 2000
Wire Wire Line
	5100 2000 4600 2000
Connection ~ 5100 2000
Connection ~ 4600 2000
Wire Wire Line
	6800 2500 6800 2450
Connection ~ 9600 2200
Wire Wire Line
	9600 2200 10050 2200
Wire Wire Line
	8650 2200 9150 2200
Connection ~ 9150 2200
Wire Wire Line
	9150 2200 9600 2200
Wire Wire Line
	6050 2200 6300 2200
Wire Wire Line
	2250 2400 2250 2500
Wire Wire Line
	2250 2500 1600 2500
Wire Wire Line
	1600 2500 1600 1800
Connection ~ 2250 2500
Wire Wire Line
	2250 2500 2250 2550
Text GLabel 9450 950  0    50   Input ~ 0
Power_rail
Wire Wire Line
	9100 1100 9100 1150
Text Label 7450 2200 0    50   ~ 0
Buck_Out
Text Label 7700 1900 0    50   ~ 0
FB
Text Label 1800 1700 0    50   ~ 0
Input
Wire Wire Line
	1600 1800 1450 1800
$Comp
L Connector_Generic:Conn_01x02 J3
U 1 1 614DA522
P 10350 850
F 0 "J3" H 10430 842 50  0000 L CNN
F 1 "Conn_01x02" H 10430 751 50  0000 L CNN
F 2 "Connector_PinSocket_2.54mm:PinSocket_1x02_P2.54mm_Vertical" H 10350 850 50  0001 C CNN
F 3 "~" H 10350 850 50  0001 C CNN
	1    10350 850 
	1    0    0    -1  
$EndComp
$Comp
L Connector_Generic:Conn_01x02 J4
U 1 1 614DBA97
P 10350 1100
F 0 "J4" H 10430 1092 50  0000 L CNN
F 1 "Conn_01x02" H 10430 1001 50  0000 L CNN
F 2 "Connector_PinSocket_2.54mm:PinSocket_1x02_P2.54mm_Vertical" H 10350 1100 50  0001 C CNN
F 3 "~" H 10350 1100 50  0001 C CNN
	1    10350 1100
	1    0    0    -1  
$EndComp
Wire Wire Line
	9100 1100 9850 1100
Wire Wire Line
	10150 1200 9850 1200
Wire Wire Line
	9850 1200 9850 1100
Connection ~ 9850 1100
Wire Wire Line
	9850 1100 10150 1100
Wire Wire Line
	9450 950  9850 950 
Wire Wire Line
	10150 850  9850 850 
Wire Wire Line
	9850 850  9850 950 
Connection ~ 9850 950 
Wire Wire Line
	9850 950  10150 950 
$Comp
L Connector_Generic:Conn_01x02 J1
U 1 1 614EAD0B
P 1000 1700
F 0 "J1" H 1080 1692 50  0000 L CNN
F 1 "Conn_01x02" H 1080 1601 50  0000 L CNN
F 2 "Connector_PinSocket_2.54mm:PinSocket_1x02_P2.54mm_Vertical" H 1000 1700 50  0001 C CNN
F 3 "~" H 1000 1700 50  0001 C CNN
	1    1000 1700
	-1   0    0    1   
$EndComp
$Comp
L Connector_Generic:Conn_01x02 J2
U 1 1 614ED5BF
P 1000 1900
F 0 "J2" H 1080 1892 50  0000 L CNN
F 1 "Conn_01x02" H 1080 1801 50  0000 L CNN
F 2 "Connector_PinSocket_2.54mm:PinSocket_1x02_P2.54mm_Vertical" H 1000 1900 50  0001 C CNN
F 3 "~" H 1000 1900 50  0001 C CNN
	1    1000 1900
	-1   0    0    1   
$EndComp
Wire Wire Line
	1200 1700 1450 1700
Wire Wire Line
	1450 1700 1450 1600
Wire Wire Line
	1450 1600 1200 1600
Connection ~ 1450 1700
Wire Wire Line
	1450 1700 2050 1700
Wire Wire Line
	1450 1800 1450 1900
Wire Wire Line
	1450 1900 1200 1900
Wire Wire Line
	1450 1800 1200 1800
Connection ~ 1450 1800
Wire Wire Line
	6050 2450 6800 2450
Connection ~ 6800 2450
Wire Wire Line
	6800 2450 6800 2400
Text Label 6050 2200 0    50   ~ 0
En
Wire Wire Line
	5600 2300 5600 2200
Wire Wire Line
	6050 2200 6050 2450
$Comp
L power:GND1 #PWR0101
U 1 1 614D4AC1
P 6800 2500
F 0 "#PWR0101" H 6800 2250 50  0001 C CNN
F 1 "GND1" H 6805 2327 50  0000 C CNN
F 2 "" H 6800 2500 50  0001 C CNN
F 3 "" H 6800 2500 50  0001 C CNN
	1    6800 2500
	1    0    0    -1  
$EndComp
$Comp
L power:GND1 #PWR0102
U 1 1 614D5BCD
P 7550 2550
F 0 "#PWR0102" H 7550 2300 50  0001 C CNN
F 1 "GND1" H 7555 2377 50  0000 C CNN
F 2 "" H 7550 2550 50  0001 C CNN
F 3 "" H 7550 2550 50  0001 C CNN
	1    7550 2550
	1    0    0    -1  
$EndComp
$Comp
L power:GND1 #PWR0103
U 1 1 614D6D15
P 8650 2450
F 0 "#PWR0103" H 8650 2200 50  0001 C CNN
F 1 "GND1" H 8655 2277 50  0000 C CNN
F 2 "" H 8650 2450 50  0001 C CNN
F 3 "" H 8650 2450 50  0001 C CNN
	1    8650 2450
	1    0    0    -1  
$EndComp
$Comp
L power:GND1 #PWR0104
U 1 1 614D7D4C
P 9150 2450
F 0 "#PWR0104" H 9150 2200 50  0001 C CNN
F 1 "GND1" H 9155 2277 50  0000 C CNN
F 2 "" H 9150 2450 50  0001 C CNN
F 3 "" H 9150 2450 50  0001 C CNN
	1    9150 2450
	1    0    0    -1  
$EndComp
$Comp
L power:GND1 #PWR0105
U 1 1 614D8E74
P 9600 2450
F 0 "#PWR0105" H 9600 2200 50  0001 C CNN
F 1 "GND1" H 9605 2277 50  0000 C CNN
F 2 "" H 9600 2450 50  0001 C CNN
F 3 "" H 9600 2450 50  0001 C CNN
	1    9600 2450
	1    0    0    -1  
$EndComp
$Comp
L power:GND1 #PWR0106
U 1 1 614DA021
P 9100 1150
F 0 "#PWR0106" H 9100 900 50  0001 C CNN
F 1 "GND1" H 9105 977 50  0000 C CNN
F 2 "" H 9100 1150 50  0001 C CNN
F 3 "" H 9100 1150 50  0001 C CNN
	1    9100 1150
	1    0    0    -1  
$EndComp
Wire Wire Line
	9100 1100 8300 1100
Wire Wire Line
	8300 1100 8300 1550
Connection ~ 9100 1100
Wire Notes Line
	500  550  500  2850
Wire Notes Line
	3550 550  3550 2850
Wire Notes Line
	11100 550  11100 2850
Wire Notes Line
	500  550  11100 550 
Wire Notes Line
	500  2850 11100 2850
Text Notes 3600 700  0    50   ~ 10
Buck Converter
Text Notes 5400 1550 0    50   Italic 0
App Note:\nthis schematic will work with an LM2576.\nincluding fixed versions, exclude resistors.\n R2 and R3 are only needed in the adj model\nVout = Vref*((R3/R2) + 1)\nInductor needs to be sized for current flow and voltage\n5v -> 120uH @2.5A
$EndSCHEMATC
