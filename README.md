# Chicken-coop-control
chicken coop control system

## Features
- Menu based navigation system
- LCD backlight timer (off after 30sec, on with any button press)
- DS3231 RTC + 32k EEPROM
- Debounce buttons 

## MENU
Individual open and close mode:
- MANUAL (buttons)
- TIME - This option is for automatic opening of the coop door in the morning, or automatic closing in the evening, at your set time/s.
- LIGHTSENSOR - This option is for automatic opening of the coop door at dawn, or the automatic closing in the evening at dusk, using the Light Sensor.
- LUX+ - lightsensor + TIME
- SUNSET-SUNRISE - calculated from LONGITUDE & LATITUDE

## THERMOSTAT
   - DALLAS DS18B20 temperature sensor (In, Out)
   - relay module (250V/10A)
   - FEATURES
   - Set regulation temperature 5-55 °C
   - Save regulation temperature in EEPROM
   - Heat, Fan
   
## v0.1
* upravene MENU
* ovladanie tlacidlami analog << up, down, right, left, menu/ok >> DEBOUNCE ANALOG BUTTONS
+ pri starte kontroluje DS3231, v pripade nenajdenia hlasi chybu
  
