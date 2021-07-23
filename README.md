# Klipper

These config files are for a CR-10s, MKS Gen L, and 3D/BLTouch setup. There are some specialized extruder settings required by my very own 25:1 gear ratio extruder. Due to the higher gear ratio, the extruder microsteps is set at 4. The first vase mode print at 120 mm/s is fantastic, and this is before I tried any other fancy tuning for Klipper.

- File printer.cfg-tmc2208-xy is for a setup with tmc2208 for x and y, and a4988 for z and e.
- FIle printer.cfg is for a setup with 4 tmc2130 for sensorless homing. This configuration needs further tuning.
