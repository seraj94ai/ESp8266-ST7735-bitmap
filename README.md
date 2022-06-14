# ESp8266-ST7735-bitmap
https://youtu.be/iLHKOl83lfo<br/>
In this video I explain how to connect an ST7735 LCD with esp8266 and use Adafruit GFX library to draw bitmap image without using SD card just using flash memory .
Converting Images to Flash Memory  for TFT (without SD Card)
---------------------------------------------------
The Pin Connection:
| LCD  |  ESP8266 |
| ------------- | ------------- |
| VCC  |  3.3V  |
| GND  |  GND  |
| Reset  |  3.3v  |
| A0 or D/C  |  D4  |
| SDA (MOSI)  |  D7  |
| SCK  |  D5  |
| LED  |  3.3V  |

               
                
                  
Image Resizer : http://www.faststone.org/FSResizerDownload.htm<br/>
LCD image Converter : https://sourceforge.net/projects/lcd-image-converter/   <br/>        
           
           
                  
                
---------------------------------------------------
To works with the Adafruit 1.8" TFT  you need this  libraries :
Adafruit GFX library: https://github.com/adafruit/Adafruit-GFX-Library
St7735 LCD library: https://github.com/adafruit/Adafruit-ST7735-Library

![alt text](https://github.com/seraj94ai/ESp8266-ST7735-bitmap/blob/main/tft_Moment.jpg)
