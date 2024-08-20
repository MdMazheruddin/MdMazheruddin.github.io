---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}



MdMazheruddin
===
mazhermohammed55@gmail.com
https://MdMazheruddin.github.io/
https://www.linkedin.com/in/mohammed-mazheruddin-14a480255/
===
contact: +91-8686868149
Professional Summary
======
* Having worked in IP verification for 4+ years.
* Broad knowledge of UVM, Verilog, System Verilog, and Digital Electronics.
* Solid grasp of the ASIC design flow.
* Practical knowledge of protocols such as SPI, AHB, AXI, I2C, and others.
* Thorough understanding of coverages, limitations, and oops.
* Thorough understanding of creating UVM verification environments.
* Contact with industry-standard EDA tools, such as VCS and Questasim.
* Proficiency in the analysis of regression coverage.
* Functional verification of AMBA Protocol: APB, AHB, and AXI protocol.
* Functional verification of Serial Protocol: I2C, SPI.
* Good understanding of Processor architecture, micro-architecture, and digital 
  design, RISC-V ISA.
* Knowledge of various simulation tools for Computer Architecture and VLSI.
  

Professional experience
======
* Company:
  * SISOC SEMICONDUCTOR
  * Verification Engineer
  * March 2024 – Present
* PROJECT DETAILS:
  * Project: RISC-V Processor Design and Verification; & exploring x86
  * Description: Building & leading a team of 10 engineers. Interviewing, Mentoring and assisting them in designing a high-performance RISC-V CPU from scratch.
* Roles & Responsibilities:
  * Taught(Graduate Computer Architecture)- RISC-V ISA & Micro-architecture design for RV32I/64I.
  * Illustrated them on tools and techniques for optimization and performance analysis for a fully functional CPU(examples include:- Branch prediction techniques, BHSR, Cache design, mapping techniques MSHR, Hardware & software prefetching, neural network and reinforcement learning, loop unrolling, Tomasulo and Amdahl's rule for performance analysis, dynamic scheduling).
  * Various Open-source tools and toolchain discussion, LLVM. Taught C/RISC-V assembly code.
  * Understood and guided the team to design various RISC-V Core(DLX, Mor1kx, & CLARVI).
  * Gave an overview of UVM for RISC-V CPU Verification.
  * Teaching myself and doing various projects on IA32/IA64(x86 Architecture) 🡪Y86-64 processor design and x86 assembly practice on NASM tool.
  * Exploring RISC-V(Packed SIMD/SIMD Vector extension)/ Bit manipulation/Vortex(GPU).
 
* Tools & Languages:
  * C/RISC & x86 Assembly, Verilog, and System Verilog, UVM, NASM.


* Company:
  * CHIPLOGIC
  * Verification Engineer
  * Sep 2023 – Nov 2023
* PROJECT DETAILS:

* Project: RISC-V Processor Verification                                                                                      
* Description:
  * The project involves creating a RISC-V CPU from the ground up. It comprises all previously supported and recently added extensions, and privileged and unprivileged specs.
* Roles & Responsibilities:
  * Understood and wrote tests for RISC-V Organisation and Architecture, RV32bit/64bit, extensions: (IMAFDC/ZICCLSM/ZA64RS/ZIFENCE/ZICSR).
  * Understood the specification (unprivileged and privileged).
  * Wrote the verification strategy/plan for the above variants of RISC-V.
  * Encoding of pseudo-instructions and writing the risc-v instructions test cases, debugging and handling the traps for hint-instructions, misaligned addresses/load/store/faults/illegal trap exceptions.
  * Wrote macros for different instructions.
  * Implementation of the switching modes (M, S, and U) of risc-v/various features/enabling the virtualization (sv32/39/48/57) and memory subsystems (cache, MMU, TLB, VM/PM).
  * Implementation of CSR listing.
  * Understanding the hypervisor mode.
  * Understanding of the risc-v environment, linker script, and toolchain makefile and makefrag.
* Tools & Languages:
  * RISC-V GNU toolchain, gdb, SPIKE, Assembly, Gitlab, Jira, Asciidoc.


* Company:
  * Cyient
  * Design Verification Engineer
  * Sep 2021–April 2022
* PROJECT DETAILS

* Project: Polar fire (FPGA) (firmware)                                                                                 
* Description:
  * PolarFire SoC FPGAs are the fifth-generation family of non-volatile SoC FPGA devicesbuilt on state-of-the-art 28nm non-volatile process technology. The PolarFire SoC family offers the industry's first RISC-V-based SoC FPGAs capable of running Linux. It combines a powerful 64-bit 5x core RISC-V Microprocessor Subsystem (MSS),based on SiFive’s U54-MC family, with the PolarFire FPGA fabric in a single device.
* Roles & Responsibilities:
  *	Understanding the specifications of the block.
  *	Verified the testcases on Read_zeroization, puf_emulation, pnvm_prog, user_public_keyfw_infoservice.
  * Secded Error injecting for (2-bit and 1-bit): Read_zeroization,puf_emulation,pnvm_prog,user_public_key,fw_infoservice
* Tools & Language:
  * Assembly,System Verilog, UVM,Questasim.
* Client:
  * Microchip
  * Verification Engineer
  * Dec 2021 - March 2022                                                       
  
* Company:
  * Pozibility
  * Verification Engineer
  * May 2021-Sep 2021                                                       
* PROJECT DETAILS

* Project: Verification of AMBA AXI.                                                                                      
* Description:
  * The AMBA AXI protocol is targeted at high-performance, high-frequency system design. It has separate address/control and data phases and supports for unaligned data transfers using byte strobes, burst-based transactions with only start address issued, and support for burst lengths up to 256 beats. 
* Roles & Responsibilities:
  * Understanding the specifications of the block.
  * Developed UVM Test bench for verification.
  * Listing down features, scenarios.
  * Worked on code and functional coverages.
  * Verified the testcases on AWSIZE, AWBURST, AWLEN, WSTRB, WLAST.
* Tools & Languages:
  * System Verilog, UVM, Questasim

* Company:
  * Elechem 
  * Verification Engineer
  * Jan 2019-April 2021                                                       
* PROJECT DETAILS
  
* Project: Verification of AMBA AHB                                                                                     
* Description: 
* AHB implements the features required for high-performance, high-clock frequency systems including burst transfers, single-clock edge operation, non-tristate implementation, wide data bus configurations.

* Roles & Responsibilities:
  * Understanding the specifications of the block.
  * Test plan development.
  * Developed UVM components for AHB Master agent.
  * Listing down features, scenarios.
  * Checked all the Signals and their functionalities
* Tools & Languages:
  * System Verilog, UVM, Questasim.


* Project: IP Level Verification of I2C                                                                                     
* Description:
  * The I2C bus uses two wires: serial data (SDA) and serial clock (SCL). All I2C master and slave devices are connected with only those two wires. Each device can be a transmitter, a receiver, or both. Some devices are masters – they generate bus clocks and initiate communication on the bus, other devices are slaves and respond to the commands on the bus. To communicate with a specific device, each slave device must have an address that is unique on the bus. I2C master devices (usually microcontrollers) don’t need an address since no other (slave) device sends commands to the master. 
* Roles & Responsibilities:
  * Test plan development.
  * Analyzing waveforms.
  * Coding Test bench components including reference models.
  * Verification closure using Functional coverage and code coverage as closing criteria.
  * Debugged and test issues reported.
* Tools & Languages:
  * System Verilog, UVM, Questasim.

* Project: AES block cipher implementations with AMBA-AHB interface                                                         * Description:
  * Network security has become the backbone of information technology due to broad security issues and large amounts of data flowing over the network. HW security solutions are often preferred in contexts where a high level of performance is required. This work presents an optimization of the AES core using synthesis tools that exploit composite field arithmetic for the S-Box module implementation. 
* Roles & Responsibilities:
  * Encryption and Decryption test cases ran and debug.
  * Reported major issues of test scenarios.
  *	Verified encryption and decryption test and scenario.
  *	Written uvm components and developed test bench architecture
* Tools & Languages:
  * verilog,System Verilog, UVM, Questasim.


Technical Skills
======
* Protocol Knowledge
  * Serial(I2C, SPI,UART)
  * AMBA(APB, AHB & AXI) protocol
  * Network protocol AES
* HDVL
  * Verilog, SystemVerilog
* Programming language
  * C/C++, Python X86/RISC-Assembly
* Methodology
  * UVM, Go-UVM
* Tools
  * Synopsys VCS, Mentor’s Questa Sim, Aldec- Riviera, GVIM, VS code, git, Jira, Vivado 	
* Operating System
  * Linux, Windows

Education
======
* B.Tech. in Electrical and Electronics, passed out in 2009-2013 session with Distinction from ARKAY College of Engineering and Technology (JNTUH), Hyderabad,Telangana, India.
