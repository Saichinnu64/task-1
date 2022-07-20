TASK

Given an integer, , perform the following conditional actions:

If  n is odd, print Weird
If n  is even and in the inclusive range of  to , print Not Weird
If  n is even and in the inclusive range of  to , print Weird
If n is even and greater than , print Not Weird
Input Format

A single line containing a positive integer, .

Constraints

Output Format

Print Weird if the number is weird. Otherwise, print Not Weird.

Sample Input 0

3
Sample Output 0

Weird
Explanation 0


 n is odd and odd numbers are weird, so print Weird.

Sample Input 1

24
Sample Output 1

Not Weird
Explanation 1


 n is even, so it is not weird.
 
 
 CODE
 
 n=int(input())
if(n%2!=0):
    print("Weird")
val=[2,4]
if(n in val):
    print("Not Weird")
val1=[6,8,10,12,14,16,18,20]
if(n in val1):
    print("Weird")
if(n>20):
    if(n%2==0):
        print("Not Weird")
