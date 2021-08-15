# 3D Solar System Scene
This was my project from the sixth semester of course Computer Graphics.


## 1     Instructions

### 1.1     Installing libraries on Linux (Ubuntu)
You can install libraries either from the Ubuntu software center or from command line.  We  recommend  command  line  and  provide  the  file  “install-libraries.sh”  to automate the complete installation procedure. To install libraries:

  1.  Simply   run  the  terminal   and   go   to  directory   which   contains   the   file
  downloaded file “install-libraries.sh”.
  
  bash install-libraries.sh

  2.  Run the command
  3.  Provide the password and wait for the libraries to be installed. If you get an error that libglew1.6-dev cannot be found, try installing an older version,

  sudo apt-get install libglew1.5-dev
  such as libglew1.5-dev by issuing following on command line

  4.  If you have any other flavour of Linux. You can follow similar procedure to
  install “OpenGL” libraries. 

### 1.2     Compiling and Executing
To compile the game (skeleton)  each  time you  will be using “g++”.  However  to automate the compilation and linking process we use a program  “make”.  Make takes as an input a file containing the names of files to compile and libraries to link. This file is named as “Makefile” in the game folder and contains the detail of all the libraries that game uses and need to linked.

So each time you need to compile and link your program (game) you will be
simply calling the “make” utility in the game directory on the terminal to perform
make
the compilation and linking.
That’s it if there are no errors you will have your game executable (on running you will see three shapes on your screen). Otherwise try to remove the pointed syntax errors and repeat the make procedure.

