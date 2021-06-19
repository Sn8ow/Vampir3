# Vampir3
Vampir3 - Send your friend a QR code. After loading with the phone, you will get its Token to log into your discord account.

### About
A Python script that automatically generates a Nitro scam QR code and grabs the Discord token when scanned. This tool demonstrates how people can trick others
into scanning their Discord login QR Code, and gain access to their account. Use for Educational Purposes only.

![obraz](https://user-images.githubusercontent.com/80784394/122617440-947ab280-d08c-11eb-9ae9-bbaa052d7be8.png)

## Installing/Usage
1. You must download Chrome Browser [Link to download](https://www.google.pl/chrome/?brand=CHBD&gclid=CjwKCAjwiLGGBhAqEiwAgq3q_tUmyFY8de8zhALEz5dyVWtATpMW3gWeSFTGh318-xjpdjKIeKdIORoCBxIQAvD_BwE&gclsrc=aw.ds)
2. If you dont have python installed, download python 3.7.6
and make sure you click on the 'ADD TO PATH' option during
the installation !
3. Install the required modules > ```pip install -r requirements.txt``` or double click `pip_install_requirements.bat`
4. Type ```python Vampir3_Generator.py``` in cmd to run or double click `run_script.bat`
5. Wait for the `discord_gift.png` to be generated. Send the image to the victim and make them scan it.
6. QR Code only lasts about 2 minutes. Make sure you send a fresh one to the victim and he is ready to scan.
7. When the QR Code is scanned, you will automatically be logged in to their account and the script will grab the Discord token.

## Troubleshoot
Make sure your chromedriver.exe file is the same version as your current Chrome web browser version. To check your current Chrome version,
paste `chrome://settings/help` in Google Chrome.

if Chrome crashes,

1. Make sure your chromedriver.exe file is the same version as your Chrome web browser version
2. Download the latest version chromedriver.exe here: https://chromedriver.chromium.org/downloads
3. Then replace the chromedriver.exe file in the folder.
