# README

# Combinational Logic Circuits Lab

A collection of digital logic circuit designs implemented in Logisim Evolution, showcasing the core principles of combinational logic.  
Each part demonstrates specific Boolean relationships through various gate combinations, serving as a practical exploration of digital design fundamentals.

--------------------------------------------------------------------------------

## Overview

This project includes three logic designs that progressively introduce more complex Boolean functions.  
Students can open and simulate these circuits in Logisim Evolution to visualize how digital gates interact to form predictable logical behavior.

Each `.dig` file corresponds to a different part of the lab, representing a standalone combinational circuit.

--------------------------------------------------------------------------------

## Files

| File | Description |
|------|--------------|
| lab2_part1.dig | Simple combinational logic using AND and OR gates |
| lab2_part2.dig | Circuit introducing NOT gates and logic inversion |
| lab2_part3.dig | Multi-input logic network combining multiple gate levels |

All designs use labeled inputs (`in0`, `in1`, `in2`, etc.) and outputs (`out0`) to make simulation and testing straightforward.

--------------------------------------------------------------------------------

## Part 1 – Basic Combinational Logic

- Demonstrates how AND and OR gates interact to implement compound Boolean conditions.  
- Example structure: `(A AND B) OR (C AND D)`.  
- Teaches input dependency and truth table formation.

Expected output: HIGH when any valid input pair condition is satisfied.

--------------------------------------------------------------------------------

## Part 2 – Inverted Logic and Complementary Behavior

- Introduces NOT gates to demonstrate inversion logic.  
- Explores gate combinations like `(A AND NOT B)` or `(NOT A OR C)`.  
- Emphasizes the importance of logical complements in control circuits.

Expected output: HIGH for selective inverse combinations of input signals.

--------------------------------------------------------------------------------

## Part 3 – Compound Multi-Input Circuit

- Combines multiple smaller logic sub-blocks to form a larger Boolean system.  
- Each sub-block can be treated as a minterm contributing to the overall output.  
- Demonstrates hierarchical circuit design and signal aggregation.

Expected output: reflects the combined evaluation of several logic conditions.

--------------------------------------------------------------------------------

## How to Simulate

1. Open **Logisim Evolution** (recommended) or **Logisim Classic**.  
2. Load any `.dig` file (e.g., `lab2_part1.dig`).  
3. Use toggle switches to change input values.  
4. Observe the result on the output LED or labeled output pin.  
5. Optionally add probes or truth tables to verify Boolean equivalence.

--------------------------------------------------------------------------------

## Learning Objectives

- Understand combinational logic behavior and gate relationships.  
- Translate Boolean algebra into circuit form.  
- Observe the effect of signal inversion and multi-level logic.  
- Verify circuit output against theoretical truth tables.  
- Develop familiarity with digital circuit simulation tools.