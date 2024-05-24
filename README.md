
# RFID Based Attendance System using ESP8266
 
Utilizing IoT devices like NodeMCU, the system connects RFID readers to the internet, enabling data transmission to servers or cloud platforms. Upon scanning RFID tags, the system captures attendance data, processes it in real-time, and stores it securely in databases or spreadsheets.

## Flowchart
![RFID Based Attendance System (WiFi ESP8266)](https://www.ijraset.com/images/text_version_uploads/imag%201_25513.png)

![RFID Based Attendance System (WiFi ESP8266)](https://i.ytimg.com/vi/xeHBKi0GLow/maxresdefault.jpg)

## HardWare Used:

## NodeMCU(ESP8266)
![](https://www.ijraset.com/images/text_version_uploads/imag%201_25514.png)
NodeMCU is an open-source Lua based firmware and development board specially targeted for IoT based Applications. It includes firmware that runs on the ESP8266 Wi-Fi SoC from Espressif Systems, and hardware which is based on the ESP-12 module.

## NodeMCU(ESP8266)
![](https://www.ijraset.com/images/text_version_uploads/imag%201_25517.png)
The RC522 RFID module based on the MFRC522 IC from NXP is one of the cheapest RFID options you can get. It usually comes with an RFID card tag and a key fob tag with 1KB of memory. And the best part is that it can write a tag that means you can store any message in it.

## Connections:

![](https://www.ijraset.com/images/text_version_uploads/imag%201_25519.png)

The pinout is as follows (left side RC522, right side ESP8266):

Vcc <-> 3V3 (or Vin(5V) depending on the module version)

RST (Reset) <-> D3

GND (Ground) <-> GND

MISO (Master Input Slave Output) <-> D6

MOSI (Master Output Slave Input) <-> D7

SCK (Serial Clock) <-> D5

SS/SDA (Slave select) <-> D4



