# PicoCTF 2021 - Challenge Python Wrangling
> 
>![File type](https://i.imgur.com/FPoEcsQ.png)
>

**WRITEUP**

Just like the challenge description suggest, we ca run a python script and then uses a password to get the flag.
The challenge provides 3 files. "ende.py",the python script, "pw.txt", what I presumed correctly was a .txt file with the password to use and "flag.txt.en", being the flag.
Taking a look in the script, I note a "import from cryptography.fernet" which confirm my suspicion about the flag ends in ".en" is a encrypted file.
By keep reading the ".py" I saw the instructions to decrypt and encryt files and that the script efectvely will ask for a password. 

![File type](https://i.imgur.com/ctV4nHy.png)

Then, running the script and following the instructions to decrypt, then providing de password taken from "pw.txt", we catch the flag.

![File type](https://i.imgur.com/5M8d4AM.png)

![File type](https://i.imgur.com/h2BTUR5.png)

