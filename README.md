# dual_rail_power_supply

Dual rail DC power supply capable of delivering positive or negative 3.3V/5V/9V/12V/15V, 1A or unregulated 24V. Banana plugs on the right supply positive voltage and the ones on the left supply negative voltage. 
They share a common ground.

## Features
- 6 position selection knob
- positive/negative 3.3V/5V/9V/12V/15V
- maximum supply current of 1.5A
- load regulation <100mV
- input voltage of 230VAC

## Hardware requirements
- LM317 3-terminal adjustable regulator
- LM337 3-terminal adjustable negative regulator
- 230V/2x15V, 1A, 30VA transformer
- 4 3300uF, 35V capacitors
- 2 10uF, 50V capacitors
- 2 1uF, 50V capacitors
- 6 4k7 resistors
- full bridge rectifier
- 4 5k trimmer resistors
- 2 2k trimmer resistors
- 4 1k trimmer resistors
- 2 220R resistors
- 4 1N4007 diodes
- 3 pin screw terminal
- 1A fuse
- 6 position rotary switch
- banana plugs
- miscellaneous

## Wiring and schematics
### Board schematic
![dual_rail_power_supply](https://github.com/user-attachments/assets/72396879-b8f1-4e9a-ac8c-2d40bc316ee0) <br><br>

## Troubleshooting
**Problem:** Negative voltage drops under load <br>
**Solution:** Fake/knock off LM337 voltage regulator, replace with a genuine one

## Usage
### Front side
![front](https://github.com/user-attachments/assets/38817c05-310c-4ecb-990f-10b74d49918a)

### Back side
![back](https://github.com/user-attachments/assets/e6bc6e73-cf34-4ea5-93a9-bd5b19153cfc)

### Internals
![internals](https://github.com/user-attachments/assets/04c096a7-7d34-4858-b938-d29e984c5842) <br><br>

**Knob positions:** <br>
1st position - 3.3V <br>
2nd position - 5V <br>
3rd position - 9V <br>
4th position - 12V <br>
5th position - 15V <br>
6th position - rectified unregulated voltage, around 24V <br>

## Measurements
### 3.3V
![3v3](https://github.com/user-attachments/assets/ac3ea6f9-8759-431c-86a3-2de45f4c9376)

### 5V
![5v](https://github.com/user-attachments/assets/e658c0e2-6131-45ad-adc9-24d5a72e72d0)

### 9V
![9v](https://github.com/user-attachments/assets/d7846ea5-f626-49a8-92ac-7d35f545d6a9)

### 12V
![12v](https://github.com/user-attachments/assets/2996dac0-f678-4bc2-b09c-6b95888d5b61)



### 15V
![15v](https://github.com/user-attachments/assets/e3ca93c0-4cf3-4bf4-b957-d56185cff292)

### 24V
![24v](https://github.com/user-attachments/assets/0f5d545e-dfbd-4065-95a0-0c13ca437e04)
