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
Outline the structure and design of the Verilog code templates you were given. What do they do? Include reference to how a VGA interface works. Guideline: 2/3 short paragraphs, consider including screenshot(s).
### **Simulation**
Explain the simulation process. Reference any important details, include a well-selected screenshot of the simulation. Guideline: 1/2 short paragraphs.
### **Synthesis**
Describe the synthesis and implementation processes. Consider including 1/2 useful screenshot(s). Guideline: 1/2 short paragraphs.
### **Demonstration**
Perhaps add a picture of your demo. Guideline: 1/2 sentences.

## **My VGA Design Edit**
Introduce your own design idea. Consider how complex/achievabble this might be or otherwise. Reference any research you do online (use hyperlinks).
### **Code Adaptation**
Briefly show how you changed the template code to display a different image. Demonstrate your understanding. Guideline: 1-2 short paragraphs.
### **Simulation**
Show how you simulated your own design. Are there any things to note? Demonstrate your understanding. Add a screenshot. Guideline: 1-2 short paragraphs.
### **Synthesis**
Describe the synthesis & implementation outputs for your design, are there any differences to that of the original design? Guideline 1-2 short paragraphs.
### **Demonstration**
If you get your own design working on the Basys3 board, take a picture! Guideline: 1-2 sentences.

## **More Markdown Basics**
This is a paragraph. Add an empty line to start a new paragraph.

Font can be emphasised as *Italic* or **Bold**.

Code can be highlighted by using `backticks`.

Hyperlinks look like this: [GitHub Help](https://help.github.com/).

A bullet list can be rendered as follows:
- vectors
- algorithms
- iterators

Images can be added by uploading them to the repository in a /docs/assets/images folder, and then rendering using HTML via githubusercontent.com as shown in the example below.

<img src="https://raw.githubusercontent.com/melgineer/fpga-vga-verilog/main/docs/assets/images/VGAPrjSrcs.png">
