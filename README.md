# Lora Shield v1.4 - Arduino Mega
###### Author: Jaime Andrés Gómez Gutiérrez | Caldas University
###### Subject: Networks III

## Features 
> Encrypted comunication, 
> Warning alarm, 
> Node server, 
> Node client: Grove-Moisture-Sensor and Accelerometer

Features:

Frequency band: 868 MHZ
Low energy consumption
Compatible with Arduino Leonardo, Uno, Mega, DUE
External antenna through the I-Pex connector
 

Specifications:

Communication link of 168dB maximum.
+20 dBm - 100 mW of constant RF power vs. +14 dBm high efficiency PA.
Programmable speed of up to 300 kbps.
High sensitivity: up to -148 dBm.
Low receive current of 10.3 mA, 200 nA in sleep mode.
Fully integrated synthesizer with a resolution of 61 Hz.
Modulation FSK, GFSK, MSK, GMSK, LoRa ™ and OOK.
Built-in bit synchronizer for clock recovery.
Preamble detection.
Dynamic range of 127 dB RSSI.
Automatic RF sensor and CAD with ultra fast AFC.
Packet engine up to 256 bytes with CRC.
Built-in temperature sensor and low battery indicator.

![alt text](http://i66.tinypic.com/33c3lhv.jpg "Testing bidirectional comunication")

### Output send data to server encrypted

![alt text](http://i66.tinypic.com/vn2knb.png "Output testing bidirectional comunication")


### Output testing bidirectional comunication without encrypted

![alt text](http://i63.tinypic.com/11v1ehh.png  "Output testing bidirectional comunication")




### Accelerometer

![alt text](http://i66.tinypic.com/r2ojeg.jpg  "Connect accelerometer to arduino mega 2560 ")



### Grove-Moisture-Sensor

![alt text](http://i63.tinypic.com/25h2z6c.jpg "Connect grove miosture sensor to arduino")


####   Here are suggested for this sensor values:
| *Min*   | *Typ*   | *Max*   | *Condition*             |
| --------|:-------:| -------:| -------------           |
| 0       | 0       | 0       | sensor in open air      |
| 0       | 20      | 300     | sensor in dry soil      |
| 300     | 580     | 700     | sensor in humid soil    |
| 700     | 940     | 950     | sensor in water         |

### Accelerometer and moisture sensor together over Lora Shield v1.4 - Arduino Mega

![alt text](http://i68.tinypic.com/ixfc74.jpg "Accelerometer and moisture sensor together over Lora Shield v1.4 - Arduino Mega 2560 ")


### Output accelerometer and moisture sensor together 

![alt text](http://i68.tinypic.com/9s48bn.png "Output later connect moisture sensor and accelerometer to arduino mega 2560 ")

## Tests field

#### Moisture test

![alt text](http://i64.tinypic.com/105v8fk.jpg "Test moisture")


![alt text](http://i68.tinypic.com/2nqbh4o.png "Test moisture")


#### Accelerometer test



![alt text](http://i67.tinypic.com/10574ud.jpg  "Accelerometer moisture")

![alt text](http://i68.tinypic.com/fbdj0g.png  "Accelerometer moisture")


#### Video test
https://youtu.be/CISP1jIE9hM





## Interesting links

1. [wiki.dragino.com](https://wiki.dragino.com/index.php?title=Lora_Shield)
2. [Grove-Moisture-Sensor](http://wiki.seeedstudio.com/Grove-Moisture_Sensor)
3. [Examples Lora - Arduino](https://github.com/dragino/Lora/tree/master/Lora%20Shield)
4. [Video connect accelerometer](https://www.youtube.com/watch?v=_przDICw1-Q)
5. [Accelerometer Arduino Code](https://hetpro-store.com/TUTORIALES/mma7361-sensor-acelerometro/)
6. [Building a global open LoRaWAN™ network](https://www.thethingsnetwork.org/)









