# Scratch-Built 4-Bit Computer

## Programming

This computer is programmed using five 8-bit switches. Each switch sets the instruction for one clock cycle.

* The **first 4 bits** control the operation of the computer
* The **second 4 bits** represent the numerical input (in binary)

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

## Overview

I’ve always wondered how computers actually work, so building one from scratch felt like the best way to learn.

Below is the full schematic of the computer:

<img width="7690" height="3105" alt="4 bit computer" src="https://github.com/user-attachments/assets/02da2816-64f4-489b-b293-fd88f76cfa8c" />

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
