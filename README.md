# ESP8266_aREST 

## Usage
1. Example uses internal LED of your ESP8266 board (D1, pin1, 1)
2. Open the sketch and modify the WiFi SSID & password
3. Upload the sketch
4. Open the Serial monitor to get the IP address of the board, for example 192.168.2.2
5. Go to a web browser and type `192.168.2.2/mode/1/o` to set the pin as an output
6. Now type `192.168.2.2/digital/1/1` and the LED should turn OFF
7. Now type `192.168.2.2/digital/1/0` and the LED should turn ON
