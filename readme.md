# About
VDIFtpTool is a lightweight portable(self contained) FTP/SFTP client written in python using the tkinter GUI toolkit. Can upload, download, create, rename, copy, move and search files/folders.

All dependancies are contained in the /pkgs folder

#### Currently supported platforms:
+ Linux
+ Windows
+ FreeBSD

# Getting vdiftptool

#### Ubuntu/Debian:
I will be packing a .deb shortly
Download the repository. Navigate to the location of the folder. Run ./VDIFTPTool/Python/pythonw.exe ./VDIFTPTool/pkgs/VDIFileTransfer.launch.pyw

#### Windows:
Download VDIFTPsetup.exe. Run the installer. Launch via the desktop or start menu icons created.
NOTE: The installation is created with Pynsist and packaged with Inno Script. If you want to create a shortcut in a defferent location have the shortcut Start in(if you used the default install location): "C:\program files (x86)\VDI FTP Tool\Python\" And set the shortcut Target to: "C:\Program Files (x86)\VDI FTP Tool\Python\pythonw.exe" ..\pkgs\VDIFileTransfer.launch.pyw"
If you used a custom installation path simply change "C:\Program Files (x86)\VDI FTP Tool\Python\pythonw.exe" our for "<your custom path>\VDI FTP Tool\Python\pythonw.exe"

#### FreeBSD and other Linux distributions:
Download the repository. Navigate to the location of the folder. Run ./VDIFTPTool/Python/pythonw.exe ./VDIFTPTool/pkgs/VDIFileTransfer.launch.pyw