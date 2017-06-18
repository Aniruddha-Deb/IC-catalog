# IC-catalog

1. [Timers, Oscillators and Counters](#Timers)
2. [Voltage Regulators](#VoltageRegulators)
3. [OpAmps and Amplifiers](#Amplifiers)
4. [Encoders](#Encoders)
5. [Decoders](#Decoders)
6. [Shift Registers](#ShiftRegisters)
6. [Tone](#Tone)
7. [Digital](#Digital)
8. [Display](#Display)
9. [Drivers](#Drivers)
10. [Microcontrollers](#Microcontrollers)

### <a name="Timers"></a>Timers, Oscillators and Counters
NAME     | QTY | PINS| DESCRIPTION              | DATASHEET                   | Pinout      
---------|-----|-----|--------------------------|-----------------------------|---------------
555      | 22  | 8   | Timer IC                 | [555](555/datasheet.pdf)    | 
4060     | 4   | 16  | Ripple binary counter    | [4060](4060/datasheet.pdf)  | 
4046     | 1   | 16  | Phase locked loop        | [4046](4046/datasheet.pdf)  | 
4029     | 1   | 16  | Decade/Binary counter    | [4029](4029/datasheet.pdf)  | 
4017     | 6   | 16  | decade counter           | [4017](4017/datasheet.pdf)  | [4017](4017/pinout.txt)


### <a name="VoltageRegulators"></a>Voltage Regulators
NAME     | QTY | PINS| DESCRIPTION              | DATASHEET                         
---------|-----|-----|--------------------------|-----------------------------------
7805     | 8   | 3   | 5v DC voltage regulator  | [78XX](78XX/datasheet.pdf)        
7809     | 4   | 3   | 9v DC voltage regulator  | [78XX](78XX/datasheet.pdf)        
7812     | 6   | 3   | 12v DC voltage regulator | [78XX](78XX/datasheet.pdf)        
7824     | 5   | 3   | 24v DC voltage regulator | [78XX](78XX/datasheet.pdf)        
80T54    | 1   | 12  | Multi voltage regulator  | [80T54](80T54/datasheet.pdf)      
34063    | 5   | 8   | buck regulator           | [34063](34063/datasheet.pdf)
3843     | 5   | 8   | switching mode regulator | [3843](3843/datasheet.pdf)

### <a name="Amplifiers"></a>OpAmps and Amplifiers
NAME     | QTY | PINS| DESCRIPTION              | DATASHEET                         
---------|-----|-----|--------------------------|-----------------------------------
TLO72CP  | 5   | 8   | General Purpose Op Amp   | [TLO72CP](TLO72CP/datasheet.pdf)  
TLC272CP | 1   | 8   | Rail to Rail Op Amps     | [TLC272](TLC272/datasheet.pdf)    
LM324    | 1   | 14  | Quad op amp              | [LM324](LM324/datasheet.pdf)
TLO84    | 5   | 14  | JFET quad op amp         | [TLO84](TLO84/datasheet.pdf)
741      | 5   | 8   | General Purpose op amp   | [UA741](UA741/datasheet.pdf)
386N     | 4   | 8   | Audio power amplifier    | [386N](386N/datasheet.pdf)
ULN2803  | 9   | 18  | Darlington array IC      | [ULN2803](ULN2803/datasheet.pdf)
380N     | 3   | 14  |2.5W audio power amplifier| [380N](380N/datasheet.pdf)
UPC1185H | 1   | 12  | 7W dual power amplifier  | [UPC1185H](UPC1185H/datasheet.pdf)

### <a name="Encoders"></a>Encoders
NAME     | QTY | PINS| DESCRIPTION              | DATASHEET                         
---------|-----|-----|--------------------------|-----------------------------------
74LS148  | 7   | 16  | 8 to 3 encoder           | [74148](74148/datasheet.pdf)      

### <a name="Decoders"></a>Decoders
NAME     | QTY | PINS| DESCRIPTION              | DATASHEET                         
---------|-----|-----|--------------------------|-----------------------------------
74LS154  | 2   | 24  | 4 to 16 decoder          | [74154](74154/datasheet.pdf)      
74LS47   | 2   | 16  | BCD to 7 segment decoder | [7447](7447/datasheet.pdf)        
4511 	 | 1   | 16  | BCD to 7 segment decoder | [4511](4511/datasheet.pdf)		
74LS139  | 2   | 16  | Dual 2 to 4 decoder      | [74139](74139/datasheet.pdf)      

### <a name="ShiftRegisters"></a>Shift Registers
NAME     | QTY | PINS| DESCRIPTION              | DATASHEET                        | Pinout    
---------|-----|-----|--------------------------|----------------------------------|------------------
74194    | 10  | 16  | 4 bit <-> shift register | [74194](74194/datasheet.pdf)     | 
74595    | 4   | 16  | 8 bit SIPO shift register| [74595](74595/datasheet.pdf)     | [74595](74595/pinout.txt)
74165    | 5   | 16  | 8 bit PISO shift register| [74165](74165/datasheet.pdf)     | [74165](74165/pinout.txt)

### <a name="Tone"></a>Tone
NAME     | QTY | PINS| DESCRIPTION              | DATASHEET                         
---------|-----|-----|--------------------------|-----------------------------------
BT66     | 4   | 3   | Music chip               | [BT66](BT66/datasheet.pdf) 
UM3561   | 4   | 8   | 3 sound siren generator  | [UM3561](3561/datasheet.pdf)     
G1       | 1   | 12  | Custom guitar circuit    | [G1](GuitarMusicChip/pinout.txt)

### <a name="Digital"></a>Digital
NAME     | QTY | PINS| DESCRIPTION              | DATASHEET                         
---------|-----|-----|--------------------------|-----------------------------------
4070     | 1   | 14  | Quad XOR gate            | [4070](4070/datasheet.pdf)
4049     | 1   | 16  | Hex inverting buffer     | [4049](4049/datasheet.pdf)        
4011     | 2   | 14  | Quad NAND gate           | [4011](4011/datasheet.pdf)        
4001     | 2   | 14  | Dual NOR gate            | [4001](4001/datasheet.pdf)
LM339N   | 1   | 14  | Quad comparator          | [LM339N](LM339N/datasheet.pdf)    
4013     | 1   | 14  | Dual flip flop           | [4013](4013/datasheet.pdf)
4066     | 18  | 14  | Quad SPST analog switch  | [4066](4066/datasheet.pdf)        
74LS24   | 5   | 20  | 3 state octal buffer     | [7424](7424/datasheet.pdf)
7404     | 5   | 14  | Hex inverter             | [7404](7404/datasheet.pdf)

### <a name="Display"></a>Display
NAME     | QTY | PINS| DESCRIPTION              | DATASHEET                         
---------|-----|-----|--------------------------|-----------------------------------
LM3915   | 5   | 18  | VU driver                | [LM3915](LM3915/datasheet.pdf)

### <a name="Drivers></a>Drivers
NAME     | QTY | PINS| DESCRIPTION              | DATASHEET                         
---------|-----|-----|--------------------------|-----------------------------------
L293D    | 5   | 16  | Stepper motor driver     | [L293D](L293D/datasheet.pdf)
IR2110   | 5   | 16  | MOSFET driver            | [IR2110](IR2110/datasheet.pdf)

### <a name="Microcontrollers"></a>Microcontrollers
NAME       | QTY | PINS| DESCRIPTION              | DATASHEET                         
-----------|-----|-----|--------------------------|-----------------------------------
PIC16F877A | 3   | 40  | PIC family large         | [PIC16F877A](PIC16F877A/datasheet.pdf)
ATMega16A  | 5   | 40  | Atmel family large       | [ATMega16A](ATMega16A/datasheet.pdf)
ATMega328  | 5   | 28  | Atmel family medium      | [ATMega328](ATMega328/datasheet.pdf)
PIC16F688  | 2   | 14  | PIC family small         | [PIC16F688](PIC16F688/datasheet.pdf)
PIC12F675  | 5   | 8   | PIC family micro         | [PIC12F675](PIC12F675/datasheet.pdf)



