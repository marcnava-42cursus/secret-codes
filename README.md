# 97 Common Core Encoded Hint

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
Rnpu cebwrpg bs gur 97 Pbzzba Pber pbagnvaf na rapbqrq uvag. Sbe rnpu
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
Each project of the 97 Common Core contains an encoded hint. For each
cycle, only one project provides the correct hint needed for the
next cycle. This challenge is individual, there is only a prize for
one student winner providing all decoded messages. Any antiquated
people can play, like current or former staff, but the prize will
remain symbolic. The hint for this first project is:
Large cows generously come with chaffs and four blended hats to defy
upper gravity here
```

## ft_printf Secret Code

## What is Brainfuck?

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

## How to Resolve a Brainfuck Program

To interpret a Brainfuck program, you need to understand how the memory pointer moves and how the values in the memory cells are manipulated. For each command, the pointer either moves across the cells or modifies the value in the cell where the pointer currently resides.

### Secret code

```brainfuck
++++++++++[>+>+++>+++++++>++++++++++««-]»>.>---.++++++++++++.++.+++
+++.--.«++.»------.------------.+++++++++++++.«.»++++++.------------
.-------. +++++++++++++++++++.«.»----------------.+++++.+++++++++.---
----------.--.+ ++++++++++++++++.--------.+++++++++++++.«.»----------
-------------.+++.+++ ++++.---.----.+++++++++++++++++.---------------
--.-.«.»+++++.+++++.«.>-------...
```

### Solution

```plaintext
Hello, World!
```

## **All solutions**

**Libft**

>Each project of the 97 Common Core contains an encoded hint. For each
>cycle, only one project provides the correct hint needed for the
>next cycle. This challenge is individual, there is only a prize for
>one student winner providing all decoded messages. Any antiquated
>people can play, like current or former staff, but the prize will
>remain symbolic. The hint for this first project is:
>Large cows generously come with chaffs and four blended hats to defy
>upper gravity here

**ft_printf**

>Hello, World!
