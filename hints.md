To get from a whole string to an array of characters use the split string method.

someString.split('');

To represent the "offset" of numbers, use 2 data structures.

1. An object that will let you translate letters to numbers.

2. An array that will let you translate numbers back into letters.

When you translate the letters into numbers you can offset that number before you translate it back into a letter:

```
var offsetNumber = 3;

var someNumber = alphabet[someLetter];

var newOffsetNumber = someNumber + offsetNumber;

var newLetter = numberToAlphabet[ newOffsetNumber ];
```

Use this in a loop to encode each letter.

Use the join method to convert the array back into a string.
