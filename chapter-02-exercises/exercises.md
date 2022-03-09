## Chapter 2 exercises 
:heavy_check_mark: - DONE
:o: - in progress
:x: - can't solve

---
### 01 - Looping a triangle - :heavy_check_mark:
Write a loop that makes seven calls to console.log to output the following triangle:

```
#
##
###
####
#####
######
#######
```
It may be useful to know that you can find the length of a string by writing .length after it.

#### Solution

```
for (let triangle = '#'; triangle.length <= 7; triangle += '#')
console.log(triangle)

```


### 02 - FizzBuzz :o:
Write a program that uses console.log to print all the numbers from 1 to 100, with two exceptions. For numbers divisible by 3, print "Fizz" instead of the number, and for numbers divisible by 5 (and not 3), print "Buzz" instead.

When you have that working, modify your program to print "FizzBuzz" for numbers that are divisible by both 3 and 5 (and still print "Fizz" or "Buzz" for numbers divisible by only one of those).

(This is actually an interview question that has been claimed to weed out a significant percentage of programmer candidates. So if you solved it, your labor market value just went up.)

#### Solution

```
function fizzbuzz(a, b) {
    let fizz = a % 3 === 0;
    let buzz = b % 5 === 0; 
    if 
} console.log()
```


### 03 - Chessboard :o:
Write a program that creates a string that represents an 8×8 grid, using newline characters to separate lines. At each position of the grid there is either a space or a "#" character. The characters should form a chessboard.

Passing this string to console.log should show something like this:
```
 # # # #
# # # # 
 # # # #
# # # # 
 # # # #
# # # # 
 # # # #
# # # #
```
When you have a program that generates this pattern, define a binding size = 8 and change the program so that it works for any size, outputting a grid of the given width and height.

#### Solution