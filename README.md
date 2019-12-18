# NuLink2_Bus_Monitor
### connection
![img](../../../Nuvoton_Tools/blob/master/img/bus_monitor_connect.PNG)

### operation screen
![img](../../../Nuvoton_Tools/blob/master/img/bus_monitor_wsg.png)

### configuration
- SPI Bus Mode 0，Bit Length 8
- RS485 Bus Baud Rate 115200
- CAN Bus Baud Rate 500K

### input pins
- I2C (PIN 3, 4)
- SPI (PIN 5~8 – SS, CLK, MOSI, MISO)
- RS485 (PIN 9, 10)
- CAN (PIN 11, 12)
- GND (PIN 18, 20)
![](../../../Nuvoton_Tools/blob/master/img/bus_monitor_pins.png)

### output
I2C  
![](../../../Nuvoton_Tools/blob/master/img/i2c_monitor.png)  
SPI  
![](../../../Nuvoton_Tools/blob/master/img/spi_monitor.png)  
RS485  
![](../../../Nuvoton_Tools/blob/master/img/rs485_monitor.png)  
Data Only HEX (00-FF)  
CAN  
![](../../../Nuvoton_Tools/blob/master/img/can_monitor.png)  


Support CAN ID
STD (11 bit ID HEX, 0~7FF)
EXT (29 bit ID HEX)
DLC means Data length
DATA, HEX (0000 - FFFF)

