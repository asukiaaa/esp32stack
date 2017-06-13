# ESP32Stack
A kicad project of stacking board with using ESP-WROOM-32.

![ESP32Stack](docs/esp32stack.jpg)
![ESP32Stack side](docs/esp32stack_side.jpg)
![ESP32Stack size](docs/esp32stack_size.png)

In combination with [EmptyStack](https://github.com/asukiaaa/emptystack).
![Stacks](docs/stacks.jpg)

[schema](docs/esp32stack.pdf)

# Driver
This board uses CP2102 for serial communication.
For mac and windiws user, please install the following driver.
Linux supports cp2102 defaul, so linux user does not need any driver.

[CP210x USB to UART Bridge VCP Drivers](http://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers)

# Shop
[trial stacks](https://trialstacks.base.ec/items/6243777)

# Components
- [esp-wroop-32](http://akizukidenshi.com/catalog/g/gM-11647/)
- [Hirose-microB-USB](http://akizukidenshi.com/catalog/g/gC-05254/)
- [Diode](http://akizukidenshi.com/catalog/g/gI-05951/)
- [transistor MMBT3904](http://akizukidenshi.com/catalog/g/gI-05969/)
- [switch SKRPACE010](http://akizukidenshi.com/catalog/g/gP-06185/)
- [100uf 1206 condensor](http://akizukidenshi.com/catalog/g/gP-08260/)
- [10uf 0603 condensor](http://akizukidenshi.com/catalog/g/gP-07768/)
- [0.1uf 0603 condensor](http://akizukidenshi.com/catalog/g/gP-04940/)
- [1nf (1000pf) 0603 condensor](http://akizukidenshi.com/catalog/g/gP-09285/)
- [10k 0603 registor](http://akizukidenshi.com/catalog/g/gR-06103/)
- [led](http://akizukidenshi.com/catalog/g/gI-06417/)
- [CP2102](https://www.aliexpress.com/item/5pcs-Free-shipping-SILABS-CP2102-GMR-CP2102-QFN-28-offen-use-laptop-chip-100-new-original/32503317767.html?spm=2114.13010608.0.0.PUEIRm)
- [NCP1117ST33T3G](https://www.aliexpress.com/item/Free-Shipping-NCP1117ST33T3G-NCP1117-3-3V-linear-regulator-SOT-223-package/32244660148.html?spm=2114.13010608.0.0.PUEIRm)

# Footprints
- [ESP32-kiCAD-Footprints](https://github.com/adamjvr/ESP32-kiCAD-Footprints)
- [switch: SKRPACE010.kicad_mod](https://github.com/nosuz/kicad-lib/blob/master/module.pretty/SKRPACE010.kicad_mod)

# Programing software tools
ESP32Stack is a ESP-WROOM-32 breakout board so you can write your own program by usinig the following tools.

- [espressif/esp-idf](https://github.com/espressif/esp-idf)
- [espressif/arduino-esp32](https://github.com/espressif/arduino-esp32)
- [Mongoose OS](https://mongoose-os.com/)
- etc

# License
MIT

# References
- [ESP32-Core-Board-V2_sch.pdf](http://akizukidenshi.com/download/ds/espressifsystems/ESP32-Core-Board-V2_sch.pdf)
- [esp_wroom_32_datasheet_en.pdf](https://espressif.com/sites/default/files/documentation/esp_wroom_32_datasheet_en.pdf)
- [Enginursday: First Impressions of the ESP32](https://www.sparkfun.com/news/2017)
- [ESP32 Development Board with TELEC Memorial photograph](https://macsbug.wordpress.com/2016/12/12/esp32-development-board-with-telec-memorial-photograph/)
- [DS_FT232R](http://www.ftdichip.com/Support/Documents/DataSheets/ICs/DS_FT232R.pdf)
- [SparkFun FTDI Basic Breakout - 3.3V](https://www.sparkfun.com/products/9873)
- [Sehematic of SparkFun FTDI Basic Breakout - 3.3V](http://cdn.sparkfun.com/datasheets/BreakoutBoards/FTDI%20Basic-v22-3.3V.pdf)
- [esp32-thing.sch](https://cdn.sparkfun.com/assets/learn_tutorials/5/0/7/esp32-thing-schematic.pdf)
- [The Internet of Things with ESP32](http://esp32.net/)
- [ESP-WROVER-KIT_SCH-2.pdf](https://dl.espressif.com/dl/schematics/ESP-WROVER-KIT_SCH-2.pdf)
- [ESP32-EVB_Rev_A.pdf](https://github.com/OLIMEX/ESP32-EVB/blob/master/HARDWARE/REV-A/ESP32-EVB_Rev_A.pdf)
