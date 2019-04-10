#About
   
   Postfix Expressions order is given by the first and secound operands and then given the operator and then does the calculation. 



#Install
  
  	-C++


#How to run
	 
   -- g++ -o test Postfix.cpp
   
   --./test                     //to get the output
   
   --you input a word and you will get the reverse of that word as this is default.


     	Changecase() is a function that is called when the character is equal 42 which is the operator *.
     This changes the case of the letters by using toupper() and tolower().

     	Swap() is a function that is called when the character is equal to 38 which is the operator &. 
     This switches the last letter with the letter that is currently being operated on.
 
     	Add() is a function that is called when the character equals 43 which is the operator +. 
     This goes to the next letter every time it is used. 

	Multiply() is a function that is called when the character is a number between 0-9,
     the number is the operator. This displays the letter as many times as the number.
     So the operator 3 after r would mean r is displayed 3 times. 
	
     Everything else that has not been explained will be ignored by the program.

#Result

	For example you put input: Post+

	You would get this in return: usoP


	Another example you put Input: w+o&r*d2 

	You would get this in return:  Expression evaluates to ddRxo
   

