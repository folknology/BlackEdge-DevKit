# BlackIce Nxt Development Kit

**The BlackIce Nxt Development Kit was designed to get early adopters of BlackIce Nxt up and running with everything they need.**

* [BlackIce Nxt](https://github.com/folknology/BlackIceNxt) Systems controller and memory
* Development Led Blade to test the MicroBlade support
* [IceLogicBus](https://github.com/folknology/IceLogicBus) Tile expansion Midplane
* Development Tiles: VGA display Tile , 7-Segment display Tile, Mixmod/Pmod and Proto-typing Tile
* All of the fixtures & fastners required to fix together all the modules together securely, providing excellent mechanical strength and reliability
* Full Opensource development support environment:
  * Verilog Via [Yosys and NxtPnr](https://github.com/YosysHQ/oss-cad-suite-build)
  * Python via [Amaranth](https://github.com/amaranth-lang)
  * Rust via [BlackCrab](https://github.com/folknology/BlackCrab/tree/BiNxt)

# [BlackIce Nxt](https://github.com/folknology/BlackIceNxt)
**BlackIce Nxt is a new systems board for the myStorm FPGA development board family. It sports the following features:**

* STM32F730 216Mhz Arm Cortex 7 Microcontroller with 256K RAM, 64k Flash
* 64Mbit HypeRam, 128Mbit HyperFlash for the [MidPlane](https://github.com/folknology/IceLogicBus)
* 16Mbit SPI Flash for local storage
* 25Mhz HSE and 32.768Khz LSE crystals
* 40 Pin FMC Parallel interface expansion
* QSPI interface to [MidPlane](https://github.com/folknology/IceLogicBus)
* 4 MicroBlade sockets
* SDCard Socket
* SWD connector
* USB-C connector with serial over usb interface
* RGB Status LED and Mode button
* 8 General purpose GPIO pins in addition to the FPGA IO
* 3 fast 12bit ADCs muxed over 8 pins, with sample rates up to 7MS/Sec

# [IceLogicBus](https://github.com/folknology/IceLogicBus) 
**The IceLogic Bus forms a midplane between the systems controller and the quad Modular Tile expansion. It sports the following features:**

* Ice40HX series FPGA chip:
  * 7680Luts with NVCM
  * 128Kb Embedded RAM
  * 2 Phase locked Loops
* RGB Status led
* Quad [Tile](https://github.com/folknology/Tiles) expansion
* USB Power delivery
* Midplane expansion Connectors
* 72 Super Fast programmable FPGA IOs

# Kit Development peripherals
## Mixmod/Pmod and proto-typing double tile
This double tile can accommodate multiple Pmods and a single Mixmod allowing the developer to use existing Pmod/Mixmod investments or select from the many peripherals available in the market place.
## VGA Display Tile
This fun Tile is capable or driving a standard VGA Monitor from the FPGA for anything from retro gaming to the next HDL GPU you are designing!
## 7-Segment Display Tile
This is a great old school display and a rite of passage for your HDL journey.

# Expansion Options
Expansion is what BlackIce Nxt is all about from the simple slot in MicroBlades to the mechanically robust Tiles. These expansions will enable you to drive digital displays and audio, DC and stepper motors, Networking like Ethernet and CanBus just to name a few. You can mix and match these peripherals and can start with the provided support examples to combine them into the next great Retro system, an awesome robot or embedded project as you see fit..

# What makes BlackIce Nxt special?
BlackIce Nxt provides modular mixed signal expansion for building hardware add-ons and applications, way more than the competing Ice40 development kits. It is also completely OpenSource hardware making it easy for others to build on top of its design, especially when combined with the OpenSource [Yosys toolchain](https://github.com/YosysHQ/oss-cad-suite-build). Unlike some other microcontroller only development boards BlackIce Nxt allows opensource hardware to be actually designed and synthesised using Verilog or Python in addition to programming the onboard STM32F730 microcontroller using Rust, This combination is very powerful for tackling challenging maker projects like robotics, Retro Games, RISC V designs, SOCs, IOT, motor control and embedded applications. This new modular system provides a much more robust and reliable mechanical assembly compared to traditional development systems, a critical feature often missed by most other providers.

# Why we made BlackIce Nxt
As makers, we fell in love with IceStorm opensource Verilog toolchain back in 2015 and wanted to create a `best of class` independent opensource hardware development board to fully compliment the OpenSource FPGA toolchain including Claire Xen's amazing YOSYS. You can read some of our myStorm [history](https://folknologylabs.wordpress.com/2016/08/28/a-storm-in-the-making/) and [background](https://folknologylabs.wordpress.com/2016/08/03/storm-in-a-pint-pot/) from it's debut at [OSHCAMP 2016](https://mystorm.uk/storm-surge-mystorm-debuts-at-oshcamp-2016/) through to it's latest incarnation in 2022. BlackIce is a leader in its class for modular opensource FPGA hardware, it's IO capabilities exceed many other Ice40 dev boards. It has been refined through 6 generations and has been proven in applications and deployment spanning over half a decade, it's got some real pedigree!
