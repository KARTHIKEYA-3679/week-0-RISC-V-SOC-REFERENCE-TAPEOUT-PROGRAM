# week-0-RISC-V-SOC-REFERENCE-TAPEOUT-PROGRAM
<div align="center">

![VLSI](https://img.shields.io/badge/VLSI-System%20Design-blue?style=for-the-badge&logo=chip)
![Week](https://img.shields.io/badge/Week-0-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

</div>
Welcome to my new chapter in the semiconductor industry India. 

This is my repository! on RISC-V SOC Reference Tapeout program conducting by **VLSI System Design(VSD)** in collab with IIT Gandhinagar.

This week task is entirely on the setting up of tools requried for the program.

----------------
## **Oracle Virtual Machine Setup and configurations**

I configured my Virtual machine in the following manner:

<div align="center">

| **Specs**             | **Config./Details**           |
|-----------------------|-----------------------|
| **Operating System**  | Ubuntu 24.10/ 25.04   |
| **RAM**               | 8GB                   |
| **Storage**           | 50GB HDD              |

</div>
These system specs and configurations gives you optimal performance while handling all kinds of tools and simulations requried all throughout the program

---------------------------------------------------------------
### **Required tools to be installed for the Program**

The tools and steps are :
<div align="center">

```
 Yosys →  Iverilog →  GTKWave →  Ngspice →  Magic VLSI
```
These tools are used for both testing and verification purposes which involve RTL synthesis, simulation, circuit analysis, layout design.

</div>

-------------------------------------------------------------------------

### **YOSYS**
This is a RTL Synthesis Tool.
<details>
<summary><b>Purpose:</b> Converts RTL code into gate-level representations.</summary>

Yosys is a framework for Verilog RTL synthesis. For Digital Circuits, it provides synthesis algorithms and optimization paths.

</details>

## **INSTALLATION & VERIFICATION DETAILS**

```bash
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys 
$ sudo apt install make  
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make 
$ sudo make install
```
<p align="center">
 <img <img width="1380" height="349" alt="Screenshot 2025-09-20 215349" src="https://github.com/user-attachments/assets/a97bfd8e-3c79-48a4-995c-cb50572303ff" />
</p>

<div align="center">

**Yosys Successfully Installed**

</div>

-----------------------------------------------------------------------------------------

### **Iverilog SIMULATOR INSTALLATION AND VERIFICATION**

<details>
<summary><b>Purpose:</b> Compiles and simulates Verilog designs for functional verification.</summary>

Icarus tool Iverilog is a verilog code synthesis and simulation tool.

</details>

```bash
$ sudo apt-get install iverilog #Verification i am doing with a half_adder verilog code thats already avaliable with me
```
 <img <img width="1239" height="73" alt="Screenshot 2025-09-20 220753" src="https://github.com/user-attachments/assets/9d784889-43ae-4b4b-80a1-54f5a549924a" />

 </p>

<div align="center">
  
 **Iverilog Successfully Installed**

</div>

-------------------------------------------------------------------------------

### **GTKWave Installation and Verification**
It analyzes and visualizes the simulated waveforms which are helpful for debugging.

## **GTKWave INSTALLATION AND VERIFICATION**

```bash
$ sudo apt update
$ sudo apt install gtkwave
```
<p align="center">
<img <img width="1121" height="393" alt="Screenshot 2025-09-20 221522" src="https://github.com/user-attachments/assets/1f334c92-7c6f-47d7-abab-b7f093c070b0" />

</p>

<div align="center">

**GTKWave Successfully Installed**

</div>

---

### **Ngspice Simulator**
Ngspice is a mixed-level/mixed-signal circuit simulator like LTspice software. 

## **Ngspice Installation**
```bash
$ sudo apt update
$ sudo apt install ngspice
```
<div align="center">

 **Ngspice Tool Successfully Installed**

 </div>

 ------------------------------------------------------------------------------------

###  **Magic VLSI – Layout Tool**
It can create, edit, analyzes VLSI  design layouts with the help of Design Rule Check(DRC)

It's a Open source tool used for IC design, DRC check.

##  **Magic VLSI Installation**

[Magic VLSI](http://opencircuitdesign.com/magic/) is an open-source VLSI layout tool widely used for IC design, DRC, and visualization.  

Follow the steps below to install Magic on an Ubuntu/Debian system:

```bash
# Install required dependencies
sudo apt-get install m4
sudo apt-get install tcsh
sudo apt-get install csh
sudo apt-get install libx11-dev
sudo apt-get install tcl-dev tk-dev
sudo apt-get install libcairo2-dev
sudo apt-get install mesa-common-dev libglu1-mesa-dev
sudo apt-get install libncurses-dev

# Clone Magic repository
git clone https://github.com/RTimothyEdwards/magic
cd magic

# Configure build
./configure

# Build Magic
make

# Install system-wide
sudo make install
```
<div align="center">

**Magic VLSI Successfully Installed**

</div>

---------------------------------------------------------------------------------------

## **Installation Summary**

All the above mentioned 5 tools(Yosys, Iverilog, GTKWave, Ngspice, Magic VLSI) been installed.

Now **WE ARE READY TO START FOR DESIGN JOURNEY IN THIS PROGRAM**

</div>

-----------------------------------------------------------------------------------------------

<div align="center">
** Author:** KARTHIKEYA SHARMA GUDA ( https://github.com/KARTHIKEYA-3679)
 
**Repository:** KARTHIKEYA-3679 (https://github.com/KARTHIKEYA-3679/week-0-RISC-V-SOC-REFERENCE-TAPEOUT-PROGRAM)

**Guided and Program offered by:** VLSI System Design (https://vsdiat.vlsisystemdesign.com)


</div>

