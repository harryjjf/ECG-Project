# ECG-Project
ECG project using AD8232 module with an Arduino UNO R3

## Hardware required  
Arduino UNO/NANO

AD8232 module

Electrode connector and 3 ECG electrodes 

5 Male-Female jumper wires 

## Software required 
Arduino IDE 

### Set up
1. Make connections as shown below:

![circuit](https://github.com/user-attachments/assets/9c8e4691-8c09-4159-bfcb-dca9dd0326ea)

| Arduino        | AD8232 Module |
| -------------  | ------------- |
| 3.3V           | 3.3V pin      |
| GND            | GND pin       |
| A1 Analogue In | Output pin    |
| Pin 10         | LO+           |
| Pin  11        | LO-           |

## Software setup
2. Download ECGcode.uno
3. Open in Arduino IDE and compile
4. Connect the Arduino to the computer and upload the file to Arduino

## Electrode connections

5. Stick electrodes to places on the chest as shown below, ensuring correct colours are in the right place. Then plug the electrode cable into the port on the AD8232 module. 

![placement](https://github.com/user-attachments/assets/2d3c5531-b6e8-4596-a882-436033a2bffa)

## Observing heart activity
After setup is complete, compile the code and send it to the Arduino. Open the serial plotter ( Tools -> Serial plotter) to observe the heart rate. An example is below. 


https://github.com/user-attachments/assets/512c15a8-4c2d-482d-a9a1-88fdd239623b


