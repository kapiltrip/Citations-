# Important VLSI and Digital Design Links

Quick reference page for videos worth revisiting for CDC, timing, devices, power, counters, memory, and microprocessors.

Duplicate URLs were removed so each topic appears once.

## CDC and Timing

1. [What is Asynchronous FIFO? \|\| Asynchronous FIFO DESIGN (Clock Domain crossing) Explained in detail.](https://www.youtube.com/watch?v=0LVHPRmi88c&t=32s)  
   CDC using Gray-coded pointers and synchronizers to safely move data between two clock domains.

2. [Metastability Masterclass: The Physics Everyone Gets Wrong](https://www.youtube.com/watch?v=8jJtZVEa2z0)  
   Explains metastability from setup/hold violations and why multi-FF synchronizers improve MTBF.

3. [Toggle synchronizer Explained!! Why 2 flop synchronizers cannot synchronize a pulse? \| CDC](https://www.youtube.com/watch?v=Fs0AJmESX3c&t=1s)  
   Shows why a two-flop synchronizer can miss a short pulse, then converts the pulse to a persistent toggle, synchronizes it, and reconstructs a destination-domain pulse with an XOR gate.

4. [Why Latch requires Setup and hold time ??](https://www.youtube.com/watch?v=NtFRl7wbdp8&t=14s)  
   Clear refresher on why input data must stay stable around the sampling instant.

5. [what is time borrowing (latch)? why does latches support it?](https://www.youtube.com/watch?v=uiBuEKZxIxA)  
   Shows how latch transparency lets a long path borrow time from the next stage.

6. [How to draw timing diagram for D Latch and D Flip-flop?](https://www.youtube.com/watch?v=oH-UQHBSL9Y)  
   Useful for revising latch transparency, edge-triggering, and race-through behavior.

## STA

7. [Setup time Analysis \|\| STA Tutorial 1 \|\| @knowledgeunlimited @VLSI](https://www.youtube.com/watch?v=5871uZY368g&list=PL3Soy1ohxlP2UQOzvB4wIJNs2gHalE6yW&index=1)  
   Good starting point for setup/hold analysis, timing paths, and slack calculation.

8. [STA-II: Transmission Gate, D Latch, DFF, Setup & Hold](https://www.physicaldesign4u.com/2020/04/sta-ii-transmission-gated-latch-dffsetup.html)  
   Connects transmission-gate latch and flip-flop operation to setup/hold requirements, timing slack, and the effect of clock skew.

## Devices and Semiconductor Basics

9. [EDC \| MOSFET - 6 \| Lec 73 \| GATE ECE 2021 Exam](https://www.youtube.com/watch?v=VRgfnTq-NQA&list=PLs5_Rtf2P2r75okkE2V9oXbwJI-8m-63Q&index=74)  
   Covers MOSFET operating regions, threshold voltage, and saturation current equations.

10. [Boolean Function Implementation using Transmission Gates \| VLSI by Engineering Funda](https://www.youtube.com/watch?v=9h5sNXzdEAo)  
   Explains why transmission gates pass full rail and are efficient for MUX and XOR logic.

11. [CMOS Transmission Gate Explained: Symbols, Circuit Design, Working & Truth Table](https://www.youtube.com/watch?v=wPs9hjrQd08)  
   Covers the complementary NMOS-PMOS circuit, control signals, bidirectional full-swing operation, and truth table.

12. [4 to 1 Multiplexer Implementation using Transmission Gates \| VLSI by Engineering Funda](https://www.youtube.com/watch?v=lm-imOZ0ItM&t=1s)  
    Demonstrates a 4:1 multiplexer built from transmission-gate switching paths and complementary select controls.

13. [D Latch Implementation using Transmission Gate \| CMOS Transmission Gate \| VLSI by Engineering Funda](https://www.youtube.com/watch?v=vXLBHkQwqoU)  
    Shows how transmission gates and inverters create the transparent and data-hold phases of a CMOS D latch.

14. [D Flip-Flop Implementation using CMOS Transmission Gates (Part 1)](https://www.youtube.com/watch?v=Cy4vIf0pgwg)  
    Introduces a master-slave D flip-flop implementation using transmission gates and complementary clock phases.

15. [EDC \| Semiconductor Physics - 6 \| Lec 6 \| GATE Electronics and Communication Engineering](https://www.youtube.com/watch?v=2MH4tXfcoH0&t=3s)  
   Reviews drift velocity, mobility, electric field relation, and velocity saturation.

16. [EDC \| Semiconductor Physics - 8 \| Lec 8 \| GATE Electronics and Communication Engineering](https://www.youtube.com/watch?v=4Rpn0F37I9k&list=PLs5_Rtf2P2r75okkE2V9oXbwJI-8m-63Q&index=8)  
    Focuses on mobility changes with temperature and doping, plus electron vs hole mobility.

17. [EDC \| MOS Capacitor - 3 \| Lec 63 \| GATE ECE 2021 Exam](https://www.youtube.com/watch?v=OGqiPPF4fxs&list=PLs5_Rtf2P2r75okkE2V9oXbwJI-8m-63Q&index=65)  
    Handy revision link for MOS capacitor behavior and the accumulation, depletion, and inversion picture.

## Power

18. [Power Analysis-II](https://www.youtube.com/watch?v=n649eze39Fc&list=PLLy_2iUCG87Bdulp9brz9AcvW_TnFCUmM&index=10)  
    Covers NLPM in `.lib` files and the difference between vector-based and vectorless power estimation.

19. [Power Optimization Techniques](https://www.youtube.com/watch?v=-jYtXAHvoZM)  
    Practical overview of DVFS, clock gating, and power gating for lowering power.

20. [Power Dissipation in CMOS](https://www.youtube.com/watch?v=u3--39QdD2Y)  
    Breaks CMOS power into dynamic, short-circuit, and leakage components.

## Counters and Memory

21. [Digital Electronics 09 \| Asynchronous Counter \| ECE, EE, CSE & IT \| GATE Crash Course](https://www.youtube.com/watch?v=kmBzDukmMcU)  
    Strong revision video for ripple counters, MOD-N design, and cumulative propagation delay.

22. [Digital Electronics 10 \| Complete Synchronous Counter in 2 Hour \| ECE, EE, CS IT \| GATE Crash Course](https://www.youtube.com/watch?v=T5X89yi16YI)  
    Covers synchronous counter design with common clocking, state tables, and excitation tables.

23. [Clock divided by 3 \|\| Explained step by step! [Frequency divide by 3] F/3 or F/odd number](https://www.youtube.com/watch?v=wxUqxSE_F5A)  
    Derives a divide-by-3 clock with a 50% duty cycle using D flip-flops, MOD-counter behavior, and timing waveforms.

24. [Clock divided by 3 with 75% Duty Cycle.](https://www.youtube.com/watch?v=4hOo1NeLVUE&t=25s)  
    Produces a 75% duty-cycle output by combining two 50% duty-cycle divide-by-3 waveforms with an OR gate and verifies the result with timing diagrams.

25. [DRAM - Read and Write operations (Most detailed explanation!)](https://www.youtube.com/watch?v=LyqyIKSYlxw)  
    Explains the 1T-1C DRAM cell, destructive read, sense amplifiers, and refresh.

## Microprocessors

26. [Lec-01: Introduction to 8085 Microprocessor | Microprocessor | Ankit Goyal | One Man Army](https://www.youtube.com/watch?v=R5dT2xM-7JQ&list=PLR7krO3VHssR87ODP_7GDPCVTAYXw9ech&index=16)  
    Introductory 8085 lecture covering microprocessor basics, architecture context, and course framing.
