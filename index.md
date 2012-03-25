---
layout: layout
---
## What we want to do ##
We design digital logic cores written in Verilog, and we
decided to write a book about it with the following goals:

- Show how to write code that will synthesize into actual hardware suitable for
  use in FPGAs and ASICs.
- Show detailed design patterns for common logic. 
- Make it available to everyone.

Most books try to teach Verilog the language, which has many non-synthesisable
constructs. We want to teach the art of building hardware using Verilog as the
means to describe that hardware.

## Who should read this book ##
Everyone, obviously. Really we want to help the next generation of logic
designers by showing them how it's actually done in industry.

## We want your help ##
Social coding is all the rage these days and for good reason. Open
collaboration keeps a project honest and everyone benefits from the diverse
knowledge base. Hopefully we will learn a bunch of new things as well.  The
book will be incrementally published on the web as we write it via the
wonderful service, GitHub. 

## Table of contents ##
We'll start with the proposed table of contents and will take suggestions from
the community for things you'd like to see in the book, so speak up and join
in. 

### Logic Machines - The Digital Designers Illustrated Primer ###

- Introduction

    - Describing Hardware

    - RTL vs. Behavioral

    - Tools of the trade

- Fundamentals

    - The Module

        - Ports List
         
        - Instances 

        - Wires and Regs

        - Timescales

        - Parameters
        
    - Signal States

    - Memory Arrays

    - Pins and Pads

    - Levels of Logic

- Combinational Logic
    
    - Simple Logic Gates

    - Concatenation
    
    - Multiplexers

    - Functions

    - always @(\*)

    - Propigation Delay

    - Priority Encoding

- Sequential Logic
    
    - Non-blocking

    - The Register (flip-lop)

- Common Logic Blocks

    - Synchronizer

    - Counters

    - Shift Registers

    - Edge Detectors

    - Pulse Stretchers

    - State Machines

    - RAMs

    - ROMs

    - CSRs - Control and Status Registers
    
        - Read Mux

        - Address decoding

- Math
    
    - Integer

    - Fixed Point

    - Arithmetic operators

- The Simulation Environment
    
    - The Testbench

    - Behavioral Models

    - Writing Tests

    - Time
    
    - Initial blocks

    - $dumpfile

    - $dumpvars

- Synthesis

    - FPGA - Field Programmable Gate Array

    - ASIC - Application Specific Integrated Circuit

- Projecst
    
    - Simple

        - "Hello World!" - Light an LED

        - Light an LED with an external input switch

        - Cylon LEDs

        - Cylon LEDs w/PWM fading

        - 7-segment decoder

    - DSP - Digital Signal Processing

        - FIR Filter - Finite Impulse Response
 
        - IIR Filter - Infinite Impulse Response

        - NCO - Numerically Controlled Oscillator
