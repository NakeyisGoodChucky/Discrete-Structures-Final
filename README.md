# Discrete-Structures-Final

Analysis of program:
	This is an encryption tool that will take a string from the user and encrypt it using a second string that is inputted from the user as a key.  The encoding works by taking each string element one at time turning it to an uppercase and then encrypting it. When testing we found the limitations to this style of encryption is that when we decode the message the program cannot replicate a case sensitive decryption. The second limitation to our program is in the decryption.  The decryption portion to our program cannot decrypt special characters or symbols. We came up with a “cheat” to get around the problem, the program will check if the element is a special symbol and if it is it will look at the original word and bypass the decryption process. In summary the program works well in all upper case letters but then has some limitations when using lowercase and symbols.

Algorithm:
	The algorithm was applied in the program in two different ways once in encryption and once in decryption. In encryption the algorithm was implemented by using a for loop and applying the formula on the string one element at a time.

Application of course concepts:
	The program utilizes the concepts of encoding and the mathematics if encoding.  We used the formula for the Vigenere Cipher as the base of our program for the encryption and the decryption. 
 
Documentation and programing approaches:
For our project we decided to go with the Vigenere Cipher Decryption.  To start the first week our team began by creating solutions separately by creating our own versions of a program that will encrypt using the Vigenere Cipher.  We then came together and took the best elements from both solutions, combined them, and submitted our rough program to Github.  Then in the second week Jonathan took the program polished it and created a final draft of the code to github. After the final version of the code was submitted by Jonathan we got together discussed the code functionality and found the limitations. Finally in week three I took the code and created the documentation and redmefile. With a week to spare we are ready to submit our project. 

