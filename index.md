## FAL3014

The FAL3014 Cipher is a polyalphabetic substitution cipher. It is similar to the Vigenère cipher but uses a different method of generating the key. It is more secure than the Vigenère cipher.
The encryption of the original text is done using the Vigenère table but there is a little change in it.
- The table consists of the alphabets written out 51 times in different rows instead of 26 as in Vigenère, each alphabet shifted cyclically to the left compared to the previous
  alphabet, corresponding to the 51 possible Caesar Ciphers.
- At different points in the encryption process, the cipher uses a different alphabet from one of the rows.
- The alphabet used at each point depends on a repeating keyword.

51= 6+1+12+3+15+14 => FALCON/ FAL3014

### Encryption:
The first letter of the plaintext is the first letter of the key. So use the row and column of the Vigenère square. Similarly, for the second letter of the plaintext, the second letter of the key is used.
The rest of the plaintext is enciphered in a similar fashion


### Decryption:
Decryption is performed by going to the row in the table corresponding to the key, finding the position of the ciphertext letter in this row, and then using the column’s label as the plaintext.
Transposition: Here the encrypted test is passed to a columnar transposition cipher where,
1. The message is written out in rows of a fixed length, and then read out again column by column, and the columns are chosen in some scrambled order.
2. Width of the rows and the permutation of the columns are usually defined by a keyword.
3. For example, the word HACK is of length 4 (so the rows are of length 4), and the permutation is defined by the alphabetical order of the letters in the keyword. In this case,    the order would be “3 1 2 4”.
4. Any spare spaces are filled with nulls or left blank or placed by a character
5. Finally, the message is read off in columns, in the order specified by the keyword.

### Transposition Encryption:
1. A matrix of Key’s length is done containing the no of rows the same as the length of the key.
2. The words of the output of the FAL3014 are placed accordingly below the key in the matrix.
3. Then then columns get shifted or transposed w.r.t the alphabetical order of the key. Ex: HACK will have order 3124.
4. This is the final output.

### Transposition Decryption:
1. Decipher it, the recipient has to work out the column lengths by dividing the message length by the key length.
2. Then, write the message out in columns again, then re-order the columns by reforming the keyword.

### Steps:
1) User inputs a String.
2) The String gets converted into an encrypted form of FAL3014 Cipher.
3) This output is passed to Columnar Transposition Cipher.
4) This is the final output
5) To decrypt the output of Columnar Transposition Cipher is passed to the decrypter function.
6) This output is passed to the decrypter function of FAL3014 Cipher

### FAL3014 Cipher Pseudocode

key = "HACK" # key for transposition

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/FalcoN046/FAL3014/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
