#SI Lab3 
#Breaking the (easy) shift cipher

Due to the simple nature of the Caesar cipher, it could easily be brute forced by trying all 
possible 25 keys and then looking by eye to see if the plaintext was revealed
(this too can be automated by checking for common English words to see if the solution was probable).
However the much more elegant method of frequency analysis can be used.



This code will calculate the error in statistical frequency 
for each letter squared to generate an error for each possible rotation.
Using a sufficiently long piece of ciphertext this code should accurately reveal the Caesar rotation use. 

The lowest error is for 5 rotations (correctly so) with an error of 0.361318100755,
the next lowest error is 22 rotations with an error of 1.5409364067.
This is ~4.3x difference, which gives a very large degree of confidence to our solution and below is the deciphered text.
