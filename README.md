# reed-solomon

k = unencoded message length  
n = encoded message length  
d = hamming distance  
fixable errors per block = ![](https://latex.codecogs.com/gif.image?\dpi{110}&space;\left&space;\lfloor&space;\frac{d-1}{2}&space;\right&space;\rfloor)  
cylclic codes = any circular bit-shif of a codeword is another valid codeword  
liner codes = any sum of two valid codewords is is another valid codeword  

cyclic codes are represented as polynomials

example:  
1011 = ![](https://latex.codecogs.com/gif.image?\dpi{110}&space;1x^0&space;&plus;&space;0x^1&space;&plus;&space;1x^2&space;&plus;&space;1x^3)

