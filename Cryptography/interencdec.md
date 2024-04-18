# interencdec
> Can you get the real meaning from this file.
#### Hints
> Engaging in various decoding processes is of utmost importance

In the file you are going to find thi:
> YidkM0JxZGtwQlRYdHFhR3g2YUhsZmF6TnFlVGwzWVROclh6ZzVNR3N5TXpjNWZRPT0nCg==

It seems like a simple Base64 encryption so lets use [Cyberchef](https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true,false)&input=WWlka00wSnhaR3R3UWxSWWRIRmhSM2cyWVVoc1ptRjZUbkZsVkd3eldWUk9jbGg2WnpWTlIzTjVUWHBqTldaUlBUMG5DZz09Cg) to decrypt it.
After decrypting it we recieve something that still looks like Base64 so lets decrypt it a second time with the result of the first decrypt:
> b'd3BqdkpBTXtqaGx6aHlfazNqeTl3YTNrXzg5MGsyMzc5fQ=='

We got something unreadable... But it did not really make sense so i removed the B from the front, then we recieved something that looked like the right format of the flag:
> wpjvJAM{jhlzhy_k3jy9wa3k_890k2379}

Now this just looks like it has been encrypted with cipher, and now when i use [Dcode](dcode.fr/caesar-cipher) i recieve the flag!
### Flag: picoCTF{caesar_d3cr9pt3d_890d2379}