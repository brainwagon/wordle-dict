# wordle-dict.py
While tinkering around with some simple programs that used entropy to try to pick the best possible starting words, I was originally
using the 5 letter words extracted from the /usr/share/dict/words on my Ubuntu box.  But it's clear that the word list I generated was 
rather signficantly larger than the one used by the actual app.    So.. I instead peeked at the Javascript source code, and 
found that the official wordlist was stored within, as well as the list of words which you are allowed to enter as your guesses.
For fun, and convenience, I coded them up as simple lists in Python.  You might find them useful for experimentation.
