# Microsoft Teams Attender v2

Waking up early in the morning to attend some online classes is hard. So I made a bot that attends my boring online classes for me according to my timetable, which allows me to focus more on the classes that I prefer and get more work done.

## Compatibility
OS compatibilty: 
  - WINDOWS
  - MAC OS
  - LINUX
  
Browser compatibility: 
  - Google Chrome **ONLY**

## Installation
Installation is a a bit more complicated, but I will try to make it simple.

1. Download the latest version of Python from this [link](https://www.python.org/downloads/)
2. **IMPORTANT** : during installation, check "Add python to PATH" - (windows only)
![Python PATH](https://datatofish.com/wp-content/uploads/2018/10/0001_add_Python_to_Path.png)

3. Check you Google Chrome version

![Chrome check](https://ctrlv.link/shots/2021/01/27/IkyG.png)
![Chrome Version](https://fdn.gsmarena.com/imgroot/news/21/01/chrome-88/-1220x526/gsmarena_000.jpg)
4. Download Chrome Driver here: https://chromedriver.chromium.org/downloads
   - Chrome driver version must be compatible with your Google Chrome version
   - After downloading, move Chrome Driver to C:\Windows or /usr/bin on Mac/Linux

5. Open Command Prompt on Windows or Terminal on Mac/linux
  - type in these commands:
    - pip3 install certifi==2020.4.5.1
    - pip3 install chardet==3.0.4
    - pip3 install idna==2.9
    - pip3 install playsound==1.2.2
    - pip3 install requests==2.23.0
    - pip3 install selenium==3.141.0
    - pip3 install urllib3==1.25.9
    
6. Download the code here: https://github.com/tomassabol/MS-Teams-Attender-v2/archive/main.zip
7. Open config.json in Text Editor/Visual Studio Code/Atom
8. Type in your Microsoft Teams *email* and *password*
   - You can also configurate a few more things, but it's not necessary

9. Open Microsoft Teams (App or on web), and in settings, change **Layout settings** to "List"
![Teams Layout](https://support.content.office.net/en-us/media/6d1215fa-f8a3-4a03-930e-20c0c1bc84b2.png)
10. Now, you can finally run the script *auto_joiner.py*
