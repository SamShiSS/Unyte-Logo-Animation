This repository creates animation of the Unyte logo on an OLED screen, under I2C connection. The animation displays the growing and shrinking of the Unyte logo in 13 frames (including 2 blank frames). To change the frame time, go to line 634 of main.cpp.

To run it under SPI connection, change line 16 of main.cpp to SPI spi_oled(SPI0_MOSI,NC,SPI0_SCK); change line 18 of main.cpp to Adafruit_SSD1306_Spi oled(spi_oled,P2_7,P2_6,SPI0_SS);
