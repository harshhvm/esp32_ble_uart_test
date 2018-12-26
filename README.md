# ESP32 BLE on Arduino IDE with UART Test 
ESP32 BLE on Arduino IDE with UART Test. you can control a LED bulb through BLE.

You need to have the ESP32 add-on installed on the Arduino IDE. Visit this 
Article http://iotbyhvm.ooo/arduino-esp32-support-on-windows-and-ubuntu/ 

Pin Diagram

Now Connect a LED bulb with PIN 25.
Positive +   ======> PIN 25
Negative –   ======> GND

Now Install BLE Scanner Android App (Link given above) and connect with ESP32 UART Test and click on RX UUID.

Here Type ON for Turn On LED and Type OFF for Turn Off LED.

Remember :

The service advertises itself as: 6E400001-B5A3-F393-E0A9-E50E24DCCA9E

Has a characteristic of: 6E400002-B5A3-F393-E0A9-E50E24DCCA9E – used to send data with  “write”
Download BLE Scanner App https://play.google.com/store/apps/details?id=com.macdom.ble.blescanner&hl=en_IN

Or use nRF Connect for Mobile App

https://play.google.com/store/apps/details?id=no.nordicsemi.android.mcp&hl=en_IN
