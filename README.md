--------------MPU9250--------------

If you are using I2C communication in the MPU9250 file, everything works fine. I also added an angle calculation section. 
If you are using SPI communication, I haven't finished the magnetic section yet.

Note: Since the magnetic sensor is affected even by the NUCLEO/DISCOVERY Board, I recommend using the MPU9250 module away from all electronic devices. Otherwise, distortions will occur in the Z-axis calculation. (The Z-axis is calculated using only magnetic field data.)
