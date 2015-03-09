#Ardui-O-Art Software Operation Guide

There are basically 2 Programs through which ArduiOArt will operate.
	[1] Arduino Code
	[2] C#.NET Code

[1] Arduino Code
	Arduino Code is resposible movement  of motors. 
	There are two modules in arduino code:
		1- It take stream of 0 & 1 serially from C#.NET Code
		2- Manipulate that data as per logic	 

[2] C#.NET Code
	Simple explanation of C#.NET Code step by step.
		1- It take .bmp(Bitmap file) file as Input
		2- It create 2 things after reading .bmp file
			[1] One .txt(Text File) which have series of 0 and 1 (0 for White & 1 for Black). Generally this 			file is use for debugging purpose
			[2] One two dimentional array which have 0 and 1 as per image (0 for White & 1 for Black). 			This file is sent as a stream of 0 & 1 as serial input to Arduino.
		3- After sending all data to Arduino program ends

  
