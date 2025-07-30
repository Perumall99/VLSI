# Challenge 01 PulseTracer

## Description
Detect a single-cycle high pulse from a noisy input stream. Ensure your design ignores short glitches and only reacts to a clean high transition.

## Module
| Name         | Description                               |
|--------------|-------------------------------------------|
| PulseTracer  | Verilog module for Challenge 01 PulseTracer |

## Files
| File Name         | Purpose              |
|-------------------|----------------------|
| PulseTracer.v     | RTL design           |
| PulseTracer_tb.v  | Testbench for design |

## Testbench Guidelines
| Test Condition   | What to Check                      |
|------------------|------------------------------------|
| Glitch Filtering | Short glitches are ignored         |
| Clean Pulse      | Single pulse generated correctly   |
| Stability        | Output remains low otherwise       |
