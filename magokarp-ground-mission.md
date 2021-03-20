# PicoCTF 2021 - Magikarp Ground Mission
> 
>![File type](https://i.imgur.com/bY98Osb.png)
>

**WRITEUP**

This challenge  ask for launches an instance, when we push the button, the instance starts and then given us a SSH command with a specific port (in my first launch given me the port 50786, after that, for the printscreen given me another port).
Making the connection following the instructions and providing the password, we fall down here:

![File type](https://i.imgur.com/jN7TC6X.png)

Then, looking the contents of directories and files we find the flag divided in 3 parts, followed by instructions to find the nexts pieces.

![File type](https://i.imgur.com/Yy1DoB7.png)

"1 of 3.flag.txt" containing the first piece: "picoCTF{xxsh_".
"2of3.flag.txt"  containing the second part: "0ut_0f_\/\/4t3r_".
"3of3.flag.txt  containing the thirdy part: "71be5264}".

Making the flag: picoCTF{xxsh_0ut_0f_\/\/4t3r_71be5264}
