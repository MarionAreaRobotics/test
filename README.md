Test
====
#include "joystickdriver.c"

motor[motorA] = 50;
motor[motorB] = 50 ? joy1Btn(5) : 0;