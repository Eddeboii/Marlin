# Things to doublecheck:
## Started:
- DEFAULT_AXIS_STEPS_PER_UNIT: Standard values are { 80, 80, 400, 500 }
  - X-axis: OK
  - Y-axis: OK
  - Z-axis: OK
  - E-axis: OK
- X-axis and Y-axis are not centering in the middle of the bed.
- Solder hotend fan cables

## To come:
- CLASSIC_JERK: Was used in previous version I think
- PROBING_MARGIN: Previusly used 0, why?
- PREHEAT_1_FAN_SPEED: Idk what pwm my PLA wants.
- ENCODER_PULSES_PER_STEP: Was enabled before, but idk what it is.
- BLTOUCH: In advanced, seems like something I should use.
- Gamla ENCODER_10X_STEPS_PER_SEC   75 -> 30
  Gamla ENCODER_100X_STEPS_PER_SEC  160 -> 80