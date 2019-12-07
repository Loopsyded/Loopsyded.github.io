---
layout: post
title: NACTF Solutions
categories: [CTF, writeup]
---
# NACTF Solution
[CTFtime.org / NACTF](https://ctftime.org/ctf/350) - 2019
- - - -
### THE METAMEME
* Flag located in meta data of pdf.
* win
- - - -
### DEXTER’S LAB
* SQL Injection
	*  `' OR 1=1 #`
- - - -
### BufferOverflow #0
* Overflowed buf by inputting data over 16 bytes which caused a seg.fault.
* Main function uses signal function as a listener for seg. fault.
* when seg. Fault is triggered, win function is called.
- - - -
### My ears hurt
* Audio file in audacity
* Convert the sound signature into morse code.
* Get flag
* win
- - - -
### Get a grep
* recursive
* cd into branch folder
* grep -r “nactf”
* win
- - - -
### Get a grep #1
* grep -E ‘[aeiouAEIOU]{7}’ flag.txt
* win
- - - -
### Cellular Evolution #0
* Follow instructions
* Record black and white after gen.17
* Convert binary into text
* Place text into nactf{…}
