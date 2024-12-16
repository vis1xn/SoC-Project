---
layout: home
title: FPGA VGA Driver Project
tags: fpga vga verilog
categories: demo
---

Hi my name is Tyrese Mumia. This is my VGA driver Project, For my project I started off with messing around with the VGA template code to further understand how it works and operates. After trying different images I finally decided on what image I wanted to recrated which was my countrys flag (Kenya). The Kenya flag was supposed to be a simply but clean image however I underestimated it as creating a shield and spears proved to be a lot more challenging than I thought. In this report I will outline my steps I took to created the flag.

## **Template VGA Design**
### **Project Set-Up**
The start template design was a straightforward demonstaration on how to add the VGA signal creation. It originally showed straight colourful stripes, this increased my knowledge of the foundation for how I was going to attempt try and re-enact a VGA timing and signal synchronization.
The project was set up in Vivado. I endsured all the design files were properly inputed and ready to start simulating, synthesising and implementing into my project. I used all the vivado tools to debug my code to find errors that were hard for me to notice. This was incredably helpful to see how everything worked together to properly work with the Basys 3 Artix 7 development board.

<img src="https://raw.githubusercontent.com/melgineer/fpga-vga-verilog/main/docs/assets/images/VGAPrjSum.png">

### **Template Code**
**VGATop:** VGA top was altered to accomodate the changes that I made when I changed colour stripes.
**VGAColourStripes:** This module uses the pixel positions to regulate the colors that are output. By default, the screen was divided into several vertical stripes, each of which had a distinct hue. The screen was divided into several vertical stripes of various colors using a straightforward but efficient logic. This made it easier for me to comprehend how the coordinates of the pixels relate to the outputs on the screen. 

<img src="https://raw.githubusercontent.com/vis1xn/SoC-Project/main/docs/assets/images/STRIPES.png">

### **Simulation**
Making a simulation was the next stage, and it helped me comprehend how the template design operated. I checked the hsync, vsync, and color signals over time using the simulator that comes with Vivado. I could see that the design was according to the VGA's standards because the simulator's waveform output allowed me to see the timing of the pulses.

The simulation had to confirm that the color regions were properly mapped to the various screen regions for this template. The above timing diagram illustrates the changes between the various color areas, confirming that the counters were increasing in accordance with the instructions that I gave it.
### **Synthesis**
Synthesis, for this step I had a design template that I changed the code into a netlist which then was used on the FPGA hardware. I used synthesis on Vivado, this gave me a detailed insight into how the design

## **My VGA Design Edit**

### **Code Adaptation**
I adapted the code so the instead of vertical lines, i had horzontal lines split up equally to create the kenyan flag.

<img src="https://raw.githubusercontent.com/vis1xn/SoC-Project/main/docs/assets/images/VgaCode.png">

### **Simulation**
Unforunatly I wasnt able to get a simulation design, the reason being that, everytime i would run the simulation, the vivado program would crash and force me to restart.
### **Synthesis**
For the synthesis process, I started with an initial design template, which I translated into a netlist for use on the FPGA hardware. To complete this, I used the synthesis tool in Vivado. This tool provided detailed insights into the resource usage, logic mapping, and timing of the design. The reports confirmed that the template design utilized minimal logic and memory, well within the capabilities of the Basys 3 Artix-7 development board. These results showed that the basic design provided by my teacher was a straightforward combinational logic sequence with counters, making it efficient and ready for FPGA programming.

### **Demonstration**

<img src="https://raw.githubusercontent.com/vis1xn/SoC-Project/main/docs/assets/images/VgaFlag.png">




<img src="https://raw.githubusercontent.com/melgineer/fpga-vga-verilog/main/docs/assets/images/VGAPrjSrcs.png">
