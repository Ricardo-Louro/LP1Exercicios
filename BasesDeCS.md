#### Exercício 1:

![Exercise 1](https://cdn.discordapp.com/attachments/1021375162836328510/1081223306314780732/image.png)

    &= is the Bitwise AND assignment which uses the binary representation
    to compare two values. If both of them have a 1 in the same place, it
    remains a 1, otherwise, it is turned into a 0.
    
    a = 0xFEDE = 1111 1110 1101 1110
    0x0F0F = 0000 1111 0000 1111
    
    As such a &= 0x0F0F turns a into 0000 1110 0000 1110 which is 0x0E0E
    which is 3598.
---
#### Exercício 2:

    |= is the Bitwise OR assignment which uses the binary representation
    to compare two values. If either of them have a 1 in a certain place, it
    becomes a 1. If neither of them have a 1, it becomes a 0.

    a = 0xFEDE = 1111 1110 1101 1110
    0x0F0F = 0000 1111 0000 1111

    As such |= 0x0F0F turns a into 1111 1111 1101 1111 which is 0xFFDF
    which is 65503.
---
#### Exercício 3:

    TO BE COMPLETED