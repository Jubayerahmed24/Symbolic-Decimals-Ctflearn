# Symbolic-Decimals-Ctflearn

 In this I will tell you how to solve a CTF challenge of CTFlearn name “Symbolic decimals”.

This challenge comes in hard but I don’t think so this should be in this criteria as after solving this it was very easy. So I am coming directly to writeup.

When you open this challenge you will see some hint and the cipher.

“Did you know that you can hide messages with symbols? For example, !@#$%^&*( is 123456789!<br /> Now Try: *% *% (% %) !)& %) %! !@# &! !)! !!^ (% (& (% !)# !)% !)@ !!^ (% !)@ !!$ !!! !)( (% %@ !)& %@ %# !)$ !@% However, this isn't as easy as you might think.”

When you will see the hint you get to know that !=1 and @=2 and #=3 and so on. These are given on the upper numeric pad of keyboard.

https://prnt.sc/LsYyCsCGdU0D

But there is twist in cipher as there is comma(,) after two or three characters. But if you will print it with comma you can’t decode it further . So I used space(‘ ‘) instead of comma(,) to decode it. You can do it using pen and paper but I decode it using python :

Symbolic-Decimals-Ctflearn.py
https://github.com/Jubayerahmed24/Symbolic-Decimals-Ctflearn/blob/main/Symbolic-Decimals-Ctflearn.py

When you will run the program you will get this:

85 85 95 50 107 50 51 123 71 101 116 95 97 95 103 105 102 116 95 102 114 111 109 95 52 107 52 53 104 125

As you can see this is encoded in decimal. To decode this I used this website

https://v2.cryptii.com/decimal/text

And Boom ! you get the flag:)

UU_2k23{Some_Text}

Thanks, everyone for reading:)

Happy Hacking ;)
