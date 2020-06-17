# PasteHakk ![License](https://img.shields.io/badge/License-GNU-red.svg) ![Version](https://img.shields.io/badge/Version-1.0-yellow.svg)
A tool to perform clipboard poisoning or paste jacking attack. There are many tools for performing this type of attack but I found none of them provides user to use their own html files, so I came up with this.

[Watch tutorial on youtube](https://www.youtube.com/channel/UCAdDJn4yWzQMJyKyRWne3qg)


## What's Clipboard Poisoning or PasteJacking ?
Browsers now allow developers to automatically add content to a user's clipboard and the attacker exploits this feature. It is a type of attack where the malicious websites take control of your device's clipboard and replace it's content to something harmful without your knowledge.</br>This method can be used to entice users into running seemingly innocent commands. The malicious code will override the innocent code, and the attacker can gain remote code execution on the user's host if the user pastes the contents into the terminal.

## Screenshot
<img src="https://user-images.githubusercontent.com/46316908/84874176-db148600-b0a1-11ea-9f72-50d889ff52ac.png" width="100%"></img>

## Usage
+ Enter command to inject :</br>
Be careful with this, it is the command which will be get excuted when the target copies something from our website and pastes it into the terminal. Know your target first before entering the command, if its windows type the windows commands and same for the Linux.
+ Enable anonymous mode (y/n) :</br>
The anonymous mode clears the terminal after executing the injected command and cleares the history as well, so no logs are being created. Please note that use anonymous mode if your target is Linux for Windows append "***;clear***" at the end of the command.
+ HTML file to infect (path) :</br>
Enter the path to the HTML file, where it is stored on your device. Make sure your file contains ***\<body>*** tag else the script will show an error.


## Installing and requirements
- Linux or Unix-based system

### Installing
```
~ ❯❯❯ git clone https://github.com/3xploitGuy/pastehakk.git

~ ❯❯❯ cd pastehakk

~/pastehakk ❯❯❯ chmod +x pastehakk.sh

~/pastehakk ❯❯❯ ./pastehakk.sh
```


## Contact
[Gmail](mailto:sandeshyadavm46@gmail.com) </br>
[Instagram](https://instagram.com/1n_only_sandy) </br>
[Blog](https://virtualprivacy.blogspot.com) </br>
[Website](https://sandeshyadav.000webhostapp.com) </br>
[YouTube](https://www.youtube.com/channel/UCAdDJn4yWzQMJyKyRWne3qg)



## Disclaimer

PasteHakk is created to help in penetration testing and it's not responsible for any misuse or illegal purposes.


## Reference
[PasteJacking GitHub repo](https://github.com/dxa4481/Pastejacking)


## License

This work by [3xplotGuy](https://github.com/3xploitGuy) is licensed under the terms of the [GNU General Public License v3.0](https://www.fsf.org/).
