---
hide:
  - navigation
---
# Documentation


## RP2040

RP2040 is the debut microcontroller from Raspberry Pi. It offers high performance, low cost, and ease of use to the microcontroller space. With a large on-chip memory, symmetric dual-core processor complex, deterministic bus fabric, and rich peripheral set augmented with unique Programmable I/O (PIO) subsystem.RP2040 is manufactured on a modern 40nm process node, delivering high performance, low dynamic power consumption, and low leakage, with a variety of low-power modes to support extended-duration operation on battery power.

### Key features of RP2040

- Dual ARM Cortex-M0+ @ 133MHz, 264kB on-chip SRAM in six independent banks
- Support for up to 16MB of off-chip Flash memory via dedicated QSPI bus & DMA controller
- Interpolator and integer divider peripherals
- On-chip programmable LDO to generate core voltage & 2 on-chip PLLs to generate USB and core clocks
- 30 GPIO pins, 4 of which can be used as analogue inputs
- Peripherals like 2 UART's, 2 SPI controller's, 2 I2C controller's,16 PWM channel's and 8 PIO state machines
  
![RP2040](https://assets.raspberrypi.com/static/chips-a126ba53c50bb160d65210696edf8ad9.png)

To View the Datasheet click ->  [DATASHEET](https://datasheets.raspberrypi.com/rp2040/rp2040-datasheet.pdf).

---

## List of different boards which used RP2040

- RASPBERRY PI PICO
- ARDUINO NANO RP2040
- ARDUINO RP2040-ZERO
- SPARKFUN MICRO MOD PI RP2040
- ADFRUIT FEATHER RP2040
- ADIY FLY RP2040
- CYTRON MAKER PI RP2040
- WIO RP2040
  


### 1) RASPBERRY PI PICO

Raspberry Pi Pico has been designed to be a low cost yet flexible development platform for RP2040

key features:

- RP2040 microcontroller with 2MB Flash
- Micro-USB B port for power and data (and for reprogramming the Flash)
- 40 pin 21×51 'DIP' style 1mm thick PCB with 0.1" through-hole pins also with edge castellations
- Exposes 26 multi-function 3.3V General Purpose I/O (GPIO)
- 23 GPIO are digital-only and 3 are ADC capable
- Can be surface mounted as a module
- 3-pin ARM Serial Wire Debug (SWD) port
- Simple yet highly flexible power supply architecture
- Various options for easily powering the unit from micro-USB, external supplies or batteries
- High quality, low cost, high availability

![RASPBERRY PI PICO](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTjcZeUUkdpaDJMWNzA_E79JtKU3-CIMUcZFg&usqp=CAU) 

To View the Datasheet click ->  [DATASHEET](https://datasheets.raspberrypi.com/pico/pico-datasheet.pdf)


### 2) ARDUINO NANO RP2040

The feature packed Arduino Nano RP2040 Connect brings the new Raspberry Pi RP2040 microcontroller to the Nano form factor. Make the most of the dual core 32-bit Arm® Cortex®-M0+ to make Internet of Things projects with Bluetooth® and WiFi connectivity thanks to the U-blox® Nina W102 module



![ARDUINO NANO RP2040](https://robu.in/cdn-cgi/image/width=1200,height=1200,fit=crop,quality=80,format=auto,onerror=redirect,metadata=none/wp-content/uploads/2021/05/Arduino-Nano-RP2040-Connect-without-Header-2.jpg)

To View the Datasheet click ->  [DATASHEET](https://docs.arduino.cc/static/7a61a8db7d46c2397aa743e026bc1204/ABX00053-datasheet.pdf)

### 3) ARDUINO RP2040-ZERO

RP2040-Zero, A Low-Cost, High-Performance Pico-Like MCU Board Based On Raspberry Pi Microcontroller RP2040.

Key features:

- RP2040 microcontroller chip designed by Raspberry Pi in the United Kingdom
- Dual-core Arm Cortex M0+ processor, flexible clock running up to 133 MHz
- 264KB of SRAM, and 2MB of on-board Flash memory
- USB-C connector, keeps it up to date, easier to use
- The castellated module allows soldering direct to carrier boards
- USB 1.1 with device and host support and Temperature sensor
- Low-power sleep and dormant modes and 8 PIO pins

![ARDUINO RP2040-ZERO](https://www.waveshare.com/media/catalog/product/cache/1/image/560x560/9df78eab33525d08d6e5fb8d27136e95/r/p/rp2040-zero-4.jpg) 


### 4) SPARKFUN MICRO MOD PI RP2040

The SparkFun Pro Micro RP2040 is a low-cost, high performance board with flexible digital interfaces featuring the Raspberry Pi Foundation's RP2040 microcontroller. Besides the good 'ol Pro Micro footprint, the board also includes a WS2812B addressable LED, boot button, reset button, Qwiic connector, USB-C, resettable PTC fuse, and castellated pads.

Key features :

- AP2112 3.3V voltage regulator
- Support programming languages like MicroPython and C/C++
- On-board USB-C connector for programming and USB 1.1 Host/Device functionality
- Built-in Resettable PTC Fuse and PTH pads w/ castellated edges
- 20x multifunctional GPIO Pins 
- 4x 12-bit ADC channels with internal temperature sensor, 0.5 MSa/s, 12-bit & 10x PWM channels
- Serial Peripherals like 2 UART's,1 I2C, 1 SPI
- 16MB External Flash Memory and it's Dimensions: 1.3in x 0.7in
  
![SPARKFUN MICRO MOD PI RP2040](https://cdn.sparkfun.com//assets/parts/1/6/8/2/6/17720-SparkFun_MicroMod_RP2040_Processor-01A.jpg)

To View the Datasheet click ->  [DATASHEET](https://datasheets.raspberrypi.com/rp2040/rp2040-datasheet.pdf)

### 5) ADFRUIT FEATHER RP2040

A new chip means a new Feather, and the Raspberry Pi RP2040 is no exception. When we saw this chip we thought "this chip is going to be awesome when we give it the Feather Treatment" and so we did! This Feather features the RP2040, and all niceties you know and love about Feathe

Key Features:

- Measures 2.0" x 0.9" x 0.28" (50.8mm x 22.8mm x 7mm) without headers soldered in
- Light as a (large?) feather - 5 grams and New pink PCB
- RP2040 32-bit Cortex M0+ dual core running at ~125 MHz @ 3.3V logic and power
- usb type c and 264 KB RAM
- 8 MB SPI FLASH chip for storing files and CircuitPython/MicroPython code storage. No EEPROM
- Tons of GPIO! 21 x GPIO pins with following capabilities:
- Four 12 bit ADCs, Two I2C, Two SPI and two UART peripherals, 
- 16 x PWM outputs - for servos, LEDs, etc
- The 8 digital 'non-ADC/non-peripheral' GPIO are consecutive for maximum PIO compatibility

![ADFRUIT FEATHER RP2040](https://cdn-shop.adafruit.com/970x728/4884-19.jpg)

To View the Datasheet click ->  [DATASHEET](https://learn.adafruit.com/adafruit-feather-rp2040-pico/downloads)

### 6) ADIY FLY RP2040

ADIY FLY comes with a large on-chip memory, symmetric dual-core processor complex, deterministic bus fabric, and rich peripheral set augmented with a unique Programmable I/O (PIO) subsystem, RP2040 provides professional users with unrivalled power and flexibility. ADIY FLY pairs RP2040 with 4MB of Flash memory, and a power supply chip supporting input voltages from 1.8-5.5V. It provides 26 GPIO pins, three of which can function as analog inputs, on 0.1”-pitch through-hole pads with castellated edges. ADIY FLY has SD card slot installed. The RESET button on ADIY FLY makes the usage of the module easy


![ADIY FLY RP2040](https://adiy.in/wp-content/uploads/2022/04/A102691_ADIY-FLY-RP2040_4-1.jpg)

To View the Datasheet click ->  [DATASHEET](https://adiy.in/shop/pico-rp2040/development-shields-hats/rp2040-board-pico-adiy-fly/)

### 7) CYTRON MAKER PI RP2040

Cytron Maker Pi RP2040 features the RP2040 chip, embedded on a robot controller board. The board also comes with 2-channel DC motor driver, 4 servo motor ports and 7 Grove I/O connectors, ready for your next DIY robot/motion control projects.

Key Features :

- 2 MB of Flash memory and Power on/off switch
- 4x Servo motors (GPIO12. GPIO13, GPIO14, GPIO15)
- 2x DC motors with quick test buttons (Dual-channel H-bridge)
- 7 Automatic power selection: USB 5 V, LiPo (1-cell) or Vin (3.6-6 V)
- Built-in 1-cell LiPo/Li-Ion charger (over-charged & over-discharged protection)
- 13x Status indicator LEDs for GPIO pins
- 1x Piezo buzzer with mute switch
- 2x Push button and 22x RGB LED (Neopixel)
- 7x Grove ports (flexible I/O options: digital, analog, I2C, SPI, UART)


![CYTRON MAKER PI RP2040](https://static.cytron.io/image/cache/catalog/products/MAKER-PI-RP2040/maker-pi-rp2040-top-leds-logo-1x1-800x800.png)

To View the Datasheet click ->  [DATASHEET](https://www.electrokit.com/uploads/productfile/41018/MAKER-PI-RP2040%20Datasheet.pdf)

### 8) WIO RP2040

Wio RP2040 mini Dev Board is a development board based on Wio RP2040 module with wireless function, supporting MicroPython programming. It has a dual-core 133MHz RP2040 cits hip, which is a low-power microcontroller with wireless functions. With powerful performance and small size, it is a perfect option for various IOT projects development.

Key Features :

- Powerful CPU: dual-core 133MHZ RP2040 processor and 264KB SRAM, 2MB Flash
- Reliable wireless connection: using powerful wifi chip, supporting 2.4~2.4835 GHz frequency and Ap&Station mode
- Flexibility: compatible with Thonny editor
- Easy project operation: breadboard friendly
- Multiple certifications: FCC and CE Certified
- Support programming languages: MicroPython 
  
![WIO RP2040](https://files.seeedstudio.com/wiki/Wio_RP2040_mini_Dev_Board-Onboard_Wifi/board_1.jpg)

To View the Datasheet click ->  [DATASHEET](https://wiki.seeedstudio.com/Wio_RP2040_Module_Build-in_Wireless_2.4G/)

---

## TYPES WIFI MODULES

### LIST OF WIFI MODULE
- ESP-01
- ESP-07
- ESP-12E
- ESP-12F
- ESP-32
- NODE MCU
- NINA W10 SERIES
- CYW43439
  
### 1) ESP-01

The ESP 01 ESP8266 Serial WIFI Wireless Transceiver Module is a self-contained SOC with integrated TCP/IP protocol stack that can give any microcontroller access to your WiFi network

![ESP-01](https://res.utmel.com/Images/UEditor/32c98dcd-7392-419f-b534-8cab6aab720e.jpg)

To View the Datasheet click ->  [DATASHEET](https://www.microchip.ua/wireless/esp01.pdf).


### 2) ESP-07

ESP-07 can be widely used in a variety of networking, for home automation, industrial wireless control, baby monitors, wearable electronic products, wireless location sensing devices, wireless positioning system signals and other networking applications. ESP-07 is packaged in SMD

![ESP-07](https://potentiallabs.com/cart/image/cache/catalog/ESP8266/ESP07_ESP8266_Pinout_Colored-550x550w.jpg)

To View the Datasheet click ->  [DATASHEET](https://docs.ai-thinker.com/_media/esp8266/docs/esp-07s_product_specification_en.pdf).


### 3) ESP-12E

ESP-12E is a member of the "ESP-XX" series. It is a miniature Wi-Fi module used to establish a wireless network connection for a microcontroller or processor. The core of ESP-12E is ESP8266EX. This module has no complicated circuits or programming so using this module is very easy

![ESP-12E](https://microcontrollerslab.com/wp-content/uploads/2020/01/ESP-12E-Pinout.png)

To View the Datasheet click ->  [DATASHEET](https://components101.com/sites/default/files/2021-09/ESP12E-Datasheet.pdf).


### 4) ESP-12F

The ESP-12F is a WiFi module based on ESP8266, with built-in 32Mbit Flash, in the small SMD22 package. There're also onboard PCB antenna and metal shield. In short, it's a small form factor and fairly high cost effective WiFi module.

![ESP-12F](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcStkBgA8t8-D-v-kR2Wgqn6HGkxaRycmi80DbUc5KR93YKtRVXT4LkoDrv-dlz9k7XEw6A&usqp=CAU)

To View the Datasheet click ->  [DATASHEET](https://docs.ai-thinker.com/_media/esp8266/docs/esp-12f_product_specification_en.pdf).


### 5) ESP-32

ESP32 is a single 2.4 GHz Wi-Fi-and-Bluetooth combo chip designed with the TSMC ultra-low-power 40 nm
technology. It is designed to achieve the best power and RF performance, showing robustness, versatility and
reliability in a wide variety of applications and power scenarios. The ESP32 series of chips includes ESP32-D0WD-V3, ESP32-D0WDR2-V3, ESP32-U4WDH, ESP32-S0WD, ESP32-D0WDQ6-V3 (NRND), ESP32-D0WD (NRND), and ESP32-D0WDQ6 (NRND), among which, ESP32-D0WD-V3, ESP32-D0WDR2-V3, ESP32-U4WDH, and ESP32-D0WDQ6-V3 (NRND) are based on ECO V3 wafer.


![ESP-32](https://media.digikey.com/Photos/Espressif%20Systems/MFG_ESP32-DEVKITC-32U.jpg)

To View the Datasheet click ->  [DATASHEET](https://espressif.com/sites/default/files/documentation/esp32_datasheet_en.pdf).


### 6) NODE MCU

NodeMCU is an open-source Lua based firmware and development board specially targeted for IoT based Applications. It includes firmware that runs on the ESP8266 Wi-Fi SoC from Espressif Systems, and hardware which is based on the ESP-12 module

![NODE MCU](https://components101.com/sites/default/files/components/ESP8266-NodeMCU.jpg)

To View the Datasheet click ->  [DATASHEET](https://components101.com/sites/default/files/component_datasheet/ESP8266-NodeMCU-Datasheet.pdf).

### 7) NINA W10 SERIES

NINA-W10 series are stand-alone multiradio MCU modules integrate a powerful microcontroller
(MCU) and a radio for wireless communication. With the open CPU architecture, customers can
develop advanced applications running on the dual core 32-bit MCU. The radio provides support for
Wi-Fi 802.11b/g/n in the 2.4 GHz ISM band and Bluetooth v4.2 (Bluetooth BR/EDR and Bluetooth Low
Energy (LE) communications.

![NINA W10 SERIES](https://sigma.octopart.com/110750636/image/u-blox-NINA-W102-00B.jpg)

To View the Datasheet click ->  [DATASHEET](https://content.u-blox.com/sites/default/files/NINA-W10_DataSheet_UBX-17065507.pdf).

### 8) CYW43439

The Cypress CYW43439 is a highly integrated single-chip solution and offers the lowest RBOM in the industry for smartphones, tablets, and a wide range of other portable devices. The chip includes a 2.4 GHz WLAN IEEE 802.11 b/g/n MAC/baseband/radio, and Bluetooth 5.0 compliance. In addition, it integrates a power amplifier (PA) that meets the output power requirements of most handheld systems, a low-noise amplifier (LNA) for best-in-class receiver sensitivity, and an internal transmit/receive (iTR) RF switch,further reducing the overall solution cost and printed circuit board area.

![CYW43439](https://rlx.sk/19118-home_default/raspberry-pi-pico-w-pico-rp2040-incl-bgn-wireless-lan-and-bluetooth-52-cyw43439.jpg)

To View the Datasheet click ->  [DATASHEET](https://www.infineon.com/dgdl/Infineon-CYW43439-Single-Chip-IEEE-802.11-b-g-n-MAC-PHY-Radio-with-Integrated-Bluetooth-5.0-Compliance-AdditionalTechnicalInformation-v03_00-EN.pdf?fileId=8ac78c8c7ddc01d7017ddd033d78594d).