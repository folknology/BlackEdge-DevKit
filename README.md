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