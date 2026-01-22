## How it works

A 2-1 multiplexer (mux) has 2 inputs and a single output. The output for any combination of inputs depends on a select signal. For example, in this design, A and B are inputs and O is the output. Let S be the select signal. Whenever S = 0, the output will always follow A, regardless of what B is. Vice versa, when S = 1, the output will follow B, regardless of what A is. When S = 0, the values of B are "dont care" values. When S = 1, the values of A are "dont care" values.

## How to test

You test it by sending select signals of 0 and sending inputs A and B and checking if the outputs match the expected values based on the select line. Refer to the truth table of a 2-1 mux below.

| S | A | B | O |
|---|---|---|---|
| 0 | 0 | X | 0 |
| 0 | 1 | X | 1 |
| 1 | X | 0 | 0 |
| 1 | X | 1 | 1 |

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any

NONE

## Pinout

### Inputs

| Pin     | Name |
|---------|------|
| ui[0]   | A    |
| ui[1]   | B    |
| ui[2]   | S (select)   |
| ui[3]   |      |
| ui[4]   |      |
| ui[5]   |      |
| ui[6]   |      |
| ui[7]   |      |

### Outputs

| Pin     | Name |
|---------|------|
| uo[0]   | O    |
| uo[1]   |      |
| uo[2]   |      |
| uo[3]   |      |
| uo[4]   |      |
| uo[5]   |      |
| uo[6]   |      |
| uo[7]   |      |
