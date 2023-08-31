
# Roadmap

My go-to resources as an electronics engineering student.

> :warning: Copyrighted documents are not shared.

## Learning Ressources
To evaluate each resource presented in this document, I have set up a rating system: 

❤️ : Must-Have (maximum one or two resources per part, mandatory resources)

⭐⭐⭐ : Required (almost essential reading)

⭐⭐ : Recommended (necessary or highly useful)

⭐ : Possibilities (useful in specific cases)

## Useful softwares any EE student should know
* Programming languages: [C](https://learnxinyminutes.com/docs/c/), [Python](https://learnxinyminutes.com/docs/python/), [Matlab/Octave](https://learnxinyminutes.com/docs/matlab/)
* VSCode
* [Git](https://learnxinyminutes.com/docs/git/)
* [Unix commands](http://www.ee.surrey.ac.uk/Teaching/Unix/) & [Bash scripting](https://learnxinyminutes.com/docs/bash/)
* [Docker](https://learnxinyminutes.com/docs/docker/)

## Electronics equipment
<details>
  <summary>Lab Equipment</summary>

* **Oscilloscope**: Siglent SDS1104X-E, Rigol DS1054Z, Keysight DSOX1202A, Rigol DS1104Z-S+ (with function generator), Rigol MSO5072 (w/ function generator & logic analyzer)
* **Function generator**: Siglent SDG1032X, Siglent SDG2042X
* **Lab power supply**: Rigol DP832
* **Digital multimeter** or bench digital multimeter
* **Logic analyzer**: Saleae Logic 8
* **Probes**: PCBite 4019
* Spectrum analyzer: Siglent SSA3021X

</details>

<details>
  <summary>Prototyping Kit</summary>

* Wire stripper
* Solderless breadboards
* Breadboard cables
* Stranded cables
* Resistor / Capacitor / Inductor kits
</details>

<details>
  <summary>Digital design Kit</summary>

* FPGA: Digilent Nexys A7-100T
</details>

<details>
  <summary>PCB Kit</summary>

* ESD mat
* Soldering iron
* Solder wire
* Solder flux
* Smoke extractor
* Desoldering braid
* Hot air station
* ESD tweezers set
* Screwdriver set
* Cutting pliers
* Hot glue gun
</details>

## Useful websites
* [EDN](https://www.edn.com/category/design/design-idea/)
* [All About Circuits](https://www.allaboutcircuits.com/technical-articles/) : Community of electrical engineers with hundreds of technical articles
* [Open Tetxbook Library](https://open.umn.edu/opentextbooks/subjects/electrical) : Free electrical/electronics engineering textbooks

## Basics electronics
### Books
* Practical Electronics for Inventors, P. Scherz ⭐️⭐️⭐️
* Getting started in electronics, F. Mims ⭐️⭐️
* [Analog's Engineer Pocket Reference, TI](https://github.com/victorbouvet/Roadmap/blob/016ae45148803e66964440f50d623fe73b21783e/Documentations/Analog%20design/Analog%20Engineer%E2%80%99s%20Pocket%20Reference%20Guide%20.pdf) : Quick guide for formulas ⭐️

### Tools
* [Falstad circuit simulator](https://www.falstad.com/circuit/)

## Semiconductors theory
### Books
* [Semiconductors & Transistors: An overview of theory, fabrication and application](https://github.com/victorbouvet/Roadmap/blob/4ae5053c6a56e19f460265719a8ffb5ce964754c/Documentations/Semiconductors%20%26%20Transistors%20Final%20Paper.pdf)

### Free resources
* Semiconductors theory  
&emsp;[Semiconductors Fundamentals](https://www.youtube.com/playlist?list=PLtkeUZItwHK6BGDhR8VC4W2L7Cllm8A-t)
* Semiconductors manufacturing  
&emsp;[How Microchips Are Made - Manufacturing of a Semiconductor](https://www.youtube.com/watch?v=HdcLRMv3D3g)  
&emsp;[Semiconductor Fabrication Basics](https://www.youtube.com/watch?v=qCSIGejNT4M)  
  
### Tools
* 3D view of FET : [Planar](https://skfb.ly/oGOKI), [FinFET](https://skfb.ly/oGOLU), [GAAFET](https://skfb.ly/oGOMz), [Planar Inverter](https://skfb.ly/oGOLC), [FinFET Inverter](https://skfb.ly/oGOLU)

## Analog design
To understand these resources, you need a solid grounding in fundamental electronics and semiconductors theory.

### Books
* Fundamentals of Microelectronics, B. Razavi ❤️  
      &emsp;Beginner level - Theoretical, very clear with Razavi's lectures (see Fundamentals of Microelectronics lectures, Razavi)

* Microelectronic circuits, A. Sedra & K.  Smith ❤️
      &emsp;Beginner level - Theoretical, easy to understand with good theory

* Design of Analog CMOS Integrated Circuit, B. Razavi ⭐⭐⭐  
      &emsp;Intermediate level - Theoretical/Practical

* CMOS Analog Circuit Design, P. Allen & D. Holberg ⭐⭐  
      &emsp;Intermediate level - Pratical, great for learning practical analog design 

* Analysis and design of analog integrated circuits, P. Gray ⭐  
      &emsp;Advanced, standard analog bipolar+cmos device physics, simple and slightly more complex circuits

* CMOS: Circuit Design, Layout, and Simulation, R. Baker ⭐  
      &emsp;Advanced level - Pratical, a lot of pratical and circuit design

* The Art of Analog Layout, A. Hastings ⭐⭐⭐  
      &emsp;Best book of analog layout

### Free resources
* [Fundamentals of Microelectronics lectures, Razavi](https://youtube.com/playlist?list=PLyYrySVqmyVPzvVlPW-TTzHhNWg1J_0LU) ❤️
* [New Analog Circuit Design, Ali Hajimiri - Caltech)](https://www.youtube.com/playlist?list=PLc7Gz02Znph-c2-ssFpRrzYwbzplXfXUT) ⭐⭐
* [VLSI Education Kit, ARM](https://github.com/arm-university/VLSI-Fundamentals-Education-Kit.git)

### Tools
* [LTSpice](om/en/design-center/design-tools-and-calculators/ltspice-simulator.html) : Free electronic circuit simulation software OR [QSpice](https://www.qorvo.com/design-hub/design-tools/interactive/qspice) : Same creator as LTSpice ([direct installation link](https://getqspice.com/InstallQSPICE.exe))
* [Cadence Virtuoso](https://www.cadence.com/en_US/home/tools/custom-ic-analog-rf-design/layout-design/virtuoso-layout-suite.html) : IC design, schematic and layout EDA software OR [XSchem](https://xschem.sourceforge.io/stefan/index.html) : Free schematic circuit editor - [Webinar](https://www.youtube.com/watch?v=q3ZcpSkVVuc)
* [Open Circuit Design](http://opencircuitdesign.com/) : Open-source circuit design softwares (Magic: Layout tool, XCircuit: Circuit drawing tool)

### Docs
* [CMOSedu.com](https://cmosedu.com/)
* [A Circuit for all seasons, B. Razavi](https://github.com/victorbouvet/Roadmap/tree/1e38719193fd49f83b672b1e18d9cfaddb081ba0/Documentations/Analog%20design/Behzad%20Razavi/A%20Circuit%20For%20All%20Seaons)
* [The Analog Mind, B. Razavi](https://github.com/victorbouvet/Roadmap/tree/main/Documentations/Analog%20design/Behzad%20Razavi/The%20Analog%20Mind)
* [Designers Guide](https://designers-guide.org/) : Community of Analog, Mixed-Signal and RF designers
* [OP Amp Cookbook, TI](https://github.com/victorbouvet/Roadmap/blob/016ae45148803e66964440f50d623fe73b21783e/Documentations/Analog%20design/Circuit_Cookbook_Op_Amp.pdf) + [Handbook of Op Amps](https://github.com/victorbouvet/Roadmap/blob/016ae45148803e66964440f50d623fe73b21783e/Documentations/Analog%20design/HANDBOOK%20OF%20OPERATIONAL%20AMPLIFIER%20APPLICATIONS.pdf) : Op Amps circuits books
* https://www.analog.com/en/education/education-library/tutorials/analog-electronics.html
* [Analog Design Layout](https://github.com/victorbouvet/Roadmap/blob/016ae45148803e66964440f50d623fe73b21783e/Documentations/Analog%20design/Analog%20Layout%20Design.pdf) : Compilation of various documentation of analog layout stuff
## Digital design

### Books
* Digital Design, M. Morris ❤️
&emsp;Clear, easy-to-understand information

### Free resources
* [Nandland](https://nandland.com) : Exceptional tutorial on FPGAs, VHDL and Verilog ❤️
* [ASIC World](https://www.asic-world.com/) : Good syntax reference about Verilog, SystemC and SystemVerilog (do not use as a tutorial) ⭐⭐
* [VHDLwhiz](https://vhdlwhiz.com/basic-vhdl-tutorials/) : Nandland complements ⭐
* [HDLBits](https://hdlbits.01xz.net/wiki/Step_one) + [ChipDev](https://chipdev.io/question-list) : Verilog exercises ⭐
* [ZipCPU](https://zipcpu.com/) ⭐️⭐️⭐️
* [ChipVerify](https://www.chipverify.com/)  : Verilog, SystemVerilog, UVM tutorial + interview questions ⭐
* [Nand2Tetris](https://www.nand2tetris.org/) : Complete educational project on digital design ⭐⭐⭐

### Tools
* [Xilinx Vivado](https://www.xilinx.com/support/download/index.html/content/xilinx/en/downloadNav/vivado-design-tools.html) : FPGA programming software
* [EDA Playground](https://www.edaplayground.com/) : Free IDE for SystemVerilog, Verilog, VHDL
* [Sigasi](https://www.sigasi.com/) : VHDL verification tool OR [OSVVM](https://osvvm.org/) : Open-source VHDL verification tool
* [Verilator](https://www.veripool.org/verilator/) : Verilog/SystemVerilog to C/C++ simulator
* [cocotb](https://www.cocotb.org/) : VHDL/Verilog verification simulator in Python
* [Dynamatic, EPFL](https://dynamatic.epfl.ch/) : Open-source HLS (high-level synthesis) compiler
* [WaveDrom](https://wavedrom.com/) : Waveforms generator
## Computer Architecture

### Books
* Processor Microarchitecture: An Implementation Perspective, A. Gonzalez ⭐⭐⭐  
&emsp;A good starting book
* Computer Organization and Design - RISC-V Edition, Patterson & Henessy ❤️  
&emsp; First book
* Computer Architecture: A Quantitative Approach, Patterson & Hennessy ⭐⭐  
&emsp;Second book, more advanced

### Free resources
* [Digital Design and Computer Architecture - ETH Zürich](https://www.youtube.com/playlist?list=PL5Q2soXY2Zi-EImKxYYY1SZuGiOAOBKaf) + [Materials](https://safari.ethz.ch/digitaltechnik/spring2023/doku.php?id=start) : First course ⭐⭐⭐
* [Computer Architecture - ETH Zürich](https://www.youtube.com/playlist?list=PL5Q2soXY2Zi-cAls3cyauNzM7-74Eq31O) + [Materials](https://safari.ethz.ch/architecture/fall2022/doku.php?id=schedule) : Second course ⭐
* [Introduction to Computer architecture, ARM](https://github.com/arm-university/Introduction-to-Computer-Architecture-Education-Kit.git)

### Tools
* [make](https://learnxinyminutes.com/docs/make/) and [CMake](https://learnxinyminutes.com/docs/cmake/)
* RISC-V tools:  
&emsp;[WARP-V](https://warp-v.org/) : Open-source RISC-V core  
&emsp;[Ripes](https://github.com/mortbopet/Ripes.git) : Visual computer architecture simulator using RISC-V  
&emsp;[RISC-V Assembler](https://riscvasm.lucasteske.dev/)  
&emsp;[RISC-V Instruction Encoder/Decoder](https://luplab.gitlab.io/rvcodecjs/)  
&emsp;[RISC-V Interpreter](https://www.cs.cornell.edu/courses/cs3410/2019sp/riscv/interpreter/)

### Docs
* [RISC-V Specifications](https://riscv.org/technical/specifications/) + [RISC-V ISA sheets](https://github.com/victorbouvet/Roadmap/tree/ec17ef6c32fb0fd58b2246a29d8c505602e1f49d/Documentations/Computer%20architecture/RISC-V)
* [Agner Fog's software optimization resources](https://github.com/victorbouvet/Roadmap/tree/ec17ef6c32fb0fd58b2246a29d8c505602e1f49d/Documentations/Computer%20architecture/Agner%20Fog)

## Mixed-Signal design (WIP)
 
### Books
* Design of CMOS Phased-Locked Loops, B. Razavi ⭐
* [PLL Performance, Simulation and Design, D. Banerjee](https://github.com/victorbouvet/Roadmap/blob/0d517c3513db8de11338bbcdbf5398d94f320ac1/Documentations/Mixed-Signal%20design/PLL%20Design%20Book.pdf) ⭐

### Tools
* [NGSpice](https://ngspice.sourceforge.io/osdi.html): Free Verilog-AMS (hardware description language that can model both analog and digital) simulator
* [Xyce](https://xyce.sandia.gov/documentation-tutorials/xyce-adms-users-guide/) + [ADMS](https://github.com/Qucs/ADMS) : Same as NGSPicew with Verilog-A and Verilog-AMS

### Docs
* [Designers Guide](https://designers-guide.org/) : Community of Analog, Mixed-Signal and RF designers
* [Verilog-AMS](https://verilogams.com/index.html) : Verilog-AMS tutorials + [Verilog-A Models for Circuit Simulation](https://github.com/dwarning/VA-Models)
* https://www.analog.com/en/education/education-library/tutorials/mixed-signal-electronics-systems.html
## Embedded systems design (WIP)

### Tools
* [CubeIDE](https://www.st.com/content/st_com/en/stm32cubeide.html) : STM32 development tool

* [PuTTY](https://www.putty.org/) or [Hercules](https://www.hw-group.com/software/hercules-setup-utility) : Serial port terminal

## PCB design

### Books
* [PCB Design Tutorial, D. Jones](https://alternatezone.com/electronics/files/PCBDesignTutorialRevA.pdf) : Starting tutorial ⭐⭐
* [Adafruit Guide To Excellent Soldering, B. Earl](https://cdn-learn.adafruit.com/downloads/pdf/adafruit-guide-excellent-soldering.pdf) : Complete tutorial to soldering ❤️

## Free resources
* [Mon premier PCB avec KiCad](https://www.youtube.com/playlist?list=PLuQznwVAhY2XyLtk11MdgLkLk3thxQi8K) FRENCH ONLY ❤
* [The Hitchhiker's Guide to PCB Design](https://github.com/victorbouvet/Roadmap/blob/bb77284a2cd2f3d3ad969b95160d8cb8e860b078/Documentations/PCB%20design/the-hitchhikers-guide-to-pcb-design_compressed.pdf) ⭐️⭐️⭐️
* [PCB Design Tutorial](https://www.youtube.com/watch?v=aVUqaB0IMh4) ❤️

### Tools
* [KiCad](https://www.kicad.org/)
* [SMD database](https://smd.yooneed.one/)

### Docs
* [Getting started in Kicad](https://docs.kicad.org/7.0/en/getting_started_in_kicad/getting_started_in_kicad.pdf)
* [Schematic design tips](https://www.reddit.com/r/PrintedCircuitBoard/wiki/schematic_review_tips/)
* [PCB Layout tips](https://www.reddit.com/r/PrintedCircuitBoard/wiki/pcb_review_tips/)
* [BOM list tips](https://www.reddit.com/r/PrintedCircuitBoard/wiki/bom_review_tips/)
## Digital signal processing (WIP)

### Books
* [The Scientist and Engineer's Guide to Digital Signal Processing](https://doc.lagout.org/science/0_Computer%20Science/9_Others/1_Digital%20Signal%20Processing/The%20Scientist%20and%20Engineer%27s%20Guide%20to%20DSP.pdf) ❤️

### Free resources
* [Signals and Systems, MIT](https://www.youtube.com/playlist?list=PL41692B571DD0AF9B) ⭐⭐
* [Digital Signal Processing, MIT](https://www.youtube.com/playlist?list=PL8157CA8884571BA2) ⭐⭐

### Docs
[DSP posts](https://zipcpu.com/dsp/dsp.html)
## RF (WIP)

### Books
* RF Microelectronics, B. Razavi ⭐⭐⭐️
* RF Circuit Design, C. Bowick ⭐⭐️
* ARRL Handbook (any edition) ⭐⭐️

### Free resources
* [Debunking the Digital Audio Myth](https://www.youtube.com/watch?app=desktop&v=cD7YFUYLpDc&t=2s) ⭐

### Tools
* [GNURadio](https://www.gnuradio.org/) : free toolkit for software-defined radios and signal processing
* [QCS Studio](http://qucsstudio.de/de/start/) : free circuit simulation tool with RF parameters

### Docs
* [Designers Guide](https://designers-guide.org/) : Community of Analog, Mixed-Signal and RF designers
## Programming (WIP)

### Books
* The C Programming Language, K&R ❤️
* Python book

### Free resources
[CS50 Harvard](https://www.youtube.com/watch?v=8mAITcNt710) ⭐⭐

## Protocols (WIP)

### Free resources
* [UART, I2C, SPI](https://www.youtube.com/watch?v=IyGwvGzrqp8) ⭐⭐⭐
* [CAN Protocol](https://www.youtube.com/watch?v=JZSCzRT9TTo&t=21s) ⭐
* [AMBA Protocol](https://zipcpu.com/blog/2022/05/07/learning-axi.html) ⭐ + https://github.com/adki/AMBA_AXI_AHB_APB

### Docs
* [I2C Protocol, Texas Instruments]
* (https://github.com/victorbouvet/Roadmap/blob/fffa16ed34aa63b05956932c9e818c2bff4855f5/Documentations/Protocols/slva704.pdf)
* AMBA protocol: [AMBA AXI Protocol](https://developer.arm.com/documentation/ihi0022/latest) + [AMBA AHB Protocol](https://developer.arm.com/documentation/ihi0033/latest)

## Authors
- [@victorbouvet](https://github.com/victorbouvet)



## OLD STUFF
[Semiconductors explained](https://www.youtube.com/playlist?list=PL9jh-CW6ZfSW3Ehx-rTy60sKwZ5_ezsZ7)
[Electric EDA](https://www.staticfreesoft.com/)
[Digital communications tutorial](https://complextoreal.com/tutorials/) + [Book](https://www.inference.org.uk/itprnn/book.pdf)
[Getting to Blinky](https://www.youtube.com/playlist?list=PLy2022BX6EspFAKBCgRuEuzapuz_4aJCn) ⭐
[KiCad Tutorial](https://www.youtube.com/playlist?list=PL3bNyZYHcRSUhUXUt51W6nKvxx2ORvUQB) ⭐⭐️
[CppSim](https://www.cppsim.com/) : Tool to perform system-level simulations of complex mixed-signal circuits
[FPGA design with Verilog tutorial](https://verilogguide.readthedocs.io/en/latest/)
* Digital Design by Wakerly  
&emsp;Acquire advanced knowledge of digital design
* CMOS VLSI Design by Neil Weste and David Harris  
&emsp;Read 3rd chapter carefully
