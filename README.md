# Drapow-SK-25-OpenBK7231N



![Screenshot (4)](https://github.com/DRCRecoveryData/Drapow-SK-25-OpenBK7231/assets/85211068/fc4f9d75-6417-4be9-912e-1f6dcecddd3e)

![Screenshot (5)](https://github.com/DRCRecoveryData/Drapow-SK-25-OpenBK7231/assets/85211068/658e95b6-94c0-455e-a639-91b72da2b579)



Open-source firmware for Drapow SK-25 development board based on OpenBK7231N platform. Versatile, low power, and customizable.

## Wiring Connection

To upload the firmware to the Drapow SK-25 board using a CH341A programmer, make the following wiring connections:

| CH341A Programmer | Drapow SK-25 (OpenBK7231N) |
|-------------------|--------------------------|
| 3.3V               | 3.3V                     |
| GND               | GND                      |
| GND (Shorted during upload)                | CSN                      |
| TX               | RX                  |
| RX              | TX                   |

*Note: The CSN pin on the Drapow SK-25 should be shorted to GND during the upload process to ensure the correct operation.*
