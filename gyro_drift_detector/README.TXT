Author: Naomi Carvalho
Date: Dec 13, 2019

This is a gyro drift detector myblock for the EV3.
It is intended for FLL tournaments to put at the beginning of a run.

If there is no gyro drift the bot will flash for 2 secs and then continue with the run.
If there is drift, the bot will flash red and stop moving. Wait for 2 secs, then check the value on the ev3 screen (This is the gyro value casted from the myblock). If it is actually drifting, UNPLUG the gyro cable and plug it back in, as many times as neccessary to stop drift (Usually, just once is needed).

MANUAL OVERRIDE: If the bot stops but the gyro is not drifting, override by pressing the left button.

NOTE: Be sure to keep the alignment of the bot correct when unplugging the gyro because the bot will continue with the run once the gyro drift has stopped.

