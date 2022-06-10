# CSE5462-lab7

## Introduction

This repository includes codes for both UDP client and server implementation. Client will integrate both client and server together. The system will create host based on config.txt file which includes ip address and port number relating to thier location. A proper prompt will print once above situation is detected. 

## Instruction

Within the file folder, runnable executables are provided. However, one can use "Makefile"'s command to compile as well by simple input:
```
make
```
or by typing:
```
gcc -g -Wall -o Drone Drone.c InputUtility.c GridUtility.c -lm
```
Once the executables are generated, type:
```
./Drone (portNumber)
```
to start the program, the (portNumber) decides which port this client is on. 

To establish connection. After this, client can input the message they want to send as their wish. To stop the client, one can simply input:
```
STOP
```

## File explanation

- [Drone.c] - source code of client in c
- [Drone] - executable which is generated by Drone.c
- [InputUtility.c] - source code of utility functions of input data
- [InputUtility.h] - header file for InputUtility.c
- [GridUtility.c] - source code of utility functions of grid calculation
- [GridUtility.h] - header file for GridUtility.c
- [config.txt] - txt file which stores the ip address and port number and thier location
- [Makefile] - makefile, 
- [README.md] - A readme file, which includes instruction and file explanation of this lab.