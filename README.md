# NextRepo
last repo
next commit

The best way to check the condition in the statement is to use bitmasks. 
Iterate from 0 to 2n−1 and for each number consider its binary representation. 
If the i-th bit of the representation is set to 0, then decide to perform the i-th rotation clockwise. 
In the opposite case, do it counterclockwise. Finally, check if the whole angle is a multiple of 360 and if so, output "YES".
If no good combination of rotations was found, output "NO".

