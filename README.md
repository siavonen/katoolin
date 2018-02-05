![katoolin](https://cloud.githubusercontent.com/assets/8742190/9415562/83397aae-4840-11e5-8f72-28dfffcc70a9.png)
# katoolin
Automatically install all Kali linux tools

# Features
- Add Kali linux repositories
- Remove kali linux repositories
- Install Kali linux tools

# Requirements
- Python 2.7
- An operating system (tested on Ubuntu)

# Installation
- sudo su
- git clone https://github.com/LionSec/katoolin.git && cp katoolin/katoolin.py /usr/bin/katoolin
- chmod +x /usr/bin/katoolin
- sudo katoolin 

# Video
https://www.youtube.com/watch?v=8VxCWVoZEEE

# Usage
- Typing the number of a tool will install it
- Typing 0 will install all Kali Linux tools
- back : Go back
- gohome : Go to the main menu
- By installing armitage , you will install metasploit

# Warning
Before updating your system , please remove all Kali-linux repositories to avoid any kind of problem .

# I have some questions!

Please visit https://github.com/LionSec/katoolin/issues

=================================================================================

This version of Katoolin has been modified by me to bypass the following error code.

```
Traceback (most recent call last):
  File "katoolin.py", line 1290, in main
    inicio1()
  File "katoolin.py", line 37, in inicio1
    opcion0 = raw_input("\033[1;36mkat > \033[1;m")
NameError: name 'raw_input' is not defined
```

Credit for this solution goes to ![Strit](https://forum.manjaro.org/t/solved-katoolin-not-installing-properly-help/31872/10)
