# M4ldu1n-Oh
Collection of malduino scripts for pentesters and red teaming.

## Usage:

  1. Download .txt files

  2. Put a 1, 2 or 3 before the script you wanna use. (exp: 1simple-poc-script.txt, 2auto-recon.txt, 3wifi-pwd-grabber.txt)

  3. Put the file(s) you wanna use in your microSD card.

  4. Put your microSD card in your malduino.

![20221101_175236](https://user-images.githubusercontent.com/40497633/199295450-0d372e1b-61ef-4d4d-b2a2-2e6aa7656d83.jpg)


  5. select the wanted position. (file 1, 2 or 3)
  
  ![20221101_181103](https://user-images.githubusercontent.com/40497633/199295346-9ee20d3c-6bf8-4ef6-9201-64bd725b7e40.jpg)


  6. Plug the malduino and make an evil laugh !

## Scripts:

- simple-poc-script.txt: Simply write "Malduino Ready !" in a notepad window.

- auto-recon.txt: Execute multiple recon commands on the computer and paste results in a file named "recon.txt".

- wifi-pwd-grabber.txt: Search for cleartext wifi passwords stored in the computer and paste results in a file named "wifipwd.txt".

- screenshot.txt: Take screenshot of the entire screen every 5min for 1h.

- KillDefender.txt: Try to disable Windows Defender on the targeted computer. ( /!\ Need Admin rights)
Command to enable back if complete disable work => "Set-ItemProperty 'HKLM:\SOFTWARE\Policies\Microsoft\Windows Defender' DisableAntiSpyware 0"
and then "Restart-Computer"

- BrowserDataGrabber.txt: Grab juicy files from Chrome, Edge and Firefox browsers and put them in a repository named BrowserInfo.

- NetworkScan.txt: Make a local network ip and port scan. (Change the ip in .txt file to target an other ip range)

- GetGPPpwd.txt: Search for encrypted passwords in Group Policies Preferences xml files and put results in a file named GPPpwd.txt.

- ADEnum.txt: Enumerate Active Directory environment and put results in a file named adoutput.txt. (Not finished => "Beta")

- VoiceAssistant.txt: Simply activate Voice Assistant. x)

### Disclaimer: This tool have been designed for cybersecurity curious, pentesters and red team operators for your own computers or on computers you are allowed to test. Please, do not use it for illegal purposes.

## Screenshots

![Capture d?????cran 2022-11-01 183203](https://user-images.githubusercontent.com/40497633/199299775-d83acc72-80f4-46a4-86fa-377ebaf57df2.png)

![image](https://user-images.githubusercontent.com/40497633/199300537-0bcab853-970f-43e3-a709-e2322357b4f3.png)
