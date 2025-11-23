Reading absolute angle using AS5600 and STM32 B-G431_ESC-1

This project uses Hardware Abstraction Layer (HAL) for STM32. You'll need STM32CubeIDE installed for this project.

1. Create a new STM32 project


2. Configure I2C for your corresponding STM32. For my B-G431-ESC1, it is PB7 and PB8 as SDA and SCL correspondingly 
![alt text](B-G431B-ESC1_I2CPorts.png)


3. Click Save and generate code.


4. compare main.c in repo and include missing part into the generated main.c code