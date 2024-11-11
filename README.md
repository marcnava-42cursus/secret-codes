# 42 Common Core Encoded Hint

> ⚠️ **Warning: Spoiler Alert!** ⚠️
> 
> This repository contains secret codes that may spoil your experience. If you don't want to spoil yourself, it is recommended not to proceed further. 
> 
> *Read at your own risk!*

## Libft Secret Code

This encoded message uses the **ROT13 cipher**, a simple letter substitution cipher that shifts each letter by 13 positions in the alphabet. It is commonly used in puzzles and some programming contexts, as it's easy to apply and decode without any additional keys.

- ROT13 transforms each letter by replacing it with the letter 13 positions after it in the alphabet, wrapping around if necessary (i.e., `A` becomes `N`, `B` becomes `O`, and so on).
- Decoding the message is straightforward: apply the ROT13 cipher to reveal the plain text.

### Secret code

```plaintext
Rnpu cebwrpg bs gur 42 Pbzzba Pber pbagnvaf na rapbqrq uvag. Sbe rnpu
pvepyr, bayl bar cebwrpg cebivqrf gur pbeerpg uvag arrqrq sbe gur
arkg pvepyr. Guvf punyyratr vf vaqvivqhny, gurer vf bayl n cevmr sbe
bar fghqrag jvaare cebivqvat nyy qrpbqrq zrffntrf. Nal nqinagntrq
crbcyr pna cynl, yvxr pheerag be sbezre fgnss, ohg gur cevmr jvyy
erznva flzobyvp. Gur uvag sbe guvf svefg cebwrpg vf:
Ynetr pbjf trarebfvgl pbzrf jvgu punegf naq sbhe oybaqr ungf gb qrsl
hccre tenivgl ureb
```

### Solution

```plaintext
Each project of the 42 Common Core contains an encoded hint. For each
cycle, only one project provides the correct hint needed for the
next cycle. This challenge is individual, there is only a prize for
one student winner providing all decoded messages. Any antiquated
people can play, like current or former staff, but the prize will
remain symbolic. The hint for this first project is:
Large cows generously come with chaffs and four blended hats to defy
upper gravity here
```

## Born2beRoot Secret Code

### What is Morse?
Morse code is a method used in telecommunication to encode text characters as sequences of dots and dashes. Each character (letters, numbers, punctuation) is represented by a unique combination of these signals. It was widely used in early radio communication and telegraph systems and is still known today as a way to communicate without traditional letters.

### Morse Table
Below is a simplified Morse code table for reference:

| Letter | Morse Code | Letter | Morse Code |
|--------|------------|--------|------------|
| A      | .-         | N      | -.         |
| B      | -...       | O      | ---        |
| C      | -.-.       | P      | .--.       |
| D      | -..        | Q      | --.-       |
| E      | .          | R      | .-.        |
| F      | ..-.       | S      | ...        |
| G      | --.        | T      | -          |
| H      | ....       | U      | ..-        |
| I      | ..         | V      | ...-       |
| J      | .---       | W      | .--        |
| K      | -.-        | X      | -..-       |
| L      | .-..       | Y      | -.--       |
| M      | --         | Z      | --..       |

### Secret Code

```plaintext
0010 01 11 111 001 000 11 01 10 1 0000 01 1 1010 111 11 0 000
011 00 1 0000 1 0000 0 01 0100 1 0 010 10 01 1 0 0001 0 010 000
00 111 10 111 0010 001100 001100 001100

### Solution

```plaintext
famousmanthatcomeeiththealternateverronof???
```

## ft_printf Secret Code

### What is Brainfuck?

Brainfuck is an esoteric programming language created in 1993 by Urban Müller. The language is known for its minimalistic design, using only eight commands and a memory model consisting of an array of memory cells, each initially set to zero. Despite its simplicity, Brainfuck is Turing-complete, meaning it can theoretically compute anything that can be computed by other programming languages, although in a less practical and more challenging way.

The eight Brainfuck commands are:
- `>`: Move the memory pointer to the right (to the next cell).
- `<`: Move the memory pointer to the left (to the previous cell).
- `+`: Increment the value of the current memory cell.
- `-`: Decrement the value of the current memory cell.
- `.`: Output the value of the current memory cell as a character.
- `,`: Accept one byte of input and store it in the current memory cell.
- `[`: If the value in the current memory cell is 0, jump to the instruction after the corresponding `]`.
- `]`: If the value in the current memory cell is non-zero, jump back to the instruction after the corresponding `[`.

### How to Resolve a Brainfuck Program

To interpret a Brainfuck program, you need to understand how the memory pointer moves and how the values in the memory cells are manipulated. For each command, the pointer either moves across the cells or modifies the value in the cell where the pointer currently resides.

### Secret code

```brainfuck
++++++++++[>+>+++>+++++++>++++++++++<<<<-]>>>.>---.++++++++++++.++.+++
+++.--.<<++.>>------.------------.+++++++++++++.<<.>>++++++.------------
.-------. +++++++++++++++++++.<<.>>----------------.+++++.+++++++++.---
----------.--.+ ++++++++++++++++.--------.+++++++++++++.<<.>>----------
-------------.+++.+++ ++++.---.----.+++++++++++++++++.---------------
--.-.<<.>>+++++.+++++.<<.>-------...
```

### Solution

```plaintext
Famous man that directly believed in ???
```

## get_next_line Secret Code

### What is Leet Speak 1337

### Leet Table 

|  A  |  B  |  C  |  D  |  E  |  F  |  G  |  H  |  I  |  J  |  K  |  L  |  M  |  N  |  O  |  P  |  Q  |  R  |  S  |  T  |  U  |  V  |  W  |  X  |  Y  |  Z  |
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
|  a  |  b  |  c  |  d  |  e  |  f  |  g  |  h  |  i  |  j  |  k  |  l  |  m  |  n  |  o  |  p  |  q  |  r  |  s  |  t  |  u  |  v  |  w  |  x  |  y  |  z  |
|  4  |  I3 |  [  |  )  |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|  /  |  8  |  ¢  | \|) |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|  \  |  13 |  <  | (\| |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|  @  | \|3 |  (  |  [) |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|  /- |  ß  |  ©  |  I> |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|  \  |  !3 |     |  ?  |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|  ^  |  (3 |     |  T) |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|  (L |  /3 |     |  I7 |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|  Д  |  )3 |     |  cl |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|     |\|-] |     | \|} |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|     |  j3 |     | \|] |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |
|     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |     |

### Secret Code

```plaintext
/=∂/\/\[](_)§ /\/\@|V †|-|@¯|¯ /-/!570®1<|-\£1_`/ ¢@/\/\ε vv!7}{ ???
```

### Solution

```plaintext
FAMOUS MAN THAT HISTORY CAME WITH ???
```

## **All solutions**

**Libft**

>Each project of the 42 Common Core contains an encoded hint. For each
>cycle, only one project provides the correct hint needed for the
>next cycle. This challenge is individual, there is only a prize for
>one student winner providing all decoded messages. Any antiquated
>people can play, like current or former staff, but the prize will
>remain symbolic. The hint for this first project is:
>Large cows generously come with chaffs and four blended hats to defy
>upper gravity here

**Born2beRoot**

>famousmanthatcomeeiththealternateverronof???

**ft_printf**

>Famous man that directly believed in ???

**get_next_line**

>FAMOUS MAN THAT HISTORY CAME WITH ???