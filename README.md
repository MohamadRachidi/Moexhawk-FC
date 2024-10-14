# 📢 **MOEXHAWK**
The **MOEXHAWK V1.0.2 Baseboard** is a versatile single-board platform that combines a swappable Pixhawk flight controller and the Raspberry Pi CM4 companion computer. This baseboard offers a compact design, integrating all essential development connections in one place. It facilitates a smooth experience for developers needing an efficient and integrated solution for UAV or robotics projects.

It follows the [Pixhawk Connector](https://github.com/pixhawk/Pixhawk-Standards/blob/master/DS-009%20Pixhawk%20Connector%20Standard.pdf) and [Autopilot Bus Standard](https://github.com/pixhawk/Pixhawk-Standards/blob/master/DS-010%20Pixhawk%20Autopilot%20Bus%20Standard.pdf), allowing easy swap of FC Module with any FC that follows the Pixhawk Bus Standard.

![image](https://github.com/user-attachments/assets/62828502-ffd1-4036-b971-44623e944b1c)

# 🔶 **Features**
| Feature       | Details                                 |
|---------------|-----------------------------------------|
| **CPU**       | Allwinner H616/H618 Quad-Core 1.5GHz    |
| **RAM**       | 1GB/2GB/4GB LPDDR4                      |
| **Storage**   | 8GB eMMC5.1                             |
| **WIFI+BT**   | WIFI/BT5.0                              |
| **Ethernet**  | 10M/100M                                |
| **OS**        | Ubuntu 22.04                            |

# Pinouts

### I2C Pinout

| **Pin**    | **Signal**   | **Voltage**           |
|------------|--------------|-----------------------|
| 1 (red)    | VCC          | +5V                   |
| 2 (blk)    | SCL          | +3.3V (pullups)       |
| 3 (blk)    | SDA          | +3.3V (pullups)       |
| 4 (blk)    | GND          | GND                   |

### CAN2 Pinout

| **Pin**    | **Signal**   | **Voltage**           |
|------------|--------------|-----------------------|
| 1 (red)    | VCC          | +5V                   |
| 2 (blk)    | CAN_H        | +12V                  |
| 3 (blk)    | CAN_L        | +12V                  |
| 4 (blk)    | GND          | GND                   |

### POWER1 Pinout

| **Pin**    | **Signal**        | **Voltage**       |
|------------|-------------------|-------------------|
| 1 (red)    | VCC               | +5V               |
| 2 (red)    | VCC               | +5V               |
| 3 (blk)    | CURRENT sensing   | +3.3V             |
| 4 (blk)    | VOLTAGE sensing   | +3.3V             |
| 5 (blk)    | GND               | GND               |
| 6 (blk)    | GND               | GND               |

### USB Pinout

| **Pin**    | **Signal**        | **Voltage**       |
|------------|-------------------|-------------------|
| 1 (red)    | VCC               | +5V               |
| 2 (blk)    | OTG_DP1           | +3.3V             |
| 3 (blk)    | OTG_DM1           | +3.3V             |
| 4 (blk)    | GND               | GND               |
| 5 (blk)    | BUZZER            | Battery voltage   |
| 6 (blk)    | FMU Error LED     |                   |

### TELEM1 Pinout

| **Pin**    | **Signal**        | **Voltage**       |
|------------|-------------------|-------------------|
| 1 (red)    | VCC               | +5V               |
| 2 (blk)    | TX (OUT)          | +3.3V to 5V       |
| 3 (blk)    | RX (IN)           | +3.3V to 5V       |
| 4 (blk)    | CTS (OUT)         | +3.3V to 5V       |
| 5 (blk)    | RTS (IN)          | +3.3V to 5V       |
| 6 (blk)    | GND               | GND               |

