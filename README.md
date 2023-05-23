# ESP32 audio spectrum visualizer

## Hardware
 - ESP32 DevKitC v4 : [AliExpress link](https://fr.aliexpress.com/item/4000089201026.html)
 - WS2812B 16x16 led matrix : [AliExpress link](https://fr.aliexpress.com/item/4000544584524.html)
 - INMP441 I2S mic : [AliExpress link](https://fr.aliexpress.com/item/4000045570318.html)
 - AC-DC 5V 12A power supply : [AliExpress link](https://fr.aliexpress.com/item/32695830918.html)
 - 	Bourns PTV09A-4020U-B104 100k linear potentiometers : [Farnell link](https://fr.farnell.com/bourns/ptv09a-4020u-b104/potentiom-rotatif-100kohm-9mm/dp/2469526)

## Software
 - CP210x USB to UART Bridge VCP drivers : [https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers)
 - Arduino core for the ESP32 v2.0.9 : [Github](https://github.com/espressif/arduino-esp32/releases/tag/2.0.9)
 - FastLED library v3.5.0 : [Github](https://github.com/FastLED/FastLED/releases/tag/3.5.0)
 - ArduinoFFT library v1.6 : [Github](https://github.com/kosme/arduinoFFT/releases/tag/v1.6)

## Wiring diagram
![Wiring diagram](/Schematics/Wiring_diagram.png)

## To do
 - Fix flickering when low brightness
 - Add support of mode switch
 - Fix 3D designs
 - Add 3D parts in repo