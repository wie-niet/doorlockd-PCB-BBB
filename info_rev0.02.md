# Info on PCB deuropener rev0.02

# Notes/Bugs: 

## printed output names of "Buzzer" and "Solenoid" were mixed up. Fixed in rev0.02.1 [Issue #3](https://github.com/wie-niet/doorlockd-PCB-BBB/issues/3)
The printed names of Buzzer and Solenoid were mixed up in rev0.02. make sure you use J13 for Solenoid and J5 for Buzzer or doorbell.

# GPIO
```
IO	P8_17	Button1
IO	P8_18	Button2
IO	P8_09	Buzzer
IO	P9_15	RC522_IRQ
IO	P9_21	RC522_MISO
IO	P9_18	RC522_MOSI
IO	P9_23	RC522_RST
IO	P9_22	RC522_SCK
IO	P9_17	RC522_SDA
IO	P9_12	Solenoid
IO	P9_14	UILED1
IO	P9_16	UILED2
IO	P8_19	UI_DuoLED1g
IO	P8_13	UI_DuoLED1r
```


## Components 
```
C1		1uF 
C2		1uF
C3		470u
D1		LED (red)
D2		1N4007
D3		LED (red)
D4		1N4007
J1		PinHeader 01x02	LED 1
J2		PinHeader 01x02	Button 2
J3		PinHeader 01x02	LED 2
J4		PinHeader 01x02	Button 1
J5		PinHeader 01x02	Buzzer 12V
J10		PinHeader 01x03	Duo LED
J11		Barrel_Jack_Switch
J12		PinHeader 01x08	RFID RC522
J13		PinHeader 01x02	Solenoid 12V
J14		PinHeader 01x02	jumper + jumper
P8		BeagleBone_Black_Header 23x02	(backside)
P9		BeagleBone_Black_Header 23x02	(backside)
Q1		STU60N3LH5
Q2		STU60N3LH5
R1		Ω LED1 
R2		pull_up
R3		220
R4		Ω LED2
R5		pull_up
R6		220
R7		100
R8		2k2
R14		Ω DuoLED
R15		Ω DuoLED
R16		100
R17		2k2
U1		TSR_1-2450
```



### Ω LED 1,2,DuoLED
```
color	  ohm
red   	100 
green 	 60 
yellow	 48 
blue  	  4
```
