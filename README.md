Since Thetis Key Manager did not have a Windows Installer just a app to run, I developed a Windows Installer for it.
To make the use of the program handy for all my family and friends it was time to make a more user friendly installer.
I will include the Inno Setup Compiler Script and the compiled version of everything so the program can also be installed
on anyones computer. It's safe, Clean and virus free. Test it yourself if your not sure. I work in the security industry. 

I have informed Thetis.io about the application I developed for their software to make it more user friendly and add the 
ability to uninstall their app and also add it to their start menu.  I hope they take this seriously. Not having a installer
for a piece of software can be difficult for end users who rely on a start menu. 

If you wish to compile this on your own download https://files.jrsoftware.org/is/6/innosetup-6.5.4.exe and 
make a directory structure like so: 

C:\InstallerFiles\Thetis
Move the install program "Thetis Key ManageR_1.1.18_1.exe" to the c:\InstallerFiles\Thetis Directory
Load Inno Setup Compiler
Paste the script above into the compiler
Set your output directory under Build> Output Directory
After you set your output directory click Build the Compile. 
Then run the executable "Thetis Key Manager Setup.exe"

Done. 

