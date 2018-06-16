---
title: "Design and modeling of CELL-SPU lite Processor"
excerpt: "<i>A dual-issue Multimedia Processor based on CELL architecture.</i><br/><img width ='500' src='/images/CELL_SPU.jpg'><br/><br/><code>Computer Architecture</code>"
collection: portfolio
---

<i>A dual-issue Multimedia Processor based on CELL architecture.</i><br/>  
<br/>

SONY CELL is a x64 multicore microprocessor which was based on Broadband Engine Architecture(BEA) and was commercially featured in Playstation 3. The Synergistic Processor Unit (SPU) is the integral part of CELL and is designed to accelerate the media and streaming workloads.

The project aims to design and implement the behavioral model SPU-lite multimedia processor in System Verilog.
The emphasis is given on the design of the following aspects,
   * Design of fundamental modules such as Instruction Line Buffer(ILB), Instruction Decoder, dual pipelined ALU , Data forwarding using forwarding Macro and Local Store.
   * Handling structural hazards and data hazards (RAW, WAR and WAW)
   * Implementing the lite-ISA of 83 commands for SPU processor.

<br/>  
<span><a href='https://github.com/Karthik4293/Design-and-Implementation-of-CELL-SPU-lite-processor' target='_blank'><img style='float: left;' width = '40' src='/images/git.png'></a></span>
<br/>
<br/>
<br/>
References:  
1. <span style="color:blue"><a href='https://www.karthik4293.me/files/Cell_microarchitecture' target='_blank'>"CELL MOVES INTO THE LIMELIGHT" By Kevin Krewell {2/14/05-01}</a></span>  
2. <span style="color:blue"><a href='https://www.karthik4293.com/files/Microarchitecture_of_SPU' target='_blank'>"The Microarchitecture of the Synergistic Processor
for a Cell Processor" IEEE journal of solid-state circuits, VOL. 41, NO. 1, JANUARY 2006</a></span>
3. <span style="color:blue"><a href='https://www.karthik4293/files/SPU_ISA_v12' target='_blank'>Synergistic Processor Unit Instruction Set Architecture - V12 </a></span>
