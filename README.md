# Scratch-Built 4-Bit Computer
## Overview

I’ve always wondered how computers actually work, so building one from scratch felt like the best way to learn.

Below is the full schematic of the computer:

<img width="7690" height="3105" alt="4 bit computer" src="https://github.com/user-attachments/assets/02da2816-64f4-489b-b293-fd88f76cfa8c" />

The Computer is going to be assemenled on breadbaords where each logic gate is a logc ic some examples of this are ben eaters 8 bit cpu which is made along the same lines.
<img width="259" height="194" alt="image" src="https://github.com/user-attachments/assets/421777d4-90fe-4557-b286-c26cbe66425f" />
Each logic ic has many logic gates built into it which allows for simpeler and easier wiring.

Here are some more examples of CPUs that are similar to the one i am going to build:
<img width="1080" height="607" alt="image" src="https://github.com/user-attachments/assets/aaa3fd8b-a497-4d7d-bd03-229efbe5b15f" />
<img width="2048" height="1607" alt="image" src="https://github.com/user-attachments/assets/9747efac-04d4-4eab-9b54-1d79fa6ce453" />


### What it can do

The computer is can do basic arithmetics on to 4 bit numbers and output up to a 5 bit number  it can also show negative numbers up to minus 15. 

## Programming

This computer is programmed using five 8-bit switches. Each switch sets the instruction for one clock cycle.

* The **first 4 bits** control the operation of the computer
* The **second 4 bits** represent the numerical input (in binary)

  ### What everything does

# The Program counter:
This allows the computer to know what clock tick it is on so that is can know which peice of code to to run.

# 4-5 Decoder:
This converts the input from the program counter into an input to the tri state buffers to allow different data streams to go onto the bus depending on the clock tick.

# The op code reg
This is just a buch of tri state buffere connected to an 8 bit input. This is used to program the computer.

# The ALU
I have already explained this before

# Sub vs add
This just allows you to choose between adding or subtracting

# Dlatch Reg
This is just a bunch of d latches used to store a number that can be used in claculations.

# Accumulator
I have already explained this before


### Instruction Set

Here’s what each command does:

* `0001` = Accumulator Register Store
* `0010` = Instruction Register Store
* `0011` = Add
* `0100` = Subtract
* `0101` = Display

After selecting a command, you simply input the number in binary, and the computer executes it.

### Example

```
00110101
```

This means: **Add 5**

---



---

## Design Approach

This computer is built using integrated circuit logic gates. While it would be possible to use individual transistors, that would take far too long and be much more complex to assemble.

---

## Bill of Materials (BOM)

Below is the BOM, also available in CSV format:

<img width="737" height="636" alt="BOM" src="https://github.com/user-attachments/assets/813a0413-2e68-4d3b-a7b4-c53a33c993c4" />

---

## Goals

Once completed, this computer should be able to perform basic calculations, and possibly even multiplication if programmed correctly.

---

## Simulation

If you want to test this computer yourself, go to the Digital Logic Sim folder I shared and open the file called **CPU**. From there, you’ll be able to fully simulate and experiment with how the computer works.
