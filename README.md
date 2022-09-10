# EXPERIMENT--01-ALP-FOR-8086
```
Name :J RAKSHITHA DEVI
Roll no:212221230082
Date of experiment :10.09.22
```





## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required:  8086  emulator 
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
ADDITION:


org 100h
MOV AH,05;
MOV BH,03;
ADD AH,BH;
MOV CX,AX;
HLT;
```



## Output  

![image](https://user-images.githubusercontent.com/94165326/189484234-974b8f6c-00da-48e6-a824-3bd0fc1e9edb.png)

![image](https://user-images.githubusercontent.com/94165326/189484244-00cc4fa4-c3e0-4112-b6c5-d943003d03bc.png)

![image](https://user-images.githubusercontent.com/94165326/189484261-bfee442a-8710-41dc-8c11-b9bdf5b8e2bc.png)

![image](https://user-images.githubusercontent.com/94165326/189484270-63618395-22ae-4a85-9c43-37235c0cae99.png)

 
## Subtraction   of 8 bit numbers  ALP 
```
SUBRACTION


org 100h
MOV AH,05;
MOV BH,03;
SUB AH,BH;
MOV CX,AX;
HLT;
```

 
## Output  

![image](https://user-images.githubusercontent.com/94165326/189484293-cfea8966-8327-407f-82ae-08335a799393.png)

![image](https://user-images.githubusercontent.com/94165326/189484301-f845c285-d699-49ca-915c-76653bfb8786.png)

![image](https://user-images.githubusercontent.com/94165326/189484312-cd86879d-8816-4f84-8407-c567201fb29b.png)


## Multiplication alp 
```
MULTIPLICATION


org 100h
MOV AH,05;
MOV BH,03;
MUL AH;
MOV CX,AX;
MOV AX,00;
HLT;
```
 ## Output  
 
 ![image](https://user-images.githubusercontent.com/94165326/189484324-6cf62fdc-9cf1-44bc-b227-442365062357.png)

![image](https://user-images.githubusercontent.com/94165326/189484331-8425cd92-ea96-4966-954d-41e1521a9932.png)

![image](https://user-images.githubusercontent.com/94165326/189484374-eb2d4ed9-b1ed-443b-96d5-73aced884898.png)

![image](https://user-images.githubusercontent.com/94165326/189484377-920f7dc0-733a-4820-9e00-5033365ee7fc.png)



## Division alp 
```
DIVISION
 

org 100h
MOV AH,05;
MOV BH,03;
DIV AH;
MOV CX,AX;
MOV AX,00;
HLT;
```
## Output  

![image](https://user-images.githubusercontent.com/94165326/189484387-19fab5d4-7bfa-4640-8a10-05b5f59d699d.png)

![image](https://user-images.githubusercontent.com/94165326/189484398-8401274a-f177-4b81-98e2-e7616804ebf9.png)

![image](https://user-images.githubusercontent.com/94165326/189484410-be41c64f-6759-4619-882e-b58712f7d6e9.png)

![image](https://user-images.githubusercontent.com/94165326/189484427-bb42882f-b56c-455a-925e-6d74f6c6b525.png)



## Result :

Hence ALP on fundamental arithmetic and logical operations is verified and executed.
 








