# Braille-to-binary
A braille to binary convertor using logic gates. Made a 6+1-bit braille to binary convertor using logic Gates. Supports 0-9 and A-Z. Use t to switch between number and alphabets.\
 I/O: '6-bit braille cell + 1-bit mode toggle in → 6-bit binary out.
## Gates used 
NAND -> 107
## Tools
Logisim\
## Problem
During my regular daily update time (scrolling reels) I saw a video of how people actually write in braille using a stencil. It made me wonder if I ever need to communicate with someone who only knows braille how would I do that. Learning braille would be interesting, but as an electronics student it was not a valid one.
## Solution
A simple digital circuit which can take braille as input and gives binary as output which can then be connect to any other system like, 7 segment display, LED matrix etc. to convert it into a readable output. The system uses 7 input buttons, 6 of which are for braille input and 1 is to toggle between alphabets and numbers.\
[Crcuit schematic](images/circuit-schematic.png)
## How to use
1. Install the [logisim](https://sourceforge.net/app/logisim-evolution/) application
2. Download the .circ file.
3. Open the file in logisim.
4. Use a, b, c, d, e, f as braille inputs.
5. Turn on t for alphabets as input.
### button layout
a • • b\
c • • d\
e • • f
## Future
The circuit is planned to be programmed in Verilog and implemented on a FPGA board.
For suggestion or questions contact on Linkedin or E-Mail both available in profile.\
Well reply as soon as possible
