# EXPERIMENT--01-ALP-FOR-8086
# Name :NARMADHA SREE S
# Roll no :212223240105
# Date of experiment :23-08-2024





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
~~~
org 100H
MOV AX,4454H;
MOV BX,3322H;
ADD AX,BX;
MOV [3000H],AX;
ret
~~~
## Output  
 ![image](https://github.com/user-attachments/assets/fd4ac8e1-6bf9-437d-81cb-bd9a73651b42)
## Subtraction   of 8 bit numbers  ALP 
~~~
org 100h
MOV AX,3848H;
MOV BX,7008H;
SUB AX,BX;
MOV [6000H],AX;
ret
~~~
## Output 
![Screenshot 2024-08-19 134121](https://github.com/user-attachments/assets/5b1a7cc3-c4df-4916-b524-febee4eac637)
## Multiplication alp 
~~~
org 100h
MOV AX,48FFH;
MOV BX,38EEH;
MUL AX;
MOV [7000H],AX;
ret
~~~
 ## Output  
 ![Screenshot 2024-08-19 134525](https://github.com/user-attachments/assets/a69d9565-58cf-48fd-a60e-e5f610abe7ab)
## Division alp 
~~~
org 100h
MOV AX,48FFH;
MOV BX,38EEH;
DIV AX;
MOV [7000H],AX;
ret
~~~
## Output  
![Screenshot 2024-08-23 084559](https://github.com/user-attachments/assets/5d7a47e7-e21c-4148-88b8-ac6e914c2fe5)
## Programs for logical  operations
## or
~~~
org 100h
mov si,5000h;
mov ax,4585h;
mov bx,8945h;
or  bx,ax;
ret
~~~
## OUTPUT
![Screenshot 2024-08-19 140610](https://github.com/user-attachments/assets/05abbead-3f49-4067-b191-4973370357ec)
## AND
~~~
org 100h
mov ax,38h;
mov bx,48h;
 ax,bx;
mov [si],ax;
ret
~~~
## output
![Screenshot 2024-08-19 142819](https://github.com/user-attachments/assets/dfd5421f-b3ec-4eb3-8ddf-711dfdb06476)
## NOT
~~~
org 100h
mov [si+4],ax;
mov ax,44h;
mov bx,58h;
not ax;
mov [si+6],ax;
ret
~~~
## OUTPUT
![Screenshot 2024-08-19 143121](https://github.com/user-attachments/assets/274b89a8-336f-45a2-9a63-f352a9963f41)
## XOR
~~~
org 100h
mov ax,38h;
mov bx,48h;
xor ax,bx;
mov [si+2],ax;
ret
~~~
## OUTPUT
![Screenshot 2024-08-19 142633](https://github.com/user-attachments/assets/21b2cc3b-950c-4286-bb2b-45ebb57e9d6f)
## Result :
Thus, to write and execute ALP on fundamental arithmetic operations and logical operation is successful.







