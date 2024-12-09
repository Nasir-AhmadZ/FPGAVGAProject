---
layout: home
title: FPGA VGA Driver Project
tags: fpga vga verilog
categories: demo
---
Hello my name is Nasir Ahmad. This is my project for the module System on Chip Design. In this project I used a Basys 3 Artix-7 FPGA board to display a VGA (VIdeo Graphics Array) image that I created using Vivado. The project was coded in verilog.

## **Template VGA Design**
### **Project Set-Up**
Summarise the set-up and design flow. Include a screenshot of your own set-up, for example see the image of my Project Summary window below. Guideline 1 short paragraph.


We were given template code by our professor Michelle Lynch. This was uploaded to moodle for our use. The first thing I did was set up my project by downloading the template code from moodle and importing it into a project within vivado. The template code included a VGATop.v, VGASync.v, VGAColorCycle.v, Testbench.v and Basys3_Master.xdc. I changed the clock frequancy to 25MHz using the clock wizard. This was done to match the timing of the VGA signal.

<img src="PXL_20241111_160449527.MP.jpg">
<img src="SoC-Images/Project Hierarchy.png">
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
