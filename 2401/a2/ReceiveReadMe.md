### Name: Hugh Xie  
### Student Number: 101036694  
##### Purpose: COMP2401 Assignment 2  
* Transmit: Outputs messagee represented as short intergers that have been encoded and randomly subjected to errors.
* Receive: Takes the encoded message with errors and corrects the potentially flipped bits by implenting the Hamming Code. The program then outputs the original and corrected messages.

| Source Files |
| ------ |
| bit_manipulation.c |
| bit_manipulation.h |
| transmit.c |
| receive.c |

#### Compilation Instructions:
##### receive.c:
&nbsp;
```sh
$ gcc -o recv receive.c bitmanipulation.c
$ ./recv
```
the user will then be prompted to enter the message from transmit.c program..
example input:
```sh
$ 2432 2136 3264 3136 3324 1796 2668 1276 3634 3264 3094
```
example output:
```sh
> Transmitted Message:
> HEldo0W/rl`
> Corrected Transmitted Message:
> Hello World
```
