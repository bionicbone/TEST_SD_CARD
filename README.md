# TEST_SD_CARD
LOLIN32 ESP32 with Adafruit 5v SD Card

This appears to be working, but more testing required.
The Adafruit 5v SD Card Breakout must be powered by 5v (I used a NANO powered by USB just to get thh 5v & GND pins in this test)

For the LOLIN32 connections,
  GPIO19 to D0,
  GPIO23 to D1,
  GPIO18 to CLK,
  GPIO5 to CS,
  
  Although I had success connecting the cheaper SD Card breakouts I have using a NANO I read that the CS pin is always GND on these
  and therefore would take full control over the SPI bus.
  
  My project will required up to 4 SPI slaves and therefore the cheap ones were not tested. 
