# Daily Exercise 25/01/24

### Notes


For these exercises note that the method input returns a `string`

This means that in `userResponse = input("What is your age ")` userResponse will be a string

So in this code:

```
userResponse = input("What is your age ")
print(userResponse + userResponse)
```

If the user inserts `10`, the output with `1010`, because python is adding the 2 strings together

To tell python that we want to use the input as numbers we can use:

```
userResponse = input("What is your age ")
userResponseNumber = int(userResponse)
```

Where the method `int(<string>)` tries to transform a string into an int

Bonus tip, to make the code smaller you can shape your code to ocupy less space, so the code above can be writen as:

```
userResponse = int(input("What is your age "))
```

---

### 1) Calculating things

1) Ask the user to insert a number representing the radius of an circle
	1.1) Knowing that you can calculate the circle area with `3.14 * r^2`, print the area of a circle
	
	1.2) Knowing that you can calculate the perimeter of the circle with `2 * 3.14 * r`, print the perimeter of the circle

---

### 2) Calculating more things

2) Create a program that reads 5 numbers from input
	2.1) Add all the read elements to a list and print that list

	2.2) Calculate and print the biggest number

	2.3) Calculate and print the average of the numbers

	2.4) Add and input asking the user to select if it wants to print the biggest number or the average

---