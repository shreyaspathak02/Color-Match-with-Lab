# hello-world
this is to program an auto match for Lab color number 
There is a set of 7 priamary colors. 

Each color has gradation 0 - 100 and each gradation is defined by a set matrix of three numbers L, a* and b*. 
See example below

Color-  Blue					Yellow
	L	a	b			L	a	b
0	44.12	-32.06	-62.08		0	77.07	-50	74.21	
50	52.31	-45.9	-54.98		50	89.62	-45.25	63.57
100	93.04	-0.65	2.59		100	99.21	-25.96	2.11


There are several new or special colors that can be created by combining these 7 colors in different ways with their different gradations. 

I want to be able to enter the La*b* numbers of any special color and be able to find the best combination of colors/ gradations to provide a formula.
Example: 

"Special House Green" has L = 129.38, a* = -95.9, b* = 19.23

Once the La*b* values above are eneterd in the software/ interface, it should be able to scan all the different color matrix available and output the correct combination required to acheive the above La*b* numbers. 
In this example referencing from the previous example the formula it should ouput be 50 Blue + 0 Yellow. 
	 	L	  a*	  b*
50 Blue 	52.31	-45.9	-54.98
   +		  +	  +	  +	
0 Yellow	77.07	-50	74.21
Total 		129.38	-95.9	19.23
