# Marlin-Creality-Ender3-v1-BLTouch
Marlin Creality Ender3 v1 BLTouch for mother board v1.1.4


> Marlin 2.0.9.8
> Marlin Configurations 2.0.9.8


## Adding BL Touch

```
// to uncomment
#define BLTOUCH

// Define personal values
#define NOZZLE_TO_PROBE_OFFSET { -42, -5, 0 }

// Increase PROBING_MARGIN from 10 to 20
#define PROBING_MARGIN 20

// MULTIPLE_PROBING 2 uncomment
#define MULTIPLE_PROBING 2

// to comment
MIN_SOFTWARE_ENDSTOP_Z

// To set to true => Firmware 2.0.9.8 want it to be false
#define Z_MIN_PROBE_ENDSTOP_INVERTING true

// To uncomment
#define AUTO_BED_LEVELING_BILINEAR

// Autoleveling number of correction points
GRID_MAX_POINTS_X 3

// To uncomment
EXTRAPOLATE_BEYOND_GRID

// To uncomment
#define Z_SAFE_HOMING

```

Fixing Y 0 offset

Configuration.h
```
#define Y_MIN_POS -8
```
