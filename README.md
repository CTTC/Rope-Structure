# Rope-Structure
The code in this repository illustrate the rope data structure by using the splay tree. The rope structure can store a string and efficiently cut a part of the string and insert it in a different positioin.
The code file cut the substring S[i...j] (i and j are 0-based) from the string and insert it after the k-th symbol of the remaining string. If k = 0, S[i...j] is inserted in the begining.
###Input Format:
* 1st line: string S
* 2nd line: number of queries q
* Next q lines: integers i, j, k

###Output:
final string after q queries


###Example:
Input:
```
hlelowrold
2
1 1 2
6 6 7
```
Output:
```
helloworld
```
Note: in this example, the word goes through these changes: hlelowrold -> hellowrold -> helloworld
