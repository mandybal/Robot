Instructions for Line tracking Robot


Installation of GCC ARM Embedded toolchain

  1) Go to link https://developer.arm.com/open-source/gnu-toolchain/gnu-rm/downloads
  2) Download ARM Embedded toolchain
  3) Install it on the computer
  4) At the last step deselect the option “launch gccvar.bat”
  5) Click on finish button.

Installation of ECLIPSE IDE for C/C++ developer:
 
 Before starting installation make sure that java development kit and JRE are installed on computer.
  1) Go to link https://github.com/gnu-mcu-eclipse/org.eclipse.epp.packages/releases/.
  2) Download GNU MCU Eclipse IDE Neon.3 for your computer.
  3) Extract the zip file
  4) Open the folder and open eclipse.exe

Download CD BOOST library

  1) Go to link http://www.boost.org/users/download/
  2) Download for your computer
  3) Extract zip in your computer

Compile edited code in Eclipse

  1) Open project folder in eclipse
  2) Open make file
  3) In line 10 you will find the path for boost library change it with your local boost library path
  4) Click on build button it will generate .bin and. hex file in root folder

Installation of ST-LINK Utility:

  1) Go to link http://www.st.com/en/development-tools/stsw-link004.html
  2) You will find link at the end of the page to download software
  3) Download software and install it on computer.
  
  Open ST-LINK Utility
  
Importing Project into Eclipse:
  1) Extract the project
  2) Copy project folder into eclipse workspace
  3) Go to window => open perspective => other => packs.
  4) Click on refresh
  5) Go to STMelectronics => stm32f4
  6) Right click and select install
  7) Go to project, open properties of project
  8) Select C/ C++ => settings => device
  9) Select stm32411re
  10) Start editing code.

Flashing Binary Code into microcontroller:

  1) Open ST-LINK Utility
  2) Open File, go to .bin file location which is compiled using eclipse
  3) Connect Nucleo board using USB cable
  4) In ST LINK Utility click on connect button
  5) It will show device name in command line
  6) Click on Program Verify button and click start to flash code
  7) It will notify in command line once the flashing is done
  
  
