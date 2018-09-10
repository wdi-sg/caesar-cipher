# caesar-cipher
![https://media.giphy.com/media/Ro2MgOxH9iaVG/giphy.gif](https://media.giphy.com/media/Ro2MgOxH9iaVG/giphy.gif)

Create a function that encodes text with a caesar cipher.

The function signature should look like this: 
```
caesarCipher( text ) => returns encoded text
```

Create an `index.html` and `script.js` file to run your code.

If you need help starting, look in the hints file.

How a Caesar Cipher works: 
[(from wikipedia)](https://en.wikipedia.org/wiki/Caesar_cipher)

The transformation can be represented by aligning two alphabets; the cipher alphabet is the plain alphabet rotated left or right by some number of positions. For instance, here is a Caesar cipher using a left rotation of three places, equivalent to a right shift of 23 (the shift parameter is used as the key):

```
Plain:    ABCDEFGHIJKLMNOPQRSTUVWXYZ
Cipher:   XYZABCDEFGHIJKLMNOPQRSTUVW
```

When encrypting, a person looks up each letter of the message in the "plain" line and writes down the corresponding letter in the "cipher" line.

```
Plaintext:  THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG
Ciphertext: QEB NRFZH YOLTK CLU GRJMP LSBO QEB IXWV ALD
```

### Further
Create a function with an argument to say how far to offset the alphabet.

### Further
Create a function that uses your above function to re-encode the text a second time.

### Further
Create a function that takes a third argument, how many times to re-encode the text.
