# Understanding 8-bit Graphics :)

To start, let's understand what is meant when talking about 8-bit graphics.  
When video game consoles were first created in the 70s, the processors were naturally not as advanced as the processors used nowadays. Any new computer these days runs on a 64-bit processing system. In the 80s, the first computer to run on a 32-bit processor was released however, due to their smaller size, game consoles were limited to 8-bit.

## let's start from the basics..
### what are these 'bits' you speak of?
The term '***bit***' is short for '**binary digit**'.  
Each 'bit' represents *a place to store information*. To make this short and sweet, a binary digit can either be a 0 or a 1. Think of it as a light switch, when the 'bit' is set to 0 it's essentially 'off'. When the 'bit' is set to 1, it is on.

Now to understand some of the maths behind it. It runs on the basis of 2<sup>n</sup> :  
***(n being the number in front of the bit)***  
*1-bit* (aka 2<sup>1</sup>) has 2 possible states - 0 and 1.  
*2-bit* (aka 2<sup>2</sup>) has 4 possible states - 00, 01, 10, 11.  
*4-bit* has 16 possible states - 0000, 0001, 0010, 0011, 0100, 0101, 0110, 0111, 1000, 1001, 1011, 1010, 1100, 1101, 1110, 1111.  
*8-bit* has 256 possible states - which i'm not going to list out (for obvious reasons).

Essentially, this means that any game console running on 8-bit has 256 possible units to store information.   
Let's imagine this as a grid:    

<img src="256grid.png" width="300">

Each individual unit in this grid stores a single piece of information and when dealing with 8-bit video games (such as the first Mario Bros on Nintendo's first console - NES) this grid was used for the colour palette. Only 256 colours could be used.
