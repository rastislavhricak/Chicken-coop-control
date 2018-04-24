# Chicken-coop-control
chicken coop control system

## Features
- Menu based navigation system
- LCD backlight timer (off after 30sec, on with any button press)
- DS3231 RTC + 32k EEPROM
- Debounce buttons
- 

## MENU
The options below can be independently set.For example, you can have a Timed opening in the morning and then use the Light Sensor to close at night.

    - MANUAL  - This option is to halt the automatic opening or closing of the coop door. You would have to manually open or close the door by pressing either the UP or DOWN buttons – useful if you have ducks as they are not creatures of habit. For example, you would set a Timed opening in the morning and MANUAL for the evening allowing you to make sure they were in safely before manually closing the door.
    - TIME - This option is for automatic opening of the coop door in the morning, or automatic closing in the evening, at your set time/s.
    - LIGHTSENSOR - This option is for automatic opening of the coop door at dawn, or the automatic closing in the evening at dusk, using the Light Sensor.
### - LUX+ 
    - This setting uses a combination of both the Light Sensor and Timer. When selecting this option, you will be asked to set a default time. When this is set, the ChickenCoopControl will use the Light Sensor as its primary method to close, but, if it is not dark enough to close using the Light Sensor when the default time is reached, the door will then close based on the default time you set.
### - SUNSET-SUNRISE 
    - calculated from LONGITUDE & LATITUDE, TIMEZONE, DST,

## - THERMOSTAT
     DALLAS DS18B20 temperature sensor (In, Out)
   - relay module (250V/10A)
   ### - FEATURES
               * Set regulation temperature 5-55 °C
       * Save regulation temperature in EEPROM
     * Heat, Fan
   
## v0.1
* upravene MENU
* ovladanie tlacidlami analog << up, down, right, left, menu/ok >> DEBOUNCE ANALOG BUTTONS
+ pri starte kontroluje DS3231, v pripade nenajdenia hlasi chybu
  
