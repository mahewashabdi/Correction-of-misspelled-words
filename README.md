# Correction-of-misspelled-words

This assignment involve the creation of a spellchecking system and an evaluation of its performance.

**Programming language** : Python<br>
**Tools** : nltk library<br>
**Dataset** : holbrook.txt (already provided)<br>
**Desciption of dataset:**
The file consists of lines of text, with one sentence per line. Errors in the line are marked with a | as follows

My siter|sister go|goes to Tonbury .
In this case the word 'siter' was corrected to 'sister' and the word 'go' was corrected to 'goes'.

In some places in the corpus two words maybe corrected to a single word or one word to a multiple words. This is denoted in the data using underscores e.g.,

My Mum goes out some_times|sometimes .
For the purpose of this assignment you do not need to separate these words, but instead you may treat them like a single token.
