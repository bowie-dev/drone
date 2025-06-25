# Low-Cost FPV Drone
## Description:
A low-cost, first-person-view, remote controlled quadcopter using the Raspberry Pi Pico 2 W as the flight controller.
I am making this because I have an interest in and want to get into FPV drone flight.

## Files:
Bill of Materials (BOM) is /bom.csv<br>
CAD files are in /cad/.

## Design:
### Model:
![](https://github.com/bowie-dev/drone/blob/main/img/img1.png?raw=true)
![](https://raw.githubusercontent.com/bowie-dev/drone/refs/heads/main/img/mock.png)
### Wiring Diagram:
![image](https://github.com/user-attachments/assets/c9e5a3aa-a088-4dbe-876e-35efe6272844)

## BOM:
| Part                            | Model                     | Link                                                                                                                            | Cost (AUD) | Quantity | Shipping | Total   |
| ------------------------------- | ------------------------- | ------------------------------------------------------------------------------------------------------------------------------- | ---------- | -------- | -------- | ------- |
| Frame                           | N/A                       | N/A                                                                                                                             | $0.00      | 1        | $0.00    | $0.00   |
| Motors                          | iFlight XING E-PRO 2450kv | https://www.fpvfaster.com.au/collections/motor/products/iflight-xing-e-pro-2207-2-6s-fpv-nextgen-motor-1800kv-2750kv-for-nazgul | $21.50     | 4        | $6.70    | $92.70  |
| Battery                         | 1550mah 4S 14.8V 150C     | https://www.aliexpress.com/item/1005009176081771.html                                                                           | $34.99     | 1        | $0.00    | $34.99  |
| Speed Controller                | 30A ESC                   | https://www.aliexpress.com/item/1005008888942406.html                                                                           | $7.24      | 1        | $0.00    | $7.24   |
| Flight Controller               | Raspberry Pi Pico 2 W     | https://raspberry.piaustralia.com.au/products/raspberry-pi-pico-2w                                                              | $12.83     | 1        | $0.00    | $12.83  |
| Sensor IMU                      | 10DOF GY87 Sensor         | https://raspberry.piaustralia.com.au/products/10dof-module-mpu6050-hmc5883l-bmp180-gy87-sensor-module                           | $16.10     | 1        | $9.50    | $25.60  |
| Camera + Transmitter + Reciever | N/A                       | https://www.aliexpress.com/item/1005001462162015.html                                                                           | $88.06     | 1        | $25.24   | $113.30 |
| Controller + Reciever           | FS-i6X + FS-iA6B          | https://www.amazon.com.au/Mingzhe-Transmitter-Receiver-Airplane-Helicopter/dp/B0CND6YBWM                                        | $103.19    | 1        |          | $103.19 |
| Voltage Regulator               | LM7805                    | https://core-electronics.com.au/lm7805-5v-voltage-regulator.html                                                                | $0.92      | 1        | $0.00    | $0.92   |
| Jumper Wire                     | N/A                       | https://core-electronics.com.au/jumper-wire-20cm-ribbon-of-40pcs.html                                                           | $3.95      | 1        | $0.00    | $3.95   |
| Power Switch                    | N/A                       | https://www.jaycar.com.au/sub-miniature-dpdt-panel-mount-switch-slide-style/p/SS0852                                            | $1.65      | 1        |          | $1.65   |
| Servo Motor                     | FS90R                     | https://core-electronics.com.au/feetech-1-5kg-continuous-rotation-servo-fs90r.html                                              | $5.60      | 1        | $7.99    | $13.59  |
| Capacitor 100uf                 | 100uf 25vdc               | https://www.jaycar.com.au/100uf-25vdc-low-esr-electrolytic-capacitor/p/RE6322                                                   | $0.50      | 1        |          | $0.50   |
| Capacitor 10uf                  | 10uf 25vdc                | https://www.jaycar.com.au/10uf-25vdc-electrolytic-rb-capacitor/p/RE6070                                                         | $0.35      | 1        |          | $0.35   |
| Resistor 1.8k                   | 8 Pack 1.8k               | https://www.jaycar.com.au/1-8k-ohm-0-5-watt-metal-film-resistors-pack-of-8/p/RR0578                                             | $0.85      | 1        |          | $0.85   |
| Resistor 2.2k                   | 8 Pack 2.2k               | https://www.jaycar.com.au/2-2k-ohm-0-5-watt-metal-film-resistors-pack-of-8/p/RR0580                                             | $0.85      | 1        |          | $0.85   |
| Resistor 3.3k                   | 8 Pack 3.3k               | https://www.jaycar.com.au/3-3k-ohm-0-5-watt-metal-film-resistors-pack-of-8/p/RR0584                                             | $0.85      | 1        |          | $0.85   |
| Resistor 6.8k                   | 8 Pack 6.8k               | https://www.jaycar.com.au/6-8k-ohm-0-5-watt-metal-film-resistors-pack-of-8/p/RR0592                                             | $0.85      | 1        |          | $0.85   |
| Resistor 10k                    | 8 Pack 10k                | https://www.jaycar.com.au/10k-ohm-0-5-watt-metal-film-resistors-pack-of-8/p/RR0596                                              | $0.85      | 1        |          | $0.85   |
| Propellors                      | 5" Propellor x4           | https://www.aliexpress.com/item/1005009127160332.html                                                                           | $3.10      | 1        |          | $3.10   |
| Charger                         | LiPo Balance Charger      | https://www.aliexpress.com/item/32932740630.html                                                                                | $13.54     | 1        |          | $13.54  |
| AUD TOTAL                       |                           |                                                                                                                                 |            |          |          | $431.70 |
| USD TOTAL                       |                           |                                                                                                                                 |            |          |          | $280.45 |
