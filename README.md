# EXPERIMENT--01-ALP-FOR-8086
Name : yamuna M
Reg no:212223230248




## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
"""
mov AL,77h
mov BL,99h
ADD AL,BL
HLT
"""
## Output  
![ADD](https://github.com/yamunadass/EXPERIMENT--01-ALP-FOR-8086/assets/138971172/27b300ee-620b-4930-aafe-f4a73a60d312)
## Subtraction   of 8 bit numbers  ALP 
"""
mov AL,33h
mov BL,89h
sub AL,BL
HLT
"""
## Output  
![SUB](https://github.com/yamunadass/EXPERIMENT--01-ALP-FOR-8086/assets/138971172/1261eef4-0aed-4ef2-b7ad-9797a9ef5c78)
## Multiplication alp 
"""
mov AL,90h
mov BL,80h
mul AL
HLT
"""
## Output  
![MUL](https://github.com/yamunadass/EXPERIMENT--01-ALP-FOR-8086/assets/138971172/d824a293-a915-4456-9d3d-ec53aed54c6a)
## Division alp 
"""
mov AL,90h
mov BL,80h
DIV AL
HLT
"""
## Output  
![DIV](https://github.com/yamunadass/EXPERIMENT--01-ALP-FOR-8086/assets/138971172/5f86451d-337a-4f87-8295-c96701604a9e)
## Result :
 Thus , A Program is develope to write and execute ALP on fundamental arithmetic and logical Operations.







