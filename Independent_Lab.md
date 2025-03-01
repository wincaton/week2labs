# Week 2 Independent Lab Instructions

In this assignment you will create basic code showcasing the concepts you learned about in the tutorial. For this assignment you will create your first notebook with complex processing.


## Descriptive Text

Use Markdown to add descriptive text at the top of your notebook. Include details that inform the reader of the context, purpose, and author of the notebook. For example, you might include: 

* Course Information (e.g., course name, program name, etc.)
* Assignment Name
* Notebook Author Name
* Submission Date

## Celsius to Fahrenheit Conversion 

This notebook will convert celsius to fahrenheit and output the converted values. You will need to rely on the following formula:
> Fahrenheit = (9 / 5) * Celsius + 32

### Step 1

The fist step is to create two variables: `celsius` and `fahrenheit`. One will hold the value of `celsius` and another will hold the value of `fahrenheit`. Assign these each the value of `0.0`.

### Step 2

The second step is to output one line of text welcoming users to your program. Use the text, "Welcome to my Fahrenheit to Celsius converter!" Output another line of text asking the user to provide a value for Celsius. Next, read input from the user.

You can request input from a user by using the function `input()`. In Python 3, input returns a string (`str`). We have to explicitly convert this string to numeric (either `int` or `float`) in order . Hint: revist step 1. 

Example code for the use of this function is provided below. Use a Markdown cell to explain your rationale for selecting either `int` or `float`. 

```
text = int(input("Please provide a value, in Celsius, to convert:\n"))
```

```
text = float(input("Please provide a value, in Celsius, to convert:\n"))
```

Hint: return (enter) will submit user input. 

### Step 3

The third step involves converting the value of celsius into fahrentheit. Assign the value from the user input (`text`) to the variable `celsius`. Using the equation given above, assign the proper value to `fahrenheit`.

### Step 4

On a single line of code, output the following text using string interpolation:

> *c* degrees celsius is *f* degrees fahrenheit.

Where *c* is the value the user provided and *f* is the converted value. So, it should look like

> 0 degrees celsius is 32 degrees fahrenheit.

## Check your work 

You can use the following table to check your work. These are common temperatures. Run your code three times and input one of the values from the table below. 


| C | F | Description |
|:---:|:---:|:---|
| -40 | -40 | Temperature where both are equal |
| -18 | 0 | 0-degrees F |
| 0 | 32 | Freezing, or 0-degrees C |
| 37 | 98.6 | Body temperature |
| 100 | 212 | Boiling point of water at sea level |


## Type conversion

Using type conversion, change the type of `fahrenheit` to `int` and save it as a new variable named `int_fahrenheit`. Output this variable and check the data type. 

## Run your code and submit your notebook

Run all cells in your notebook and use `37` as your input value. Save your notebook with output from your code cells.
