The Zodiark-V2 is a remake of the original Zodiark, using the save general footprint, but adding advanced features over the original:
    * MX and Choc hotswap sockets
    * Underglow LEDs
    * Full support for VIK with the 35 Pin AliExpress RP2040 Pro Micros: [Tested RP2040 Pro Micro here](https://www.aliexpress.us/item/3256806413474305.html?spm=a2g0o.order_list.order_list_main.88.12691802UXk6Ew&gatewayAdapt=glo2usa)
    * Dual Axis Encoder (35 Pin RP2040 Pro Micro/Nice!Nano/SuperMini)
    * Battery connector and Power Switch for Nice!Nano/SuperMini
    * Works with Original Zodiark Firmware when using a standard Pro-Micro (Untested)

| Microcontroller          | VIK                         | Dual Axis Encoder  |
| ------------------------ | --------------------------- | ------------------ |
| RP2040 35 Pin Pro Micro  | :heavy_check_mark:          | :heavy_check_mark: |
| Nice!Nano - SuperMini    | :x: I2C Only (no GPIO/SPI)  | :heavy_check_mark: |
| AVR Pro Micro            | :x: I2C Only (no GPIO/SPI)  | :x:                |
| Other Pro Micro clones   | :x: I2C Only (no GPIO/SPI)  | :x:                |

Currently Nice!Nano/SuperMini firmware and support has not been tested, in progress.