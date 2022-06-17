# BlackIce Nxt Development Kit
**The BlackIce Nxt Development Kit was designed to get early adopters of BlackIce Nxt up and running with everything they need.**
* [BlackIce Nxt](https://github.com/folknology/BlackIceNxt) Systems controller and memory
* Development Led Blade to test the MicroBlade support
* [IceLogicBus](https://github.com/folknology/IceLogicBus) Tile expansion Midplane
* Development tiles: VGA display Tile , 7-Segment display Tile, Mixmod/Pmod and Proto-typing Tile
* Full Opensource development support environment:
  * Verilog Via [Yosys and NxtPnr](https://github.com/YosysHQ/oss-cad-suite-build)
  * Python via [Amaranth](https://github.com/amaranth-lang)
  * Rust via [BlackCrab](https://github.com/folknology/BlackCrab/tree/BiNxt)

# [BlackIce Nxt](https://github.com/folknology/BlackIceNxt)
BlackIce Nxt is a new systems board for the myStorm FPGA development board family. It sports the following features:
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

# [IceLogicBus](https://github.com/folknology/IceLogicBus) 
* Ice40HX series FPGA chip:
  * 7680Luts with NVCM
  * 128Kb Embedded RAM
  * 2 Phase locked Loops
* RGB Status led
* Quad Tile expansion
* USB Power delivery
* Midplane expansion Connectors

# Kit Development peripherals
## Mixmod/Pmod and proto-typing double tile
This double tile can accommodate multiple Pmods and a single Mixmod allowing the developer to use existing Pmod/Mixmod investments or select from the many peripherals available in the market place.
## VGA Display Tile
This fun Tile is capable or driving a standard VGA Monitor from the FPGA for anything from retro gaming to the next HDL GPU you are designing!
## 7-Segment Display Tile
This is a great old school display and a rite of passage for your HDL journey.

# Expansion
Expansion is what BlackIce Nxt is all about from the simple slot in MicroBlades to the mechanically robust Tiles. These expansions will enable you to drive digital displays and audio, DC and stepper moros, Networking like Ethernet and CanBus just to name a few. You can mix and match these peripherals and can start with the provided support examples to combine them into the next great Retro system,robot or embedded project as you see fit..