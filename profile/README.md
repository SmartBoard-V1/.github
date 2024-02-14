## Project Description: SmartBoard - A Platform for Education and Rapid Prototyping

SmartBoard is a development and educational platform designed to facilitate learning and project development in hardware programming languages such as VHDL, Verilog, and SystemVerilog. Aimed at demystifying the complexities of hardware design and simplifying the process of FPGA (Field-Programmable Gate Array) interfacing, this platform stands as a crucial tool in both educational and development spheres. It enables the swift implementation of support for various interfaces and the testing of preliminary versions or concepts of entire System on Module (SOM) setups, truly embodying the essence of Rapid Prototyping.

![Audio Effects and Filters Development on SmartBoard](profile/sb_v1_xp2_overview.jpg)

The hardware concept of SmartBoard, akin to Arduino, features a main board and a multitude of modules that can be swiftly connected in various ways. This modularity not only facilitates quick expansions but also significantly enhances the educational experience by allowing educators to demonstrate numerous project configurations, design principles, and then move to labs where these systems are brought to life.

For Rapid Prototyping, SmartBoard allows for the quick assembly and testing of project concepts. Operational projects can easily transition to dedicated hardware, often requiring minimal adjustments. The platform's flexibility and the ability to quickly adapt to new requirements or expand with additional modules make it an invaluable tool in the development process. Its capability to connect multiple modules of the same type, such as I/O interfaces or control units, adds a layer of versatility invaluable in debugging and real-time system monitoring.

### Example Application: Audio Effects and Filters Development

A prime example of SmartBoard's capabilities is its configuration for developing hardware-based audio effects and filters. This setup includes a system integrated with 8 potentiometers to control the parameters of the audio processing module, selection switches for operating modes, and stereo audio input/output with 48KHz sampling. This practical application showcases how SmartBoard can be used to experiment with and refine sophisticated audio processing techniques in a real-world context.


![Audio Effects and Filters Development on SmartBoard](SmartBoardV1/media/example_audio.png)

By joining the SmartBoard community, developers and educators can contribute to the platform's evolution, share their projects, and leverage a collective repository of knowledge and resources. This collaborative environment not only accelerates individual project development but also enriches the learning experience for all users.

## Expansion Modules Overview

SmartBoard's versatility is significantly enhanced by its range of expansion modules, each designed to add specific functionalities and interfaces to the platform. Below is an overview of the available modules along with placeholders for their descriptions and links to their respective repositories.

### Expansion Module: Audio Line-In
This module, featuring the CS5343 audio ADC, enables high-quality audio recording and processing with features like high sample rates up to 192 kHz, low power consumption, and a compact size for easy integration. It connects via an I2S interface, making it perfect for digital audio capture in various designs.  
[go to repo](https://github.com/SmartBoard-V1/expansion_module_audio_line_in)

### Expansion Module: ARDUINO UNO
Fully compatible with Arduino UNO, this expansion module is designed to enhance FPGA system operations within the smartboard ecosystem. It supports UART and I2C communication, along with interrupt handling, making it a versatile tool for debugging, configuring, and controlling hardware projects on FPGA. Programmed via USB, it simplifies firmware updates and configurations.  
[go to repo](https://github.com/SmartBoard-V1/expansion_module_ARDUINO_UNO)

### Expansion Module: BT RN42
The Bluetooth RN42-I/RM Expansion Module offers a compact, low power solution for adding Bluetooth 2.1 + EDR wireless capability to devices. Ideal for mobile applications, it ensures robust serial communication via UART, fully compliant with Bluetooth standards.  
[go to repo](https://github.com/SmartBoard-V1/expansion_module_BT_RN42)

### Expansion Module: SW8 BTN4
This repository contains the design and implementation details of the Control Input Module, which features an 8-position rotary switch, 4 buttons, and a single digit 7-segment display, all powered by an ATtiny48 microcontroller. Designed as a versatile control interface for smartboard applications, it connects through two smartboard connectors to offer enhanced functionality.  
[Go to repo](https://github.com/SmartBoard-V1/expansion_module_sw8_btn4)

### Expansion Module: MicroSD
Designed for seamless interfacing with FPGA on the SmartBoard platform, this module provides a microSD card slot to facilitate easy data storage and retrieval. It's an excellent resource for learning about microSD interfacing and for practical data management applications.  
[Go to repo](https://github.com/SmartBoard-V1/expansion_module__micoSD)

### Expansion Module: Triple I2C
This module enhances Smartboard prototyping capabilities by offering three independent I2C outputs, enabling management of multiple I2C devices simultaneously. It integrates easily with Smartboard's single connectors, supporting a variety of connectivity options including JST, GROVE, and GOLD PIN headers for oscilloscope bus monitoring. It's versatile for connecting sensors, memory modules, RTCs, and other I2C devices, also serving as an educational tool for learning about hardware I2C interfaces.  
[Go to repo](https://github.com/SmartBoard-V1/expansion_module_triple_I2C)

### Expansion Module: SPI Flash
Designed to interface with FPGA on the SmartBoard platform, this module provides an SPI interface for connecting flash memory, making it a versatile tool for both data storage and SPI flash interfacing learning experiences. It efficiently integrates with a single socket on the SmartBoard, enhancing the board's capabilities without compromising on space or connectivity.  
[Go to repo](https://github.com/SmartBoard-V1/expansion_module_spi_flash)


### Expansion Module: BLE BMD330AR
*Opis...*  
[Link do repozytorium](#)

### Expansion Module: Oscillators
*Opis...*  
[Link do repozytorium](#)

### Expansion Module: Dual Rotary Encoder
*Opis...*  
[Link do repozytorium](#)

