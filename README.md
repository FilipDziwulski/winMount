# winMount

Two shell scripts: wmount and wumount 



wmount

To use, enter in terminal:

$ . wmount ‘\\windows\file\path'
 
The script converts the path into smb format, mounts the directory into ~/winMount, and navigates to the mount. If you want, you can then '$ open .' to open in a finder window. 
(FYI: If you omit the ‘.’ before the wmount command, It will still work, but won’t cd to the mounted directory.)
 


wumount

To use, enter in terminal:

$ . wumount
 
cd to your home directory, unmounts the ~/winMount directory, and removes it.
 



To install, you can:


brew tap fdziwuls/tap

brew install winMount
