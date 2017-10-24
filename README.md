The animation displays the growing and shrinking of the Unyte logo in 13 frames (including 2 blank frames).

The main.cpp program runs in the ARM mbed operating system version#5

The default frame time is 0.2 seconds. To adjust the frame time, go to line 615 in main.cpp.
The default communication protocol is I2C. To run the program under SPI communication protocol, change line 16 of main.cpp to SPI spi_oled(SPI0_MOSI,NC,SPI0_SCK); change line 18 of main.cpp to Adafruit_SSD1306_Spi oled(spi_oled,P2_7,P2_6,SPI0_SS);
