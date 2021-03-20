# PicoCTF 2021 - Nice Netcat
> 
>![File type](https://i.imgur.com/X0aNTOh.png)
>

**WRITEUP**

The challenge show a command from [Netcat](https://en.wikipedia.org/wiki/Netcat) over a PicoCTF URL and a port there.
Besides give us a hint talking about [ASCII](https://en.wikipedia.org/wiki/ASCII).
Well, we run the Netcat command just like they given to us, and receive some bits in ASCII.

![File type](https://i.imgur.com/02NN42m.png)

Check here the complete output:
112 105 99 111 67 84 70 123 103 48 48 100 95 107
49 116 116 121 33 95 110 49 99 51 95 107 49 116 
116 121 33 95 97 102 100 53 102 100 97 52 125 10 

After find a ASCII Converter online, [dcode.fr](https://www.dcode.fr/ascii-code), deconding the output from netcat, we catch the flag.

![File type]([https://i.imgur.com/6qfQBUp.png)


