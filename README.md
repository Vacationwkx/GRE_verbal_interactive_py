# GRE_verbal_interactive_py

A small program showing in terminal, using interactive mode to increase the concentration

## Before using

- Fit for linux and windows
- Based on python3.7
- Package needed : xlrd, xlwt,xltuils

    ```
    pip3 install xlrd
    pip3 install xlwt
    pip3 install xltuils
    ```

## Supporting
- Regular Experssion
  - for "\*", need to type ""\\\\\*""
- Special alphabet
  - é : use e/
  - è : use e\
    - like "éclat" just type "e/clat"
  - ï : use i..

## How to use

1. Choose continuing learning or starting a bra new turn.
   ```
   1. type 'no' for a new one
   2. press any key to continue
   ```
2. Choose the file by typing the number in terminal:
   ```
   1. 6 stufe
   2. xdf 6 stufe
   3. 3000
   4. Phrase
   ```
3. Choose the study mode:
  ```
   - typing correct mode(default)
   - fast view mode
  ```
4. Type ":s" at any place to exit and the record will be noted.

5. Type ":f XXX" out of review mode, to find the "XXX" in any word, and show the relative explanation, like :
    ```
    Please reprint: :f a
    >
    annoy
    banality
    ...
    ```
6. After every 5 words will be stopped and maybe review for better equality, also file autosaved.

### Tips :
   > in the review, when word is showed, remind the meaning of it and type any key to continue reviewing
