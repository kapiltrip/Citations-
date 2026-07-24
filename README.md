# Important VLSI and Digital Design Links

Quick reference page for videos worth revisiting for CDC, timing, devices, power, counters, and memory.

Duplicate URLs were removed so each topic appears once.

## CDC and Timing

1. [What is Asynchronous FIFO? \|\| Asynchronous FIFO DESIGN (Clock Domain crossing) Explained in detail.](https://www.youtube.com/watch?v=0LVHPRmi88c&t=32s)  
   CDC using Gray-coded pointers and synchronizers to safely move data between two clock domains.

2. [Metastability Masterclass: The Physics Everyone Gets Wrong](https://www.youtube.com/watch?v=8jJtZVEa2z0)  
   Explains metastability from setup/hold violations and why multi-FF synchronizers improve MTBF.

3. [Why Latch requires Setup and hold time ??](https://www.youtube.com/watch?v=NtFRl7wbdp8&t=14s)  
   Clear refresher on why input data must stay stable around the sampling instant.

4. [what is time borrowing (latch)? why does latches support it?](https://www.youtube.com/watch?v=uiBuEKZxIxA)  
   Shows how latch transparency lets a long path borrow time from the next stage.

5. [How to draw timing diagram for D Latch and D Flip-flop?](https://www.youtube.com/watch?v=oH-UQHBSL9Y)  
   Useful for revising latch transparency, edge-triggering, and race-through behavior.

## STA

6. [Setup time Analysis \|\| STA Tutorial 1 \|\| @knowledgeunlimited @VLSI](https://www.youtube.com/watch?v=5871uZY368g&list=PL3Soy1ohxlP2UQOzvB4wIJNs2gHalE6yW&index=1)  
   Good starting point for setup/hold analysis, timing paths, and slack calculation.

## Devices and Semiconductor Basics

7. [EDC \| MOSFET - 6 \| Lec 73 \| GATE ECE 2021 Exam](https://www.youtube.com/watch?v=VRgfnTq-NQA&list=PLs5_Rtf2P2r75okkE2V9oXbwJI-8m-63Q&index=74)  
   Covers MOSFET operating regions, threshold voltage, and saturation current equations.

8. [Boolean Function Implementation using Transmission Gates \| VLSI by Engineering Funda](https://www.youtube.com/watch?v=9h5sNXzdEAo)  
   Explains why transmission gates pass full rail and are efficient for MUX and XOR logic.

9. [EDC \| Semiconductor Physics - 6 \| Lec 6 \| GATE Electronics and Communication Engineering](https://www.youtube.com/watch?v=2MH4tXfcoH0&t=3s)  
   Reviews drift velocity, mobility, electric field relation, and velocity saturation.

10. [EDC \| Semiconductor Physics - 8 \| Lec 8 \| GATE Electronics and Communication Engineering](https://www.youtube.com/watch?v=4Rpn0F37I9k&list=PLs5_Rtf2P2r75okkE2V9oXbwJI-8m-63Q&index=8)  
    Focuses on mobility changes with temperature and doping, plus electron vs hole mobility.

11. [EDC \| MOS Capacitor - 3 \| Lec 63 \| GATE ECE 2021 Exam](https://www.youtube.com/watch?v=OGqiPPF4fxs&list=PLs5_Rtf2P2r75okkE2V9oXbwJI-8m-63Q&index=65)  
    Handy revision link for MOS capacitor behavior and the accumulation, depletion, and inversion picture.

## Power

12. [Power Analysis-II](https://www.youtube.com/watch?v=n649eze39Fc&list=PLLy_2iUCG87Bdulp9brz9AcvW_TnFCUmM&index=10)  
    Covers NLPM in `.lib` files and the difference between vector-based and vectorless power estimation.

13. [Power Optimization Techniques](https://www.youtube.com/watch?v=-jYtXAHvoZM)  
    Practical overview of DVFS, clock gating, and power gating for lowering power.

14. [Power Dissipation in CMOS](https://www.youtube.com/watch?v=u3--39QdD2Y)  
    Breaks CMOS power into dynamic, short-circuit, and leakage components.

## Counters and Memory

15. [Digital Electronics 09 \| Asynchronous Counter \| ECE, EE, CSE & IT \| GATE Crash Course](https://www.youtube.com/watch?v=kmBzDukmMcU)  
    Strong revision video for ripple counters, MOD-N design, and cumulative propagation delay.

16. [Digital Electronics 10 \| Complete Synchronous Counter in 2 Hour \| ECE, EE, CS IT \| GATE Crash Course](https://www.youtube.com/watch?v=T5X89yi16YI)  
    Covers synchronous counter design with common clocking, state tables, and excitation tables.

17. [DRAM - Read and Write operations (Most detailed explanation!)](https://www.youtube.com/watch?v=LyqyIKSYlxw)  
    Explains the 1T-1C DRAM cell, destructive read, sense amplifiers, and refresh.
