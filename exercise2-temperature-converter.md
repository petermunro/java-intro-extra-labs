# Chapter 2 Exercise: Temperature Converter

Create a Java program that converts temperatures between Celsius and Fahrenheit scales. This exercise will help you practice using operators, type conversion, and decision-making constructs.

## Requirements:

1. Create a new Java file called `TemperatureConverter.java`.
2. Define a class called `TemperatureConverter` with a `main` method.
3. Use `java.util.Scanner` to get user input.
4. Implement the following functionality:
   a. Prompt the user to enter a temperature value (as a `double`).
   b. Ask the user to specify the input scale (Celsius or Fahrenheit).
   c. Convert the temperature to the other scale.
   d. Print the result of the conversion.
   e. Provide a qualitative description of the temperature (e.g., "freezing", "cold", "warm", "hot").

## Implementation Details:

1. Use appropriate arithmetic operators for the temperature conversion formulas:
   - Celsius to Fahrenheit: (C * 9/5) + 32
   - Fahrenheit to Celsius: (F - 32) * 5/9

2. Use casting when necessary to ensure accurate calculations.

3. Use `if-else` statements to determine which conversion to perform based on user input.

4. Use a `switch` statement or nested `if-else` statements to provide the qualitative temperature description.

5. Format the output temperature to one decimal place.

6. Use constants for any fixed values in your program (e.g., freezing point of water).

7. Implement input validation to ensure the user enters valid data.

## Example Output:

```
Enter a temperature value: 25
Is this temperature in (C)elsius or (F)ahrenheit? C
25.0°C is equal to 77.0°F
This temperature is warm.
Would you like to convert another temperature? (Y/N) Y
Enter a temperature value: 68
Is this temperature in (C)elsius or (F)ahrenheit? F
68.0°F is equal to 20.0°C
This temperature is room temperature.
Would you like to convert another temperature? (Y/N) N
Thank you for using the Temperature Converter!
```

## Bonus Challenges:

1. Allow the user to convert multiple temperatures without restarting the program.
2. Add support for the Kelvin scale.
3. Implement error handling for invalid user inputs.

Remember to use appropriate variable names, add comments to explain your code, and consider edge cases in your implementation.

