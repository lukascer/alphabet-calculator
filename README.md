alphabet-calculator module calculates position of a letter in alphabet and backwards. It was made for data manipulation of excel sheets. 

Range: A - AZ.

-> npm install alphabet-calculator
const alphabetCalculator = require('alphabet-calculator')

alphabet-calculator module has 2 methods:

findPosition(letter)
- returns a position of the letter

example
alphabetCalculator.findPosition('A') returns 0


findLetter(number)
- returns a letter

example
alphabetCalculator.findLetter(0) returns 'A'