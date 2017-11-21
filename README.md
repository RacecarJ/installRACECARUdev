# installRACECARUdev
Install the RACECAR Udev rules

This script installs the udev rule for the RACECAR.
The udev makes an alias named 'imu' for the Sparkfun 9DoF IMU.
The udev makes an alias named 'vesc' for the VESC (version < 6.0) electronic speed controller.
To install the rule:

$ ./installRACECARUdev.sh

The script attempts to reload the udev rules, but may require replugging of the IMU and VESC.

