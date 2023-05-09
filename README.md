# Data-Acquisition-System-Telemetry
This project involves telemetry i.e transmission and reception of data from various sensors such as Battery Management System, Motor Control, Mass Flow Rate Sensor,Hall Effect Sensor etc to a remote computer using HC-12 module on UART serial communication protocol.

**HARDWARE AND COMPONENTS**

1.) Arduino UNO and Arduino MEGA 2560

![image](https://github.com/ayushjain143/Data-Acquisition-System-Telemetry/assets/73123555/0f06e3af-20a4-41c7-8d73-c9c606b114d0)
![image](https://github.com/ayushjain143/Data-Acquisition-System-Telemetry/assets/73123555/5469b42f-dd0f-4ecf-92c6-8708bc7571b0)

2.) Arduino IDE Software

3.) Male to Female Jumper Wires

![image](https://github.com/ayushjain143/Data-Acquisition-System-Telemetry/assets/73123555/6eec20c1-000f-4a33-bd56-82944140a900)

4.)2 HC-12 Communication Modules

![image](https://github.com/ayushjain143/Data-Acquisition-System-Telemetry/assets/73123555/05a95151-1ed3-4961-bf92-27adc7d1bead)

5.) Arduino USB Cable

![image](https://github.com/ayushjain143/Data-Acquisition-System-Telemetry/assets/73123555/97e8950f-8e31-4c38-9690-175021e1a20c)

**CONNECTIONS**
1. Connect the VCC pin of HC-12 module to 5V or 3.3 V of the Arduino board.
2. Connect the GND pin of HC-12 module to any of the GND port of the Arduino board to ensure common grounding.
3. Connect the RX pin to the digital pin 11 and the TX pin to the digital pin 10.
   ![image](https://github.com/ayushjain143/Data-Acquisition-System-Telemetry/assets/73123555/c0899c1b-8e35-4ae0-bdbc-20140044ea07)
4.) Power the Arduino Mega using LV(Low voltage) power supply from the power outlet whereas power the Arduino Uno using Arduino USB cable Type A to Type B.
5.) Open Arduino IDE software and choose appropriate Arduino Board and COM port to ensure correct serial values and uploading.

**MY ROLE**
I undertook this aspect of the Data Acquisition system where I published the Sender Code consisting of BMS,MFR,Motor Controller and Hall Effect Sensor data which is encapuslated and then sent in the form of a byte array.Also, I published the reciever code which decapsulates the data recieved on the HC-12 and then showcases it on the Serial Monitor.For this an important library needs to be installed :-https://downloads.arduino.cc/libraries/github.com/coryjfowler/mcp_can-1.5.0.zip







