## FAL3014

The FAL3014 Cipher is a polyalphabetic substitution cipher. It is similar to the Vigenère cipher but uses a different method of generating the key. It is more secure than the Vigenère cipher.
The encryption of the original text is done using the Vigenère table but there is a little change in it.
• The table consists of the alphabets written out 51 times in different rows instead of 26 as in Vigenère, each alphabet shifted cyclically to the left compared to the previous
  alphabet, corresponding to the 51 possible Caesar Ciphers.
• At different points in the encryption process, the cipher uses a different alphabet from one of the rows.
• The alphabet used at each point depends on a repeating keyword.

51= 6+1+12+3+15+14 => FALCON/ FAL3014

### Encryption:
The first letter of the plaintext is the first letter of the key. So use the row and column of the Vigenère square. Similarly, for the second letter of the plaintext, the second letter of the key is used.
The rest of the plaintext is enciphered in a similar fashion


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

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
