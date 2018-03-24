KeDei 6.3 SPI TFT Display Test Program

2018 Ch. Kranz 
- Small Demo Program to show figures and colors on the LC-Display V6.3

-![RPI KeDei 6.3 Display](/kedei_63_work.jpg)
-![KeDei 6.3 Display Butt](/kedei_butt.jpg)

- based on FreeWing's code
    https://github.com/FREEWING-JP/RaspberryPi_KeDei_35_lcd_v50
  and Tong Zhang's code
    https://github.com/lzto/RaspberryPi_KeDei_35_lcd_v62

- added V6.3 init sequence and rotating sequence
- added many improvements for bmp figures handling

- circut:

You need 7 wires to make kedei 6.2 display work!(not including touch panel)

* VCC - 5v
* GND
* MOSI
* MISO
* SCLK
* L\_CS - Chip select for TFT display (of course!)
* T\_CS - Chip select for xpt2046, you need this in order to make display work!
nasty 🤢
manually yank this line(pull low) when finish sending data through SPI



