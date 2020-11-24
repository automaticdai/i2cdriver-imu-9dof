# I2CDriver IMU

Use an I2CDriver and a 9-DoF IMU sensor to estimate oritention. I2CDriver allows I2C communication /monitoring from a PC using USB. The 9-DoF IMU sensor is using the following two chips:

- LSM303D: accelerometer and magnetometer
- L3GD20: gyroscope


## How to run

1. Connect I2CDriver to the IMU sensor (SCL, SDA, VCC, GND), and then I2CDriver to the PC thorugh usb.
2. Run `python3 main.py`


## Roadmap

- [ ] Read raw data from the IMU sensor
- [ ] Filter the data using Kalman
- [ ] Filter the data with Quest filter 
- [ ] Visualize the data with a 3D view
