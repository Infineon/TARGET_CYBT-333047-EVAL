# CYBT-333047-EVAL

### Overview

The Infineon AIROC&#8482; CYW20706 Bluetooth&#174; and Bluetooth&#174; LE module evaluation kit (CYBT-333047-EVAL) enables evaluation, prototyping, and development of a wide array of IoT applications using the AIROC&#8482; CYW20706, a low-power Bluetooth&#174; and Bluetooth&#174; LE system on chip.

The AIROC&#8482; CYW20706 Bluetooth&#174; and Bluetooth&#174; LE system on chip provides reliable Bluetooth&#174; connectivity, along with compute capability integrating an Arm&#174; Cortex&#174;-M3 processor. This evaluation kit (CYBT-333047-EVAL) includes an Infineon in-house AIROC&#8482; Bluetooth&#174; Module hosting the AIROC&#8482; CYW20706 that is globally certified and has uFL connector for external antenna designed for reducing time-to-market.

The AIROC&#8482; CYW20706 Bluetooth&#174; and Bluetooth&#174; LE module evaluation kit (CYBLE-333047-EVAL) is supported in the AIROC&#8482; Bluetooth&#174; SDK within ModusToolbox&#8482; Software and Tools with copious code examples and documentation.

### Kit Features

* AIROC&#8482; CYW20706 Bluetooth&#174; and Bluetooth&#174; LE module (CYBLE-333047-02)
* Arduino compatible headers for hardware expansion
* USB connector for power, programming, and USB-UART bridge

### Kit Contents

* CYBT-333047-EVAL module evaluation board
* USB Standard-A to Micro-B cable

### Standalone Usage

To use the CYBT-333047-EVAL:

1) Configure the evaluation board headers/switches to the desired settings

2) Connect the evaluation board to a PC via a USB cable

3) Refer to KBA226703 for platform files, Makefile target generation, and HCI UART switch position setting for programming

4) Use ModusToolbox&#8482; 2.3 and BTSDK 3.2 (or higher) to develop your application, program, and test

Note: Recover the CYBT-333047-EVAL before programming. The Arduino-compatible headers(J3/J4/J6/J7) are optional connections, which provide additional I/O connections to the module and allow for other Arduino shields to be used during development.

Optional Usage with Arduino Shield:

Arduino compatible shields can be connected through the Arduino compatible headers (J3/J4/J6/J7) to provide additional I/O connections and functionality.

### Additional Information

Max UART baud rate is 1M. Use baud rate of 115200 for Client Control.

For more information, see [CYBT-333047-EVAL](https://www.infineon.com/cms/en/product/evaluation-boards/cybt-333047-eval/)
