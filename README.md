Download Link: https://assignmentchef.com/product/solved-cecs326-homework-24
<br>
Chapter 14 (Page 11 through 18)

Purpose: This assignment provides experience with encryption.

<ul>

 <li>Get a copy of the instructors c program.</li>

</ul>

Compile it and run it. Make sure you can explain what the program prints. (Don’t turn anything in for this part.)

<ul>

 <li>Redo homework 2 (c) (yet again).</li>

</ul>

<ol>

 <li>As you make the copy, encrypt (or decrypt) each block before you write it. The key may be embedded inthe code (like my example).</li>

 <li>Add a fourth commandline parameter to your c. If the argv[3][0] is ’e’ encrypt while doing the copy. Otherwise decrypt.</li>

</ol>

Hint: place an if statement before you start the copy, set a variable to either DES_ENCRYPT or DES_DECRYPT. Use the variable in your copy.

Example:

a.out encrypt.c crypted_file e Produces an encrypted version of encrypt.c

a.out crypted_file encrypted_copy.txt d

Produces an encrypted version of crypted_file (which should be identical to the original file).

File: encrypt.c is a copy of what I used in lecture. It should compile and run.


