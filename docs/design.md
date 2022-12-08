---
layout: page
title: Design
permalink: /doc/
---

# Design
<!-- Include images of the schematics for your system. They should follow best practices for schematic drawings with all parts and pins clearly labeled. You may draw your schematics either with a software tool or neatly by hand. -->

<img src="./assets/img/fft_in_reg.PNG" alt="schematic" width="100%" />
<img src="./assets/img/fft_out_reg.PNG" alt="schematic" width="100%" />

# MCU Design
The main components of the MCU include the usage of an ADC (Analog to Digital Converter), and the SPI module within the MCU. 


The source code for the project is located in the Github repository [here](https://github.com/brianSimpkins/E155_Final/tree/main/src).

# FPGA Design
The main modules within the FPGA include
1. SPI Transciever
2. 1024 bit input buffer
3. FFT Unit
    * Address Generation
    * RAM Blocks
    * Twiddle generation
    * Fused multiply accumulate
4. 1024 bit output buffer

We began by understanding then implementing a single-cycle FFT.



# Bill of Materials
<!-- The bill of materials should include all the parts used in your project along with the prices and links.  -->

| Item | Part Number | Quantity | Unit Price | Link |
| ---- | ----------- | ----- | ---- | ---- |
| Electret Microphone Amplifier - MAX4466 with Adjustable Gain |  1063 | 1 | $6.95 |  [link](https://www.adafruit.com/product/1063) |

**Total cost: $6.95**