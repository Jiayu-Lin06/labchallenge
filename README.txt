# labchallenge 

challenge for deca lab part2&amp;3

slow, but easy to use, simply call MOVC1 - 7 in order. Takes 11 clock cycles.

------> MOVCn Instructions:
MOVC1: LOAD MULTIPLIER WITH OPERAND
MOVC2: 16 LSB PRODUCT
MOVC3: 16 MSB PRODUCT
MOVC4: 16 LSB AL BH PRODUCT
MOVC5: 16 MSB AL BH PRODUCT
MOVC6: 16 LSB AH BL PRODUCT
MOVC7: 16 MSB AH BL PRODUCT

then use ADD and ADC instruction to add up products.
32 bits result stored in 2 registers

unsigned multiplication only
