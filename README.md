# Klipper configuration file for my Ender 3 v2 Voxelab Aquila with BLTouch

This is the current configuration for my machine, minus the machine specic items like bed mesh points and temperature PID. The 3d printer has an aluminum dual gear extruder and a BLTouch installed.

I followed [this reddit post](https://www.reddit.com/r/klippers/comments/kj2h5r/stepbystep_guide_for_ender_3_v2_klipper_w_bltouch/) to get [Klipper](https://www.klipper3d.org/) installed onto my Ender 3 v2 clone printer.

This is the current configuration for my machine, minus the machine specic items like bed mesh points and temperature PID.

## Note:
* Bed mesh speed turned up and the BLTouch sensor will travel with the probe extended. I am very impaitent and this helps speed it up.
* Some macros are included from web interface [Mainsail](https://docs.mainsail.xyz/).
* Tweaked the bed screw postions 


### Helpful Links (for me)
* [Klipper configuration file reference](https://www.klipper3d.org/Config_Reference.html)
* [Input shaper setup with the ADXL345](https://www.klipper3d.org/Measuring_Resonances.html)
  * Includes connection diagram to connect the [ADXL345](https://www.adafruit.com/product/1231) to the Raspberry Pi.
* [Adjusting bed leveling screws using probe](https://github.com/KevinOConnor/klipper/blob/master/docs/Manual_Level.md#adjusting-bed-leveling-screws-using-the-bed-probe)

