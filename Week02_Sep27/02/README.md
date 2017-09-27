## Sorting "numbers"

This challenge involves sorting an `array` of `integers` and `strings`. We are not worrying about efficiency here, just as long as the thing works.

### Part 1

Create a function which, when given a list of `single-digit integers` in a certain order, returns an `array` of all of the elements that have been `sorted`. If there are repeating elements, put them next to each other.

Sample Input 1: `2, 5, 3, 1` | Output: `1, 2, 3, 5`

Sample Input 2: `9, 2` | Output: `2, 9`

Sample Input 3: `0, 1, 2, 3, 3, 4, 5, 4` | Output: `0, 1, 2, 3, 3, 4, 4, 5`

### Part 2

Add on to the function so that when given a list of strings of single-digit integers in a certain order, it returns an array of the all of the elements sorted.

Sample Input 1: `“one”, “five”, “three”` | Output: `0, 3, 5`

Sample Input 2: `“two”, “two”, “nine”, “zero”` | Output: `0, 2, 2, 9`

### Part 3

Now, amend the function so that it sorts a given list of `both` strings and numbers.

Sample Input 1: `2, “three”, 9, 2` | Output: `2, 2, 3, 9`

Sample Input 2: `“one”, “zero”, 0, 7, “six”` | Output: `0, 0, 1, 6, 7`

### Part 4

Finally, amend the function so that it can sort integers that are `two-digits` as well. For simplicity sake, numbers in the teens will be referred to as “onety-“. Ex. `12` -> `“onety-two”`, `18` -> `“onety-eight”`

Sample Input 1: `“thirty-two”, “onety-five”, 24, 9, “zero”` | Output: `0, 9, 15, 24, 32`

Sample Input 2: `“eighty-four”, 76, “ninety-nine”, 12` | Output: `12, 76, 84, 99`
