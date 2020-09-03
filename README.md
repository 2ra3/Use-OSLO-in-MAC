# Use-OSLO-in-MAC

NOTE: To open the mac-terminal:

1)Click Command+Space

2)Type Terminal

3)Click Enter

Follow the steps given below (in the README file) to run OSLO on your mac system.

1)Go to mac-terminal and type:

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

and press enter.

This command will install Homebrew in your system. Type your mac password to proceed with the installation process. 

2)After installation, open another terminal and type:

brew cask install xquartz

3)After installation, open another terminal and type:

brew install wine

This installs wine on you computer which lets you run windows files. 

3)Save the OSLO2019_EDU_Insaller.exe in Desktop preferably. Open a new terminal and type:

wine /Users/rahilshajahan/Desktop/OSLO2019_EDU_Installer.exe 

This will run the installer and keep clicking 'Next'. Do not change any folder destinations. 
NOTE: You will have to change 'rahilshajahan' to your username on mac.

4)After finishing installation process, open a new terminal and type:

wine /Users/rahilshajahan/.wine/drive_c/Program\ Files/Lambda\ Research\ Corporation/OSLO\ 64bit\ EDU/OSLOedu.exe 

This will run the OSLOedu.exe program.
NOTE: You will have to change 'rahilshajahan' to your username on mac.

5)While saving files in OSLO, make sure to give proper destination folder in Desktop preferably.

Thank you for reading. I hope this information has helped you.
