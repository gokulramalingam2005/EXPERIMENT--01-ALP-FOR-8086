# EXPERIMENT--01-ALP-FOR-8086
Name : Gokul R

Roll no : 212222230039

Date of experiment : 14-3-25





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
```
MOV AL, 78H
MOV BL, 54H
ADD AL,BL
HLT
```

## Output  
![ADD](https://github.com/user-attachments/assets/2ba8dc2f-e135-4fba-88e7-7e5537e8e6df)

 
## Subtraction   of 8 bit numbers  ALP 
```
MOV AL, 78H
MOV BL, 54H
SUB AL,BL
HLT
```
## Output  
![SUB](https://github.com/user-attachments/assets/a25ee2ef-a732-44ce-b6d2-53741851efb2)

## Multiplication alp 
```
MOV AL, 78H
MOV BL, 54H
MUL BL
HLT
```
 ## Output  
![MUL](https://github.com/user-attachments/assets/60e28edb-1376-4105-b7c3-adfc84a556d4)


## Division alp 
```
MOV AL, 78H
MOV BL, 54H
DIV BL
HLT
```

## Output  
![DIV](https://github.com/user-attachments/assets/484da9a3-15ea-44b6-b3bb-c7d6dcfd41ed)

## NOT alp
```
MOV AL , 78H
NOT AL
HLT
```

## Output 
![NOT](https://github.com/user-attachments/assets/61b29c59-da2e-4bb8-9187-36a1213caed9)


## AND alp
```
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```

## Output
![image](https://github.com/user-attachments/assets/5f84ff3a-49ab-4d41-aa2d-4895c637ecb3)

## OR alp
```
MOV AL, 78H
MOV BL, 54H
OR AL,BL
HLT
```

## Output 
![OR](https://github.com/user-attachments/assets/5015b4e0-bab7-41f7-93fd-064062741819)

## XOR alp
```
MOV AL, 78H
MOV BL, 54H
XOR AL,BL
HLT
```

## Output 
![XOR](https://github.com/user-attachments/assets/b2ac083f-3237-4fbc-a15a-cbb60d908927)

## Result :
Thus, the program executed successfully.
