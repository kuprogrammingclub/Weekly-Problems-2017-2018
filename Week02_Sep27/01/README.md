## Two Characters

String `x` always consists of two alternating characters. That is, if string `x` had the distinct characters `a` and `b`, 
then some possible values for `x` are `abababab`, or `babab`, but not `aabbaabb` or `aabaaabbbb`. Note that the two characters
do not necessarily need to be `a` and `b`. For convenience, we can also assume we will only be dealing with lowercase letters
(a-z) in this type of string.

Let's also call any string with this property an `alternating` string.

### Part 1

Create a function which, when given a string, returns `true` if the string is `alternating`, or `false` if it isn't.

Sample Input 1: `stststs` | Output: `true`

Sample Input 2: `abcabcabc` | Output: `false`

Sample Input 3: `qrrq` | Output: `false`

Sample Input 4: `u` | Output: `true`

### Part 2

Create another function which, when given a string, returns the longest substring of itself which is `alternating`.
If there are multiple alternating substrings of the same length, return the one that appears first.

Sample Input 1: `alabama` | Output: `ala`

Sample Input 2: `hakunamatata` | Output: `tata`

Sample Input 3: `mfmmfmfmmfmf` | Output: `mfmfm`

Sample Input 4: `abcdefghijklmnop` | Output: `ab`

Sample Input 5: `fffffffff` | Output: `f`

### Part 3

Create another function which takes in a string. This time, we're allowed to remove exactly one character from the string
(if we want to) in order to find the longest `alternating` substring. So, given a string, remove zero or one characters from it
and then find the longest substring possible which has the `alternating` property. It's possible that defining the one that
appears "first" in this case would be complicated to define, so for this method return the length of the longest `alternating`
substring.

Sample Input 1: `ohio` | Output: `3`

Sample Input 2: `sestettes` | Output: `4`

Sample Input 3: `abdababc` | Output: `6`

Sample Input 4: `kukukuku` | Output: `8`

### Part 4

Expanding on Part 3, we want to modify the input string in some way to find the longest substring. This time, we are allowed
to do exactly one of the following: Either remove exactly one character (as before), add another character somewhere in the
string (either at the start, anywhere in the middle, or at the end), or changing a character already in the string to something
else. You can only choose one of these, and you're only allowed to modify one character. Using these rules, find the longest
substring possible by modifying the original string.

Sample Input 1: `abracadabra` | Output: `5`

Sample Input 2: `inning` | Output: `6`

Sample Input 3: `ammmazing` | Output: `5`

Sample Input 4: `minimize` | Output: `6`

Sample Input 5: `hehehe` | Output: `7`

## Have fun!

Adapted from
https://www.hackerrank.com/challenges/two-characters

(Hey, if you want another challenge, the problem from the source is pretty fun to do!)
